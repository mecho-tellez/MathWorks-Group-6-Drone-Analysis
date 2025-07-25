# MATHWORKS Group 6 - Engineering Pathway Program Drone Analysis

Project description: The purpose of our project was to design a drone, calculate its thrust and moments, predict the performance of the drone, and calculate the possible payload that it can handle.

Methods: We designed a drone frame using AutoCAD and SolidWorks. Using the geometry of each part of the frame and the density of the material, we calculated the weight. Using the weights and thrust of the motors, we were able to find the remaining thrust left for carrying the payload.  Then we analyzed the arms to see if the forces acting on the arms would cause it to break or cause and permanent bending.

Breakdown of what each student did:
- Huy Tran: Modeled the 2D model into a 3D model using Solidworks. Conducted research on materials and assisted in selecting the materials for the drone.
- Victor Espinoza: Created 2D model of frame and parts, calculated the total weight and the remaining thrust to carry the payload, estimated the maximum payload, calculated the center of mass to align with the center of moments, calculated shear and moments of drone arms
- Allen Kuo: Added motors and propellers to the assembly. Tried to include Simulink and possible animation, but only got as far as adding a single set of forces and torque to the airframe before getting stuck.
- Ernesto Tellez Perez: Modeled and calculated the drone arm as a cantilever. Found the general equation for the shear and moment of the drone arm in variable form. Programmed the MATLAB Analysis with plots of shear and moment using relevant dimensions and constants. Researched and found the speed and flight controller for the drone. Calculated the centroid of the drone.

Folders and What They Hold: 
- src/ : Holds the MATLAB code 
- media/ : Holds the MATLAB plots of shear and moment for both types of arms in the Drone model, orthographic drawings for the drone frame, files for the 3d model, and images of the final model.

  - The MATLAB code is ready to run through MATLAB and return the plots of shear and moment for the drone arms. If dimensions or constants are to be changed, the variables are easily accessible and editable to match design changes.
  - The 3d model can be opened through ........................
