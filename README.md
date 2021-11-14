# MASc project (FISH Codes - a language similar to Java)
Code to model seals for tunnels in underground nuclear waste repositories.         
The Master file defines global input variables for the program. It also calls other modules (final_mesh, assign_properties, initialize_stresses, thermal_analysis_stress_evolution_hitory).       
The second module final_mesh makes geometry of a square tunnel as shown in the figure below. It also creats three shapes of seals (trapezoid, triangular and rectangular) around the tunnel. Only trapezoid shape of the seal is shown in the figure below. In order to make the seal this module calls the modules cutoff_final and grouping_flac_mesh.      
![image](https://user-images.githubusercontent.com/61520478/141703633-5d674c6e-748c-414a-90ed-6f1c07e0a6a7.png)
