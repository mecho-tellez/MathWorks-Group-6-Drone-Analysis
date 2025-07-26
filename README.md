# MATHWORKS Group 6 - Engineering Pathway Program Drone Analysis

Project description: Design a lightweight, quadcopter delivery drone that is able to maximize the payload mass without compromising stability or the integrity of the frame.

Parameters: Drone must weight less than 2 kg and the motors can provide at most 1 kg of thrust.

Methods: We designed a drone frame by creating a schematic in AutoCAD and a 3D model in SolidWorks. Using the geometry of each part of the frame and the density of the material, we calculated the weight of each part and found the total mass of the drone by combining all of the masses. We were able to then find the net upward force available from the motors by doing summation of forces in the y-direction of a FBD of the drone and used that value to calculate the maximum payload capacity that will still keep the drone in equilibrium. We also validated that the center of mass would align with the center of moments of the arms to ensure an even lift-off. We then analyzed the arms to see if the forces acting on the arms would cause it to break or cause and permanent bending by measuring the shear and moments.

Results:
- Net force available from motors: 24.074 N
- Estimated weight of drone: 1.56 kg
- Maximum payload capacity: ~2.454 kg = ~5.41 lbs
- Center of mass with payload: 7.664 in from the front

Breakdown of what each student did:
- Huy Tran: Modeled the 2D model into a 3D model using Solidworks. Conducted research on materials and assisted in selecting the materials for the drone.
- Victor Espinoza: Created 2D schematic of frame and parts, calculated the total weight and the remaining thrust to carry the payload, estimated the maximum payload, calculated the center of mass to align with the center of moments, calculated shear and moments of drone arms by creating a cut down the center of the arm.
- Allen Kuo: Added motors, propellers, tie down, and overwrote weight to the assembly. Calculated drone weight without tie down parts. Tried to include Simulink and possible animation, but only got as far as adding a single set of forces and torque to the airframe before getting stuck.
- Ernesto Tellez Perez: Modeled and calculated the drone arm as a cantilever. Found the general equation for the shear and moment of the drone arm in variable form. Programmed the MATLAB Analysis with plots of shear and moment using relevant dimensions and constants. Researched and found the speed and flight controller for the drone. Calculated the centroid of the drone.

Folders and What They Hold: 
- src/ : Holds the MATLAB code 
- media/ : Holds the MATLAB plots of shear and moment for both types of arms in the Drone model, orthographic drawings for the drone frame, files for the 3d model, hand manual calculations, and images of the final model.

  - The MATLAB code is ready to run through MATLAB and return the plots of shear and moment for the drone arms. If dimensions or constants are to be changed, the variables are easily accessible and editable to match design changes.
  - The 3d model can be opened through media/Final Drone Assembly.html
    
<img width="739" height="879" alt="image" src="https://github.com/user-attachments/assets/900ddc46-be77-4ccf-a7d7-7a2bf89f56c8" />

<img width="729" height="846" alt="image" src="https://github.com/user-attachments/assets/2865cf3a-040f-4da3-9fd8-e30628b12b58" />

