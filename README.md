# Drone-Payload-Capacity-and-Structural-Design-Analysis
Team #9

Objective

This project evaluates two drone arm designs and six materials to figure out the best combination for maximizing payload capacity.

MATLAB is used for
- Thrust-to-weight analysis
- Finite element analysis (FEA)
- Image processing and visualization

The analysis requires a minimum payload of 0.5 kg and a minimum thrust-to-weight ratio of 2:1.

Requirements

- MATLAB
- Partial Differential Equation Toolbox
- Image Processing Toolbox
- CAD software capable of exporting STL/STEP files
- `droneArmMaterials.mat`

The material file contains density, Young's modulus, Poisson's ratio, yield strength, and cost data for six materials.

How to Run

1. Open MATLAB and set the project folder as the current directory.
2. Make sure `droneArmMaterials.mat`, MATLAB scripts, and CAD/STL files are available.
3. Run the thrust-to-weight analysis script.
4. Run the FEA scripts for the drone arm designs.
5. Review the generated tables, structural results, and visualizations.

The thrust-to-weight analysis evaluates all 12 design/material combinations.

Reproducing Results

The analysis uses the following assumptions:


                      
 Motors = 4, 
 Maximum thrust/motor = 1 kg, 
 Base drone mass = 1 kg, 
 Minimum payload  = 0.5 kg, 
 Minimum T/W ratio = 2:1,
 Gravity = 9.81 m/s² 

The FEA models apply motor thrust, drone/payload weight, and gravity to each arm. Maximum displacement, von Mises stress, and factor of safety are then calculated.

Running the provided MATLAB scripts with the same input files and assumptions will reproduce the project results.
