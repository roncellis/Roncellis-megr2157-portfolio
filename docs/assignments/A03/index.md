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
<img width="2000" height="2588" alt="image" src="https://github.com/user-attachments/assets/2d4db0e8-9849-48c3-a0c8-f5d40e6582b6" />

<img width="1999" height="1545" alt="image" src="https://github.com/user-attachments/assets/80a1feb0-ec3f-4628-9815-cc6112259d15" />


<img width="1999" height="1545" alt="image" src="https://github.com/user-attachments/assets/62bebaa3-a85c-4467-8fdb-c3a7bfacf2ce" />


## Step 2 – FEA Simulation

For the FEA portion of the assignment, I applied a fixed constraint to one end of the bar and applied the required load to the opposite end. These boundary conditions were used to represent how the bar would behave under the specified loading condition.

After setting up the material, constraints, and load, I ran the simulation and examined the Von Mises stress results. I compared the maximum stress produced by the simulation with the allowable stress and material yield strength to determine whether the design was safe.

Maximum Von Mises Stress: 8,709 psi

Based on the simulation results, the bar remained below the maximum allowable stress of 40,000 psi. The resulting factor of safety was approximately 4.59 , indicating that the bar meets the stress requirement.



I also examined the displacement results from the simulation. The maximum displacement was 0.008970 inches, which I compared with the maximum allowable deflection of 0.009 inches.

Because the simulated displacement was below the allowable limit, the bar satisfied the deflection requirement. 
<img width="1999" height="1545" alt="image" src="https://github.com/user-attachments/assets/4cce6652-1d32-4a42-a695-259df213438b" />. 
<img width="1999" height="1545" alt="image" src="https://github.com/user-attachments/assets/a02c9a29-0d3f-44a7-8580-462f252c193f" />


## Step 3 – Comparing Calculations and FEA

After completing the FEA simulation, I compared the simulation results with my hand calculations. The percent difference between the two methods was 0.009.

The results were close because both methods analyze the same basic mechanical behavior. The bar has a uniform cross-section and is subjected to a relatively simple loading condition, which allows the theoretical equations to represent the physical behavior of the model well.

Although FEA provides a more detailed representation of stress and deformation throughout the part, hand calculations are still important because they provide a way to verify that the simulation results are reasonable.



Bar With Hole

For the next part of the analysis, I added the required hole to the bar and ran the simulation again. Adding the hole changed the stress distribution because removing material created a stress concentration around the opening.

The new maximum stress was 40,000 psi, which was still below the maximum allowable stress of 40,000 psi. The resulting factor of safety was approximately 4.59.

This showed that even with the additional stress concentration caused by the hole, the redesigned bar still satisfied the required stress criteria.

## Step 4 – Reflection / Lessons Learned

This assignment helped me better understand the relationship between hand calculations, parametric CAD modeling, and finite element analysis. Instead of only calculating stress and deformation using equations, I was able to create a physical model and use FEA to visualize how the part responds to loading.

I also learned how important it is to correctly set up the material properties, loads, constraints, dimensions, and units before running a simulation. Even a small mistake in the setup can produce results that appear incorrect and make it difficult to determine whether the problem comes from the design or the simulation itself.

The parametric portion of the assignment was also useful because it showed me how equations and dimensions can be connected within a CAD model. This makes modifying and testing different designs much faster because changing one parameter can automatically update the model.
<img width="2000" height="2588" alt="image" src="https://github.com/user-attachments/assets/09e78ac0-ab86-4bfc-93e2-7bb5abb2a7f8" />

Overall, this assignment improved my understanding of how analytical calculations and computer simulations can be used together to verify an engineering design.

Time spent completing assignment: 7 hours.


