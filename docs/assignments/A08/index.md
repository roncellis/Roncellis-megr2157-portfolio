# A8 – Gears

## Objective

The purpose of this assignment was to develop a gearbox that could be easily assembled and disassembled. I started by using the provided information to analyze the strength of the input and output shafts. I also performed calculations to determine the pressure, velocity, and required thickness of the journal bearings. These results helped me make decisions when creating the gearbox housing in CAD. The design consists of two spur gears with a gear ratio of 24:9, an output torque of 1.25 in·lbf, and an output speed of 1100 rpm. The input shaft has a diameter of 0.125 inches, and the output shaft has a diameter of 0.250 inches, with both shafts measuring 1 inch in length. As I worked through the assignment, I kept track of my calculations, design choices, and overall progress toward completing the gearbox assembly. The image below shows the two gears that will be placed inside the gearbox housing.
<img width="848" height="711" alt="image" src="https://github.com/user-attachments/assets/1b9b559b-9482-4ac5-a337-684719da9a09" />


## Analyze


## Input shaft 
For the input shaft, I started with the given diameter of 0.125 inches and used the gear ratio to determine the input torque. From there, I calculated the torsional shear stress acting on the shaft. I chose steel as the material because of its strength and common use in mechanical power-transmission systems. After completing the calculations, I found that the shear stress was approximately 1,222 psi. I will use this result to check whether the shaft can safely handle the applied torque by comparing it to the allowable shear stress of the selected steel. The calculations and free-body diagram used for this analysis are provided below.
<img width="1448" height="1086" alt="image" src="https://github.com/user-attachments/assets/3a8e9200-5f5a-4ebd-af03-1cbbec03587e" />
## Output Shaft
For the output shaft, I followed a similar process to the input shaft by using the torsional shear stress equation. This time, I used the given shaft diameter of 0.250 inches and the output torque of 1.25 in·lbf. After working through the calculations, I noticed that the output shaft experienced less shear stress than the input shaft, even though it carried more torque. This is because the larger shaft diameter helps reduce the amount of stress. I then used the calculated stress to determine if the shaft was strong enough by comparing it to the allowable shear stress of the chosen material. The calculations and free-body diagram for the output shaft are shown below.
<img width="1448" height="1086" alt="image" src="https://github.com/user-attachments/assets/7ab63ce0-4e6b-44e3-ac20-40d722689e06" />
## Journal Bearings
For this part of the assignment, I focused on designing the journal bearings that support the input and output shafts while allowing them to rotate smoothly. I started by drawing a free-body diagram to better understand the forces acting on the bearings. After identifying the known and unknown values, I used the appropriate equations to calculate the bearing pressure, surface velocity, and PV rating. These calculations helped me understand the conditions the bearings would experience during operation. I then used the results to check if the selected bearing material could safely handle the load and rotational speed. The free-body diagram and calculations for this section are shown below.
<img width="1448" height="1086" alt="image" src="https://github.com/user-attachments/assets/e2580775-70e9-4fe0-8d95-d57d8a861732" />


Knowns

Input shaft diameter: d_in = 0.125 in

Output shaft diameter: d_out = 0.250 in

Gear ratio: GR = 24/9 = 2.667

Output torque: T_out = 1.25 in·lbf

Output speed: n_out = 1100 rpm

Input speed: n_in = 1100(2.667) = 2933.3 rpm

Pressure angle: alpha = 20 degrees

Assumed output gear pitch diameter: d_p = 1.00 in

Assumed input bearing length: L_in = 0.375 in

Assumed output bearing length: L_out = 1.00 in

Assumed allowable PV rating for porous bronze: PV_allow = 50000 psi·ft/min

Unknowns

Radial gear force, F_r

Bearing pressure, P

Surface velocity, V

PV rating, PV

Solving Algebraically

Tangential gear force:

F_t = (2 * T_out) / d_p

Radial gear force:

F_r = F_t * tan(alpha)

Bearing pressure:

P = F_r / (d * L)

Surface velocity:

V = (pi * d * n) / 12

PV rating:

PV = P * V

Solving Numerically

Tangential gear force
F_t = (2 * 1.25) / 1.00

F_t = 2.50 lbf

Radial gear force
F_r = 2.50 * tan(20 degrees)

F_r = 0.910 lbf

Input Bearing
Assume d = 0.125 in, L_in = 0.375 in, and n_in = 2933.3 rpm.

Bearing pressure:

P_in = 0.910 / (0.125 * 0.375)

P_in = 19.41 psi

Surface velocity:

V_in = (pi * 0.125 * 2933.3) / 12

V_in = 95.99 ft/min

PV rating:

PV_in = 19.41 * 95.99

PV_in = 1863 psi·ft/min

Output Bearing
Assume d = 0.250 in, L_out = 1.00 in, and n_out = 1100 rpm.

Bearing pressure:

P_out = 0.910 / (0.250 * 1.00)

P_out = 3.64 psi

Surface velocity:

V_out = (pi * 0.250 * 1100) / 12

V_out = 71.99 ft/min

PV rating:

PV_out = 3.64 * 71.99

PV_out = 262.1 psi·ft/min

Comparison with Allowable PV Rating

Assumed allowable rating:

PV_allow = 50000 psi·ft/min

Input bearing:

1863 < 50000

Output bearing:

262.1 < 50000

These preliminary PV values are below the assumed allowable rating. The bearing dimensions, actual material rating, gear pitch diameter, and radial loading must be verified before these results are treated as final.
## Journal Bearing Thickness
For this section, I focused on finding the proper thickness for the journal bearings. I started by looking at the force applied to the bearing and the strength of the material being used. I listed the known and unknown values and created a free-body diagram to help understand how the forces act on the bearing. Using the appropriate equations, I calculated the minimum thickness needed to support the load. From there, I considered a thickness that would provide enough strength while still allowing the bearing to fit properly inside the gearbox housing. My calculations and free-body diagram are shown below.
<img width="2048" height="768" alt="image" src="https://github.com/user-attachments/assets/c9beb31e-231e-49cb-b794-d72086347c51" />
Knowns

Input shaft diameter: d_in = 0.125 in

Output shaft diameter: d_out = 0.250 in

Tangential gear force: F_t = 2.50 lbf

Radial gear force: F_r = 0.910 lbf

Allowable bearing pressure: P_allow = 4500 psi

Unknown

Minimum bearing wall thickness: t

Free-Body Diagram

Draw the bearing cross-section and show the resultant load acting on the bearing.

Solving Algebraically

Resultant force:

F_result = sqrt(F_t^2 + F_r^2)

Bearing cross-sectional area:

A = F_result / P_allow

For the cylindrical bearing wall:

A = (pi/4) * ((d + t)^2 - d^2)

Equating the areas:

F_result / P_allow = (pi/4) * ((d + t)^2 - d^2)

Solving for wall thickness:

t = sqrt((4 * F_result)/(pi * P_allow) + d^2) - d

Solving Numerically

Resultant force:

F_result = sqrt((2.50)^2 + (0.910)^2)

F_result = 2.660 lbf

Input bearing:

t_in = sqrt((4 * 2.660)/(pi * 4500) + (0.125)^2) - 0.125

Output bearing:

t_out = sqrt((4 * 2.660)/(pi * 4500) + (0.250)^2) - 0.250

After calculating the minimum thickness needed for the journal bearings, I compared my results with the dimensions of bearings available from McMaster-Carr. For the output shaft, I selected the Mil. Spec. Oil-Embedded 841 Bronze Sleeve Bearing (part 7639N11). This bearing is designed for a 1/4-inch shaft, has a 3/8-inch outside diameter, and is 1/2 inch long. I chose this bearing because the oil-embedded bronze helps reduce friction and wear as the shaft rotates. The bearing also matches the output shaft diameter and gives me the dimensions needed to design the housing in CAD. McMaster-Carr lists a dynamic radial load capacity of 200 lb at 120 rpm. Since my gearbox operates at a higher speed, I would need to compare my calculated pressure, velocity, and PV values with the bearing's specifications to make sure it can safely handle the operating conditions. I also need to confirm that the bearing's actual wall thickness meets the minimum thickness I calculated.
<img width="1410" height="717" alt="image" src="https://github.com/user-attachments/assets/782d27bd-4bb0-4b49-ab24-f81a6fa8ed2f" />

<img width="1448" height="1086" alt="image" src="https://github.com/user-attachments/assets/11a72c6e-3adb-4ff3-9f48-26f1a7ebccf2" />

For the gearbox housing, I chose to create two separate pieces consisting of a top and bottom half. I decided to use screws to connect the two sections so the gearbox could be taken apart and put back together without much difficulty. This would also make it easier to access the internal components if any changes or repairs were needed. I added mounting holes at each corner for the screws and made sure there would be enough room inside the housing for the gears, shafts, and journal bearings. After finishing my initial sketch, I used it as a guide to begin designing the housing in CAD. The drawing below shows my original idea for the gearbox housing.

## CAD Modeling Process
The CAD portion of this assignment ended up taking longer than I planned because I had to pay close attention to how each component would fit inside the gearbox. I began by setting up parametric dimensions so I could easily change certain measurements without starting the design over. From there, I created the top and bottom sections of the housing and made sure there was enough space for the gears, shafts, and journal bearings. I also included holes for the screws that would hold the two halves together while still allowing the gearbox to be disassembled. As I continued modeling, I had to go back and change some dimensions to get everything to line up properly. Making these adjustments helped me improve the overall design and make sure it followed the requirements of the assignment.

<img width="1307" height="569" alt="image" src="https://github.com/user-attachments/assets/32826db4-2b88-42d2-9634-cf547da7de5b" />
After downloading the required components, I began assembling the gearbox in CAD. During this process, I tried out two different designs for the housing to see which one would work best. My first design was more detailed, but as I continued working on it, I realized it was more difficult to create than I originally thought. It would have taken more time and CAD experience to get everything to fit correctly. Because of this, I decided to use a simpler housing design that would be easier to model and assemble. This allowed me to focus on making sure the parts fit together properly while still following the assignment requirements.
<img width="1908" height="796" alt="image" src="https://github.com/user-attachments/assets/6d3d7ab1-a565-4083-83e6-a2e9405f1dc3" />
One issue I ran into during the CAD modeling process was trying to make the gearbox housing symmetrical by dividing it into two equal halves. At first, I thought this would make the design easier, but I had trouble getting the two sections to separate and fit together correctly in the assembly. After spending some time trying to fix the problem, I decided it would be better to restart and model the top and bottom halves individually. This made it easier to control the dimensions of each piece and adjust them when needed. Although starting over took extra time, it helped me create a better design and made the assembly process easier.
<img width="889" height="620" alt="image" src="https://github.com/user-attachments/assets/2fab9bb4-2883-42d5-92ad-4070a3bdbb48" />
At first, I thought I could extrude several moving components together, but after trying it, I realized that it wasn't going to work the way I planned. I decided to restart the model and focus on creating the main housing frame first. From there, I added holes for the shafts that would support the gears. I started by positioning the gears to make sure they lined up correctly before adding the remaining parts one at a time. One mistake I made was working on the assembly without including the top half of the housing. Looking back, I should have added it earlier because it would have helped me check the spacing and clearances between the components. This would have saved me some time and prevented a few adjustments later in the design process.
<img width="785" height="643" alt="image" src="https://github.com/user-attachments/assets/15a91a28-5ba5-4af0-9182-40757c504a72" />
After spending a few hours trying to get the gears to rotate correctly, I started working on the top section of the gearbox housing. At first, everything was going pretty well until I realized that the holes on the top and bottom pieces were not matching up. I was confused because I had used a copy of the bottom housing to create the top, so I expected everything to line up. After going back through the model and checking my measurements, I noticed that some of the dimensions had been switched around. I had to go in and manually adjust the dimensions until the holes were in the correct positions. Once I fixed that issue, I added the holes for the screws and hex nuts so the two housing pieces could be secured together. This part of the assignment taught me how important it is to double-check dimensions, even when using an existing part as a starting point.
<img width="847" height="534" alt="image" src="https://github.com/user-attachments/assets/4196a840-261d-47dd-ba95-def3f668858e" />
The image below shows my completed gearbox design. After spending a lot of time making adjustments and fixing issues with the gears, housing, and alignment, I was finally able to put everything together. Even though I ran into several problems throughout the process, I was able to work through them and get the assembly looking the way I wanted. Seeing the final design come together was rewarding, especially after all the time I spent troubleshooting and making changes. Below is the finished gearbox assembly.<img width="891" height="678" alt="image" src="https://github.com/user-attachments/assets/9ee3cb1c-8128-40a6-9910-feffb57f5515" />

## Communicate

I learned a lot more about SolidWorks while working on this assignment. Every time I think I am getting comfortable with the software, I run into a new challenge that forces me to learn something else. I spent many hours working on this gearbox, from getting the gears to rotate properly to making sure the top and bottom halves lined up. Looking back at how far I have come since first starting SolidWorks, I can tell that I am developing a useful new skill. One of my biggest takeaways was learning to pay closer attention to dimensions and orientation when flipping or modifying parts. I will definitely remember that lesson for future CAD projects.

Part file: https://mail.google.com/mail/u/0?ui=2&ik=4e9b2dd91e&attid=0.1&permmsgid=msg-a:r8734702875944574608&view=att&dsp=safe&realattid=f_mv7715ee0&zw
