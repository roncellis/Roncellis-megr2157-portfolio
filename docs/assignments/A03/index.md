# A3 – [Topic]

## Objective

Use axial deflection modeling to design its dimensions
Use parametric design to determine a bars length
Introduce you to FEA (Finite Element Analysis)
Introduce you to linking dimensions to appropriate parameters in CAD.
Compare and contrast the different analysis

## Step 1 – Parametric Bar Design

For the first part of this assignment, I designed a bar with a circular cross-section based on the given material, loading, and maximum deflection requirements. I selected an initial diameter for the bar and calculated its cross-sectional area. I then used the direct tension elongation equation from Machinery’s Handbook to determine whether the dimensions would satisfy the design requirements.

After completing my initial calculations, I created the bar in CAD by sketching the circular cross-section and extruding it to the required length.

To make the model parametric, I defined the important dimensions using parameters and equations. This allows the geometry of the bar to automatically update whenever one of the design values is changed instead of having to manually rebuild the model.

<img width="1999" height="1545" alt="image" src="https://github.com/user-attachments/assets/80a1feb0-ec3f-4628-9815-cc6112259d15" />


<img width="1999" height="1545" alt="image" src="https://github.com/user-attachments/assets/62bebaa3-a85c-4467-8fdb-c3a7bfacf2ce" />


## Step 2 – FEA Simulation

For the FEA portion of the assignment, I applied a fixed constraint to one end of the bar and applied the required load to the opposite end. These boundary conditions were used to represent how the bar would behave under the specified loading condition.

After setting up the material, constraints, and load, I ran the simulation and examined the Von Mises stress results. I compared the maximum stress produced by the simulation with the allowable stress and material yield strength to determine whether the design was safe.

Maximum Von Mises Stress: 8,709 psi

Based on the simulation results, the bar remained below the maximum allowable stress of 40,000 psi. The resulting factor of safety was approximately 4.59 , indicating that the bar meets the stress requirement.

[Insert Von Mises stress FEA image here]

I also examined the displacement results from the simulation. The maximum displacement was [YOUR VALUE] inches, which I compared with the maximum allowable deflection of 0.009 inches.

Because the simulated displacement was below the allowable limit, the bar satisfied the deflection requirement.
## Decide


## Communicate

