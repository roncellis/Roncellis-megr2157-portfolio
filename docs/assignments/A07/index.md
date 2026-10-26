# A7 – FEA on Bracket

## Objective
The purpose of this assignment is to improve the bracket design created in Assignments #5 and #6 by using finite element analysis (FEA). The main goal is to optimize the bracket for strength, stiffness, and weight while keeping the original assigned material.

The design requirements from Assignment #5 include a 600 lbf applied load, Aluminum 6061-T6 with a yield strength of 35,000 psi, a Young’s modulus of 10,000,000 psi, a safety factor of 4, and a maximum allowable deflection of 0.005 in.

Three different bracket designs will be analyzed using static stress simulations with proper loads, constraints, and mesh settings. The stress, displacement, and safety factor results will be evaluated to ensure mesh convergence within a 7% difference, as required by the assignment. These results will help identify areas for improvement and guide design changes to achieve a stronger, stiffer, and lighter bracket.

<img width="1007" height="896" alt="image" src="https://github.com/user-attachments/assets/c96ffe9c-cba8-4b6e-9671-1bb0b1f1a9b8" />

<img width="1396" height="1199" alt="image" src="https://github.com/user-attachments/assets/e7002b18-0df6-4110-aa91-98050d26d620" />

<img width="1356" height="1090" alt="image" src="https://github.com/user-attachments/assets/63f76df5-d8bc-43c6-a6b3-d9c29115d95d" />

<img width="1347" height="1114" alt="image" src="https://github.com/user-attachments/assets/3f26983b-f62a-4baa-85a8-6db4de7bd114" />

The initial bracket design had a mass of approximately 1.33 lb, a factor of safety of 1.4, a maximum stress of 25,000 psi, and a maximum deflection of 0.0046 in. Although the deflection was within the allowable limit of 0.005 in, the factor of safety was below the required value of 4, indicating that the design needed further improvements to meet the strength requirements.

## Design I: Increase Shaft Diameter
For my first design, I increased the shaft diameter from the original 1.22 inches to improve the bracket's stiffness and strength. I kept the assigned Aluminum 6061-T6 material and the 600 lbf load. After making the geometry change, I performed a static stress analysis and compared the results from different mesh sizes.

I checked the maximum stress, maximum displacement, and factor of safety using the percentage-difference formula. The geometry remained unchanged during each mesh comparison. If all three results converged within 7%, I used those results to evaluate the design. If they did not converge after three attempts, I used the results from the finest mesh, following the assignment instructions. Iteration 1
<img width="1054" height="975" alt="image" src="https://github.com/user-attachments/assets/ecd55a17-de55-4120-a2d7-ead31b1e0572" />

Mistake Identified

While working on my next design iteration, I noticed that the applied force in my simulation was incorrect. The load was supposed to be 600 lbf based on my Assignment #5 and #6 requirements, but it had not been set properly. Because of this mistake, my previous simulation results were inaccurate and could not be used for comparison.

After identifying the issue, I corrected the applied load before continuing with the analysis. Although this required me to redo part of the simulation process, I had gained a better understanding of how to properly set up the FEA and was able to work more efficiently moving forward.

I also developed an Excel calculator to help speed up the mesh convergence calculations. The calculator allowed me to quickly determine the percentage differences in maximum stress, displacement, and factor of safety between mesh results. This made it easier to organize my data and verify that the results were within the required 7% difference.

Initial Results
- Material: Aluminum 6061-T6
- Applied Load: 600 lbf
- Maximum Allowable Deflection: 0.005 in
- Yield Strength: 35,000 psi
- Required Factor of Safety: 4

## Iteration 1: 2 in Diameter
Maximum stress = 2.60 × 10³ psi

Maximum deflection = 2.50 × 10⁻² in

Factor of safety = 13.46

The stress percentage difference was 23.61%, the deflection percentage difference was 32.43%, and the factor of safety percentage difference was 23.61%. These results were outside the required 7% convergence limit, so I needed to continue refining the mesh before proceeding to the next geometry change.

## Iteration 2: 1.9 in Diameter
Iteration 2: 1.9 in Diameter
Maximum stress = 1,855 psi

Maximum deflection = 0.02935 in

Factor of safety = 18.87 (calculated from yield strength divided by maximum stress)

The reported stress percentage difference was 11.39%, the deflection percentage difference was 16.76%, and the safety factor percentage difference was 26.85%. These differences exceed the required 7% convergence limit, indicating that the mesh results had not converged. The maximum deflection also exceeded the allowable limit of 0.005 in. Comparing the 1.9-inch design with the 2.0-inch design suggests that reducing the shaft diameter increased deflection, so stiffness remains an important consideration. iteration 2 ##

## Iteration 3: 1.85 in Diameter

## Final Mesh-Validation Attempt: 1.85 in Diameter
The maximum stress percentage difference was 1.5%, the maximum deflection percentage difference was 8.55%, and the factor of safety percentage difference was 80.81%. The stress results were within the required 7% limit, but the deflection and factor of safety results were not. Since this was the third attempt, I used the results from the finest mesh for the next design stage, as specified in the assignment.

These results will serve as the baseline for the next design iteration:

Maximum Stress: 2,048 psi
Maximum Deflection: 0.03187 in
Factor of Safety: 17.09 (calculated using 35,000 psi divided by 2,048 psi)
Mass: 1.34 lb

## Design II: Adding Fillets
<img width="933" height="858" alt="image" src="https://github.com/user-attachments/assets/dd7f4a73-467c-48e1-8266-e7564f86de35" />
I added 0.10-inch fillets to the inner and back edges of the bracket to reduce stress concentrations. I then ran the simulation using a fine mesh to evaluate how the changes affected the maximum stress, maximum deflection, and factor of safety.

## Iteration 1: 0.10 in Fillet
Maximum Stress: (3.316 \times 10^2) psi
Maximum Deflection: (7.108 \times 10^{-3}) in
Factor of Safety: (4.177 \times 10^6)
The percentage differences were 144% for maximum stress, 127% for maximum deflection, and 111% for the factor of safety. These results were outside the required 7% convergence limit, so I needed to continue checking the mesh. Even a small change to the bracket's geometry can significantly affect the calculated stress and deflection. I will compare the results from different mesh sizes before proceeding to the next iteration.

## Iteration 2: 0.02 in Fillet

For this iteration, I reduced the fillet size to 0.02 inches to see how a smaller fillet affected the bracket's stress, deflection, and factor of safety.

Maximum Stress: (2.8 \times 10^4) psi
Maximum Deflection: (4.6 \times 10^{-3}) in
Factor of Safety: 1.25
The smaller fillet leaves a sharper transition around the corners, which can increase stress concentrations compared with a larger fillet. I will compare different mesh sizes on this same geometry to check whether the maximum stress, deflection, and factor of safety converge within the required 7% difference. If the results do not converge after three attempts, I will use the results from the finest mesh before proceeding to the next design change. iteration 3
## Iteration 3: 0.001 in Fillet
For this iteration, I reduced the fillet size to 0.001 inches to evaluate how a much smaller fillet affected the bracket's stress, deflection, and factor of safety.

Maximum Stress: (3.2 \times 10^4) psi
Maximum Deflection: (4.8 \times 10^{-3}) in
Factor of Safety: 1.09
Mass: 1.48 lb
The results show that the smaller fillet can increase stress concentrations around the corners. After the third mesh-convergence attempt, I would use the results from the finest mesh if the values did not converge within the required 7% difference. These results would then become the baseline for Design III, where I would focus on reducing the bracket's mass while maintaining sufficient strength and stiffness.

## Design III: Removing Material
<img width="1218" height="1125" alt="image" src="https://github.com/user-attachments/assets/fa97915c-d2f2-478f-80b6-4f08a2abb194" />
For my third design, I added two circular holes with a 0.5-inch radius to reduce the bracket's mass while maintaining its strength and stiffness. I then evaluated how removing material affected the maximum stress, maximum deflection, and factor of safety.

## Iteration 1: 0.5 in Radius Holes
Maximum Stress: (2.9 \times 10^4) psi
Maximum Deflection: (5.1 \times 10^{-3}) in
Factor of Safety: 1.21
Mass: 1.29 lb
Removing material reduced the overall mass of the bracket, but the holes may also introduce stress concentrations around their edges. I would compare different mesh sizes on this geometry to check whether the maximum stress, deflection, and factor of safety converge within the required 7% difference. If the results do not converge after three attempts, I would use the results from the finest mesh. The final design should balance weight reduction with adequate strength and stiffness.


## Communicate
This assignment gave me a better understanding of how finite element analysis (FEA) can be used to evaluate and improve a mechanical design. Throughout the process, I learned how modifying the geometry of a bracket can impact its stress, displacement, factor of safety, and overall mass. I also learned that adding fillets can help minimize stress concentrations, while creating holes can reduce weight but may also weaken certain areas of the bracket.

One of the biggest things I learned was the importance of mesh convergence. I realized that using different mesh sizes can produce different results, which is why it is necessary to compare them before making changes to the design. I also gained a better understanding of why stress, displacement, and factor of safety must all be evaluated to determine whether a design meets the required specifications.

Another important takeaway was learning how to balance strength, stiffness, and weight. Reducing the mass of a bracket does not always mean the design is better, especially if it leads to higher stress or greater deflection. I also learned the importance of double-checking my simulation setup, including the applied forces and constraints, to avoid errors that could affect my results. Moving forward, I plan to use what I learned from this assignment to make better design decisions and improve the accuracy of my simulations.

The total time I spent completing this assignment was 7 hours.
