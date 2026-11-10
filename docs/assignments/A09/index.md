# A9 – Pulleys

## Objective

The objective of this assignment is to design a pulley system that transfers power between two parallel shafts. The design must meet the specified requirements for pulley diameter, shaft spacing, rotational speed, belt tension, and safety factor. I will use engineering calculations to determine the required belt dimensions, minimum shaft diameter, and journal bearing specifications. I will also design a supporting frame to hold the pulleys and shafts in the correct positions.

The design requirements are:

Pulley diameter: Both pulleys must have a diameter of 3 inches.
Center distance: The parallel shafts must be separated by 4–6 inches. I will use a center distance of 5 inches.
Rotational speed: The operating speed must be between 1,000 and 2,000 rpm. I will use 1,500 rpm.
Static belt tension: The belt tension must be between 4 and 6 lbf. I will use 5 lbf.
Pulley material: The pulleys will be designed using aluminum.
Safety factor: The design must satisfy a minimum safety factor of 3.
Belt material: The belt is assumed to be polyurethane rubber with a yield strength of 3.25 MPa (471 psi) at 20% strain, based on the research paper “Strain-induced Structural and Dynamic Changes in Segmented Polyurethane Elastomers.”
I will use these requirements to guide the calculations, component selection, and CAD design. The final design will include the belt, shafts, journal bearings, and a supporting frame.

## Analyze

I began designing the pulley system by figuring out the belt dimensions and choosing a belt that would fit both pulleys. The given values included a pulley diameter of 3 inches, a center distance of 5 inches, a static belt tension of 5 lbf, and a safety factor of 3. I started by organizing the known and unknown values and creating a free-body diagram (FBD) to better understand the forces acting on the system. From there, I set up the equations to solve for the tight-side and loose-side belt tensions. Using the yield strength of the polyurethane belt material, I calculated the minimum cross-sectional area and belt diameter needed to safely handle the forces. After that, I estimated the total belt length and used my calculations to find a suitable belt from McMaster-Carr.
<img width="1312" height="1199" alt="image" src="https://github.com/user-attachments/assets/91c895ee-ab03-4a20-9198-18d7f724151a" />

Once I finished calculating the belt dimensions, I went to McMaster-Carr to find a polyurethane round belt that would work for my design. From my calculations, I determined that the minimum belt diameter needed was about 0.242 inches, with an estimated belt length of 19.42 inches. After looking through the available options, I found part 3044K608, which seemed like a good choice for the system. This belt has a diameter of 3/8 inch, which is larger than the minimum diameter I calculated. Before making my final decision, I still need to double-check the belt's available length and specifications to make sure it will fit and work properly with both pulleys.
<img width="1919" height="1090" alt="image" src="https://github.com/user-attachments/assets/2c2181d3-ccff-4cb4-9b06-ea960bd7d9dc" />

After finishing my calculations for the belt diameter and outer circumference, I used McMaster-Carr to look for a polyurethane round belt that would fit my pulley system. I found part 3044K608, which looked like a good option because it has a diameter of 3/8 inch and an available outer circumference range of 12¼ to 24 inches. Since my calculated belt length was about 19.42 inches, it falls within that range. The belt diameter is also larger than the minimum size I calculated, meaning it meets my initial design requirements. Before moving forward with the final design, I will double-check the belt's fit and tension to make sure everything works properly.

## Shaft Design

After completing the belt selection, I moved on to figuring out the minimum shaft diameter needed to hold the pulleys and transfer torque throughout the system. I began by writing down the known and unknown values and drawing a free-body diagram (FBD) to better understand the forces acting on each shaft. From there, I used the belt forces and pulley radius to calculate the torque on the shaft. Once I found the torque, I used the material properties of 1060 hardened steel along with a safety factor of 3 to calculate the minimum cross-sectional area and shaft diameter. These calculations gave me a starting point for choosing a shaft size that would safely support the pulleys and handle the torque in the system.
<img width="1227" height="1282" alt="image" src="https://github.com/user-attachments/assets/92c5456c-85b0-419c-a620-54c954cbd7ff" />

Once I finished calculating the torque and minimum shaft diameter, I went to McMaster-Carr to look for a shaft that would work with my pulley system. Based on my calculations, the shaft needs to be made from 1060 hardened steel and have a diameter of at least 0.101 inches. I also need to make sure the shaft fits properly with the pulley bores and journal bearings. Before making my final selection, I will double-check the shaft's material properties and dimensions to make sure it meets all the requirements for my design.
<img width="3807" height="1835" alt="image" src="https://github.com/user-attachments/assets/44c07ab9-5125-4491-a48c-e30f69d5826c" />

## Journal Bearing Design

After finishing the shaft calculations, I moved on to designing the journal bearings that would support the shafts and help the pulleys rotate smoothly. I started by writing down the known and unknown values and creating a free-body diagram (FBD) to understand the forces acting on the shafts and bearings. From there, I calculated the pressure on the bearings and the linear velocity of the shaft. Using those results, I found the pressure-velocity (PV) value and compared it to the limits of different bearing materials. After reviewing the calculations, I was able to determine which bearing material would be a good choice for my pulley system.
<img width="1312" height="1199" alt="image" src="https://github.com/user-attachments/assets/c228acf3-fc7c-48da-bb3d-93a245580e04" />
<img width="602" height="821" alt="image" src="https://github.com/user-attachments/assets/d736728a-9fda-4ff7-91f2-0a1650628845" />

After completing my calculations, I used Table 4 from Machinery's Handbook to compare different bearing materials and determine which one would work best for my design. I decided to go with porous bronze because my calculated pressure-velocity (PV) value of 982.36 psi·ft/min was well below its maximum allowable value of 50,000 psi·ft/min. Once I confirmed that the material met the initial requirements, I went to McMaster-Carr to look for a journal bearing that would fit my 1/4-inch shaft. Before making my final decision, I still need to double-check the bearing's dimensions, load capacity, and operating speed limits to make sure it will work properly with my pulley system.
<img width="1322" height="1270" alt="image" src="https://github.com/user-attachments/assets/2b6b9c92-1fdd-447e-a95f-02111d92ea69" />
After calculating the bearing pressure, surface velocity, and pressure-velocity (PV) value, I decided to use an oil-embedded 841 bronze sleeve bearing for my design. I searched McMaster-Carr and found part 7639N11, which fits a 1/4-inch shaft and has a length of 1/2 inch. This bearing comes with synthetic oil embedded in the material to help reduce friction during operation. It also has a dynamic radial load capacity of 200 lb at 120 rpm. Since my pulley system will be operating at 1,500 rpm, I still need to check whether the bearing can safely handle that speed before making my final selection.

## Frame Design

The last part of the assignment was to design a frame that would support the entire pulley system. I started by planning how the frame would hold both shafts and journal bearings in place while keeping the required 5-inch distance between the pulleys. When choosing a material for the frame, I looked at several factors, including strength, stiffness, weight, cost, and how easy it would be to manufacture. I also considered using an Ashby plot to compare different materials based on their density and strength. Since the frame will be supporting moving components, I need to make sure it can handle the forces without bending too much or shifting out of place. My final material choice will depend on which option best meets these requirements and the results of my engineering calculations.
<img width="532" height="408" alt="image" src="https://github.com/user-attachments/assets/0608f948-a46d-4959-9c80-2abfb023b13a" />

I used the Young’s modulus–density Ashby plot to look at different materials and compare their stiffness and weight. From the plot, I noticed that metals are generally stiffer than polymers and foams, while some composites and natural materials are lighter. For my pulley system, I wanted a frame material that would be strong enough to support the shafts and bearings without adding too much weight or bending under the applied forces. I also had to think about the cost of the material and how easy it would be to manufacture the frame. By comparing these factors, I can determine which material would be the best choice for my final design.

Finally, I developed a preliminary frame design to support the pulley system. I chose a compact bracket-style frame to hold the journal bearings and keep the shafts aligned at the required 5-inch center distance. I planned to use rounded corners and fillets to reduce unnecessary material and avoid sharp corners. The final design will need to provide enough stiffness and strength to support the rotating components without excessive deflection. I will verify the frame dimensions and material choice based on the expected loads and ease of fabrication.
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/50e891a0-20b8-42ba-9213-3ee4cbcd1330" />

## Mistakes and Areas for Improvement
Throughout this assignment, I noticed a few mistakes and assumptions that could have affected my pulley system design. One issue was using a friction coefficient of 0.3 without confirming it from the reference material. This affected my belt force calculations, which should have been approximately 7.19 lbf and 2.81 lbf. I also needed to be more consistent with rounding and make sure the belt length and tension matched the manufacturer's specifications.

For the shaft design, I realized that I needed to use the correct shear stress relationship instead of directly using the tensile yield strength. This means my calculated minimum shaft diameter of 0.101 inches still needed to be verified. For the journal bearings, I assumed the load was split evenly between two bearings, but I should have confirmed this using my free-body diagram. I also needed to make sure the selected bearing could operate safely at 1,500 rpm.

Another area I could have improved was the frame design. I chose preliminary dimensions and used an Ashby plot to compare materials, but I did not complete all the stress and deflection calculations needed to confirm my design.

Overall, this assignment helped me understand the importance of checking my assumptions, using the correct equations, and verifying component specifications before making final decisions. If I were to do this project again, I would spend more time checking my calculations and making sure every component works properly together.
## Communicate
Throughout this assignment, I gained a better understanding of how to determine the proper belt and shaft sizes for a pulley system. I also learned how belt tension affects the forces on the shafts and how to calculate bearing pressure, surface velocity, and pressure-velocity (PV) values when selecting journal bearings. Using Machinery's Handbook helped me understand why material properties and operating limits are important when choosing components. I also learned how to use an Ashby plot to compare different materials based on stiffness and density to help decide which material would work best for the frame.

For the design portion, I started by drawing my sketches by hand and then used AI to turn them into cleaner and more detailed images. I was happy with how they turned out because they made my designs easier to see and explain in my report. Overall, this assignment took me approximately 5 hours to complete and helped me better understand the process of designing a complete pulley system.
