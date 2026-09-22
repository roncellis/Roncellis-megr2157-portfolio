# A5 – Design for Strength and Stiffness I

## Assignment Requirements
Applied load: F = 600 lbf
Safety factor: SF = 4
Material: Aluminum 6061-T6
Yield strength: Sy = 35,000 psi
Young's modulus: E = 10,000,000 psi
Maximum allowable deflection: δmax = 0.005 in
Direct shear failure is neglected as required by the assignment.
The bracket is designed symmetrically.
Features A through E are analyzed for both stress and stiffness. 

<img width="323" height="238" alt="image" src="https://github.com/user-attachments/assets/baec9675-0533-4d9f-b5d1-782c8143f99b" />



## Objective

The purpose of this assignment was to develop a bracket using the conceptual design provided in Appendix B. The bracket was designed to support a horizontal load applied evenly through the polyester strap specified in Resource #1.

The bracket design was separated into five individual features, labeled A through E in Appendix C. Each feature was evaluated for strength and stiffness to determine the dimensions needed to meet the design requirements.



## Analyze

## Design Requirements
Applied load: F = 600 lbf
Safety factor: SF = 4
Material: Aluminum 6061-T6
Yield strength: Sy = 35,000 psi
Young's modulus: E = 10,000,000 psi
Maximum allowable deflection: δmax = 0.005 in
Direct shear failure is neglected as instructed in the assignment.
The bracket is designed symmetrically.
The T beam is treated as rigid.
The loading is treated as static.
## Allowable Stress
σallow = Sy / SF

σallow = 35,000 psi / 4

σallow = 8,750 psi

## Material Selection Justification

Aluminum 6061-T6 was chosen because it offers a good combination of strength, stiffness, low weight, and ease of machining. With a yield strength of 35 ksi and an elastic modulus of 10 Msi, the material provides the properties needed for the bracket design. Although steel and titanium provide greater strength, their additional weight and cost are not necessary for this application. Aluminum 6061-T6 satisfies the design requirements while also being suitable for manufacturing the bracket geometry.

## Overall Analysis Approach

The bracket was separated into five features, labeled A through E. Each feature was evaluated using the strength-of-materials method that best represented its loading condition. Stress and stiffness were both analyzed to determine whether each feature could safely support the applied load while maintaining the required rigidity. 
Here’s a reworded version that keeps the same engineering meaning but sounds more natural and original:

# Feature A – Cantilever Beam

Based on the design requirements provided in Appendix D, Feature A was analyzed as a cantilever beam.

## Feature A – Stress Analysis

### Given

* Applied force, F = 600 lbf
* Safety factor, SF = 4
* Yield strength, Sy = 35,000 psi
* Allowable stress, σallow = 8,750 psi
* Feature A length, LA = 3.00 in
* Circular cross section

### Find

* Required minimum diameter, dA

### Assumptions

1. Feature A behaves as a cantilever beam fixed at one end.
2. The 600 lbf force acts at the free end of the feature.
3. The bracket geometry and loading are symmetric.
4. Feature A has a uniform circular cross section.
5. Failure caused by direct shear is not considered.
6. The applied force is treated as a static load.
7. The material is assumed to remain within its elastic limit.
8. The T-beam is assumed to behave as a rigid member.
9. A design safety factor of 4 is applied.

### Free-Body Diagram



<img width="1095" height="1437" alt="image" src="https://github.com/user-attachments/assets/005a04fc-564f-4a2d-aad2-096c43f29588" /> 


<img width="1091" height="1441" alt="image" src="https://github.com/user-attachments/assets/76c38396-9108-4ede-b6c4-d85f64490fdd" />

## Final Stress Dimension
dA,stress = 1.28 in

## Feature A – Cantilever Beam

Based on the design requirements provided in Appendix D, Feature A was analyzed as a cantilever beam.

## Feature A – Stress Analysis
## Given
Applied force, F = 600 lbf
Safety factor, SF = 4
Yield strength, Sy = 35,000 psi
Allowable stress, σallow = 8,750 psi
Feature A length, LA = 3.00 in
Circular cross section
## Find
Required minimum diameter, dA
Assumptions
## Feature A behaves as a cantilever beam fixed at one end.
The 600 lbf force acts at the free end of the feature.
The bracket geometry and loading are symmetric.
Feature A has a uniform circular cross section.
Failure caused by direct shear is not considered.
The applied force is treated as a static load.
The material is assumed to remain within its elastic limit.
The T-beam is assumed to behave as a rigid member.
A design safety factor of 4 is applied.
## Free-Body Diagram
<img width="1098" height="1433" alt="image" src="https://github.com/user-attachments/assets/b98b3436-3e72-40d1-8e11-abcb028994e2" />

## Governing Requirement
Strength governs Feature A.
## Final Feature A Dimension
dA = 1.28 in


## Feature B – Axially Loaded Bar

According to the requirements in Appendix D, Feature B is analyzed as a member subjected to axial loading.

## Feature B – Stress Analysis
## Given
Applied force, F = 600 lbf
Axial force, PB = 2F = 1,200 lbf
Safety factor, SF = 4
Yield strength, Sy = 35,000 psi
Allowable stress, σallow = 8,750 psi
Feature B width, wB = 1.00 in
## Find
Required cross-sectional area, AB
Required thickness, tB
## Assumptions
Feature B carries the applied force as an axial member.
The force is distributed through a symmetric load path.
The resulting axial load is PB = 2F = 1,200 lbf.
Feature B has a rectangular cross section.
Failure due to direct shear is not considered.
The applied force is assumed to be static.
The material is assumed to behave elastically.
A design safety factor of 4 is applied.
## Free-Body Diagram and Calculations
<img width="1099" height="1431" alt="image" src="https://github.com/user-attachments/assets/d2b3562a-c8c4-41d7-8700-d56d45e367ae" /> 
<img width="1309" height="1201" alt="image" src="https://github.com/user-attachments/assets/6b0623ff-01a9-4380-8cfb-29baa54c67a1" />

## Numerical Solution

AB = 1200 / 8750 = 0.1371 in²

tB = 0.1371 / 1.00 = 0.1371 in

## Final Stress Dimension

tB,stress = 0.1371 in

## Feature B – Stiffness Analysis
## Given
Axial force, PB = 1,200 lbf
Feature B length, LB = 2.00 in
Elastic modulus, E = 10,000,000 psi
Maximum deflection, δmax = 0.005 in
Feature B width, wB = 1.00 in
## Find
Required minimum cross-sectional area
Required minimum thickness, tB
## Assumptions
Feature B is analyzed as a member subjected to axial loading.
Deformation caused by shear is assumed to be insignificant.
The material is assumed to behave elastically under the applied load.
The applied force is considered static.
Feature B has a uniform rectangular cross section.
Axial displacement is limited to a maximum of 0.005 in.
## Free-Body Diagram and Calculations 
<img width="1109" height="1419" alt="image" src="https://github.com/user-attachments/assets/09f2ec58-1d52-4c29-8f51-d36b574c9847" />

## Numerical Solution

AB = (1200)(2.00) / (10,000,000)(0.005)

AB = 0.0480 in²

tB = 0.0480 / 1.00

tB = 0.0480 in

## Design Comparison

Stress-based thickness = 0.1371 in

Stiffness-based thickness = 0.0480 in

Since 0.1371 in > 0.0480 in, the stress-based thickness controls the design.

## Governing Requirement

The strength governors Feature B.

## Final Feature B Dimensions

tB = 0.14 in
## Decide

## Feature C – Simply Supported Beam
Appendix D specifies that Feature C is treated as a simply supported beam with a concentrated load at the center.

## Feature C – Stress Analysis
## Known
F = 600 lbf
LC = 4.00 in
wC = 1.00 in
SF = 4
Sy = 35,000 psi
σallow = 8,750 psi
## Unknown
Minimum beam thickness, tC
## Assumptions
Feature C is modeled as a simply supported beam.
The load is concentrated at the center.
The beam is symmetric.
The cross section is rectangular.
Direct shear failure is neglected.
The load is static.
The material remains in the elastic range.
A safety factor of 4 is used.
## Free Body Diagram 
<img width="1118" height="1407" alt="image" src="https://github.com/user-attachments/assets/e6721e66-f1f4-4216-b448-d5a7249bbc8b" />

##  Numerical Solution
Mmax = (600)(4.00) / 4

Mmax = 600 lbf·in

tC = [6(600) / (1.00)(8,750)]^(1/2)

tC = 0.642 in

## Final Stress Dimension
tC,stress = 0.642 in

## Feature C – Stiffness Analysis
## Known
F = 600 lbf
LC = 4.00 in
wC = 1.00 in
E = 10,000,000 psi
δmax = 0.005 in
## Unknown
Minimum beam thickness, tC
## Assumptions
Feature C is modeled as a simply supported beam.
The load is concentrated at the center.
The beam is symmetric.
Shear deflection is negligible.
The cross section is rectangular.
The material remains in the elastic range.
Maximum allowable deflection is 0.005 in.
## Free Body Diagram and Calculation 
<img width="1119" height="1405" alt="image" src="https://github.com/user-attachments/assets/3d736ac6-b77d-4254-ac38-52d1148cd631" />

## Numerical Solution
tC = [600(4.00)³ / (4)(10,000,000)(1.00)(0.005)]^(1/3)

tC = 0.577 in

## Comparison
tC,stress = 0.642 in

tC,stiffness = 0.577 in

Since:

0.642 in > 0.577 in

## Governing Requirement
Strength governs Feature C.

## Final Feature C Dimension
tC = 0.642 in

## Feature D – Axially Loaded Bar Model
## Feature D – Stress Analysis
## Known
PD = 300 lbf
SF = 4
Sy = 35,000 psi
σallow = 8,750 psi
Width, wD = 0.50 in
## Unknown
Cross-sectional area, AD
Required thickness, tD
## Assumptions
Feature D is modeled as an axially loaded bar based on the bracket geometry and the student example.
The load transferred to Feature D is 300 lbf.
The cross section is rectangular.
Direct shear failure is neglected.
The load is static.
The material remains in the elastic range.
A safety factor of 4 is used.
## Free Body Diagram and Calculation

<img width="1216" height="1293" alt="image" src="https://github.com/user-attachments/assets/6e7cf711-b9bc-4c3f-8d48-2be8c61a04d4" />

## Numerical Solution
AD = 300 / 8750

AD = 0.03429 in²

tD = 0.03429 / 0.50

tD = 0.06857 in

## Final Stress Dimension
tD,stress = 0.06857 in

## Feature D – Stiffness Analysis
## Known
PD = 300 lbf
LD = 0.50 in
E = 10,000,000 psi
δmax = 0.005 in
wD = 0.50 in
## Unknown
Minimum cross-sectional area
Minimum thickness, tD
## Assumptions
Feature D behaves as an axially loaded bar.
Shear deformation is negligible.
The load is static.
The material remains in the elastic range.
The cross section is rectangular.
Maximum allowable deflection is 0.005 in.
## Free Body Diagram and Calculation
<img width="1103" height="1426" alt="image" src="https://github.com/user-attachments/assets/5b03e16b-c0c6-4711-874c-7acfb7a34088" />

## Numerical Solution
AD = (300)(0.50) / (10,000,000)(0.005)

AD = 0.00300 in²

tD = 0.00300 / 0.50

tD = 0.00600 in

## Comparison
tD,stress = 0.06857 in

tD,stiffness = 0.00600 in

Since:

0.06857 in > 0.00600 in

## Governing Requirement
Strength governs Feature D.

## Final Feature D Dimension
tD = 0.06857 in
## Feature E – Cantilever Beam
## Feature E – Stress Analysis
## Known
F = 600 lbf
LE = 2.00 in
SF = 4
Sy = 35,000 psi
σallow = 8,750 psi
Width, wE = 1.00 in
Rectangular cross section
## Unknown
Minimum beam height, hE
## Assumptions
Feature E is modeled as a cantilever beam with an end load.
The cross section is rectangular.
Direct shear failure is neglected.
The load is static.
The material remains in the elastic range.
Shear deformation is neglected.
A safety factor of 4 is used.
## Free Body Diagram and Calculation
<img width="1137" height="1383" alt="image" src="https://github.com/user-attachments/assets/77fb3758-de84-4ea2-914e-169bf72f3a06" />

## Numerical Solution
Mmax = (600)(2.00)

Mmax = 1,200 lbf·in

hE = [6(1,200) / (1.00)(8,750)]^(1/2)

hE = 0.907 in

## Final Stress Dimension
hE,stress = 0.907 in

## Feature E – Stiffness Analysis
## Known
F = 600 lbf
LE = 2.00 in
E = 10,000,000 psi
δmax = 0.005 in
wE = 1.00 in
## Unknown
Minimum beam height, hE
## Assumptions
Feature E behaves as a cantilever beam.
The load is applied at the free end.
Shear deflection is negligible.
The cross section is rectangular.
The load is static.
The material remains in the elastic range.
Maximum allowable deflection is 0.005 in.
## Free Body Diagram and Calculation
<img width="1100" height="1430" alt="image" src="https://github.com/user-attachments/assets/2da1a601-1408-4934-88d3-18f2dbf945f9" />

## Numerical Solution
hE = [4(600)(2.00)³ / (10,000,000)(1.00)(0.005)]^(1/3)

hE = 0.727 in

## Comparison
hE,stress = 0.907 in

hE,stiffness = 0.727 in

Since:

0.907 in > 0.727 in

## Governing Requirement
Strength governs Feature E.

## Final Feature E Dimension
hE = 0.907 in

## Decide
## Final Design Dimensions
The stress and stiffness requirements were compared for each feature. The larger required dimension was selected as the governing design dimension.

<img width="1774" height="887" alt="image" src="https://github.com/user-attachments/assets/27bfc98a-d94d-49d2-a684-15f4c2e94507" />

## Communicate

Multiview Drawing – Stress Dimensions
The multiview drawing below shows the dimensions determined from the stress analysis.

<img width="1825" height="862" alt="image" src="https://github.com/user-attachments/assets/89e06154-e4df-4350-bd72-502e82fa2d47" />

Multiview Drawing – Stiffness Dimensions
The multiview drawing below shows the dimensions determined from the stiffness analysis.

<img width="1871" height="840" alt="image" src="https://github.com/user-attachments/assets/3fc4a666-e05b-4979-82fc-782c95ad127d" />

AI-Enhanced Multiview Drawings

I started by drawing the multiview sketches by hand to develop the design and determine the required dimensions. After completing the sketches, I used AI to improve the appearance and make the drawings easier to understand. The enhanced versions kept the same general design and dimensions from my original work. This was a useful way to see how AI can help turn basic engineering sketches into cleaner and more organized visuals.

## Process Documentation
## Design Process
The design was developed by starting with Feature A and then using the resulting dimensions and load path to determine the dimensions of the following features. The bracket was analyzed using both stress and stiffness requirements.

## Design Changes and Corrections
During the calculations, an initial approach was checked against the cantilever-beam model required by Appendix D. The calculation was corrected to use the appropriate cantilever bending relationship and the required safety factor of 4.

The corrected Feature A calculations resulted in:

Stress requirement: dA = 1.28 in
Stiffness requirement: dA = 1.22 in
Governing dimension: dA = 1.28 in
The calculations were checked before using the resulting dimensions in the remaining feature analyses.

## Lessons Learned

This assignment helped me better understand how strength and stiffness both play a role when designing a mechanical component. Even if a part can safely handle the applied stress, it may still deform more than allowed. Because of this, both strength and stiffness have to be considered when determining the final dimensions.

For this bracket, strength controlled Features A through E because the dimensions required for stress were greater than those required for stiffness. This showed me the importance of analyzing each feature individually instead of assuming the same condition will control every part of the design.

I also learned how errors in one calculation can affect the rest of the design. Since Feature A was analyzed first and influenced later geometry and calculations, an incorrect value early in the process could lead to incorrect results for the other features. Checking my work throughout the analysis and comparing my calculated dimensions with my drawings helped make sure everything remained consistent.

Another assumption made during the assignment was that direct shear failure could be ignored. If direct shear had been considered, additional calculations would have been necessary and could have resulted in larger required dimensions.

Overall, this assignment showed me how important it is to keep the engineering calculations and drawings consistent. I also learned to clearly separate the minimum calculated dimensions from the dimensions actually chosen for the final design.

## Time Spent
I spent approximately 12 hours completing this assignment.
