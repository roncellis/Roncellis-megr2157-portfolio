# A2 – Truss Stress Analysis

## Objective

- Design a lightweight planar truss using A500 steel or an alternative material.

- Create free body diagrams (FBDs) for joints and critical pins.

- Calculate the required cross-sectional area of truss elements with a safety factor.

- Determine pin sizes based on shear forces with a safety factor.

- Solve equations symbolically and numerically for both truss and pin design.

- Estimate the total weight of the truss and pins.

- Create a CAD model with accurate dimensions and connections.

- Compare CAD weight predictions with hand calculations.

- Document key engineering lessons learned from the process.

## Analyze
I analyzed the given geometry with a=0.4, b=0.3 a pin at A, and a roller at B. The loads act at points C and D, so the truss needs members that transfer those forces safely to the supports. I will use a simple triangulated design to keep the truss stable and lightweight.
## Decide
I decided to use \(P=25 kN\) and create a simple triangular truss connecting A, B, C, and D. I selected this geometry because triangles provide stability while keeping the number of members and overall weight low. This design also makes it easier to calculate the member forces and transfer the loads at C and D to the supports.

# 2i. – Truss Structure 

I designed a five-member truss consisting of members AB, BC, CD, DA, and CA. Using the given dimensions of \(a=0.4\,m\) and \(b=0.3\,m\), I determined the member lengths to be 1.20 m for AB, 0.50 m for BC, 0.40 m for CD, 0.50 m for DA, and 0.854 m for CA. This geometry keeps the truss simple and lightweight while supporting the loads at C and D.
  <img width="2000" height="2666" alt="image" src="https://github.com/user-attachments/assets/7e5d06d8-6e04-4e39-b42d-3615840fa297" />

# 2ii. – Free Body Diagrams

I created free-body diagrams of the truss joints to identify the forces acting on each member. I also calculated the support reactions and found \(A_x=0\), \(A_y=8.33\) kN, and \(B_y=-8.33\) kN. These reactions were then used with the Method of Joints to solve for the internal member forces.
<img width="2000" height="2666" alt="image" src="https://github.com/user-attachments/assets/166c8587-e429-4ddb-8c9b-7d4a4a29ded1" />

# 2iii. – Symbolic Internal Forces

I used the equilibrium equations \(\sum F_x=0\) and \(\sum F_y=0\) at each joint to symbolically solve for the member forces. The forces were kept in terms of \(P\), \(a\), and \(b\) before substituting numerical values. This allowed me to determine which members were in tension and which were in compression.

# 2iiii. – Numerical Internal Forces

Using \(P=25\) kN, \(a=0.4\) m, and \(b=0.3\) m, I calculated the member forces. AB was 11.11 kN in tension, BC was 13.89 kN in compression, CD was 33.33 kN in tension, AD was 41.67 kN in tension, and CA was 47.47 kN in compression. Therefore, CA had the largest internal force and controlled the member design.


# CAD DESIGN

I modeled the truss as one solid part in Creo. I started by creating the main members and setting the overall dimensions of the truss. The top member was set to 1.20 m long, and the overall height was set to 0.30 m.
<img width="1999" height="1545" alt="image" src="https://github.com/user-attachments/assets/25bd6a55-f6bc-4960-8f5c-259287e6dabd" />


<img width="1999" height="1545" alt="image" src="https://github.com/user-attachments/assets/dcd35395-0452-49a2-a8b7-afa6a4729c18" />
Next, I added the diagonal members to connect the upper and lower joints. I used dimensions and constraints to control the locations of the members and make sure they connected at the correct points.


<img width="1999" height="1545" alt="image" src="https://github.com/user-attachments/assets/78eb7863-a349-4ffa-9473-e9fed01caae0" />

After establishing the basic truss shape, I added the remaining diagonal member to increase the triangulation of the design. This created the final geometry I selected for the truss.

<img width="1999" height="1545" alt="image" src="https://github.com/user-attachments/assets/98a306dc-805f-4f99-b5a6-5eb3d1dfd742" />
I then adjusted the dimensions and constraints until the members were positioned correctly and formed one continuous truss. The completed sketch was used to create the solid model.


<img width="1999" height="1545" alt="image" src="https://github.com/user-attachments/assets/0297c548-d7d1-46f6-82b8-3aa1b6cdd407" />
Next, I created the pin holes at the joints. Each hole was centered at the connection point so the load could be transferred through the joints properly.

<img width="1999" height="1545" alt="image" src="https://github.com/user-attachments/assets/4c1f62dd-3daf-4dd8-a9d1-c66bb6b762a5" />
After completing the 2D geometry, I extruded the sketch to give the truss its required thickness. This produced the final 3D shape of the truss.

<img width="1999" height="1545" alt="image" src="https://github.com/user-attachments/assets/1381d683-680f-4f42-9bc0-863f53079c00" />
I checked the final model and the joint geometry to make sure the members remained connected and that there was enough material around the pin holes.
<img width="1999" height="1545" alt="image" src="https://github.com/user-attachments/assets/da7ba7b6-088f-4707-861a-7f21e7202707" />


<img width="1999" height="1545" alt="image" src="https://github.com/user-attachments/assets/d0f46a97-0638-43dc-886d-8b688d18ec27" />
Finally, I assigned steel as the material and used the Mass Properties tool to evaluate the completed design. Creo calculated a volume of approximately 1.5895 × 10⁻³ m³ and a mass of approximately 12.44 kg.

<img width="1999" height="1545" alt="image" src="https://github.com/user-attachments/assets/44b9a2e7-bf3d-4003-9df1-28753df29dd1" />


<img width="2000" height="2588" alt="image" src="https://github.com/user-attachments/assets/98e2855c-346b-4015-ab60-cac6213c5133" />
This is better than putting a sentence under every single picture because the screenshots that show similar steps can be grouped together. It also reads like you’re documenting your actual CAD process instead of just describing what is visible in each screenshot.
## Communicate

One of the main things I learned from this project was how to take calculations and actually use them to design a structural part. Before starting, I spent some time researching truss structures to get a better understanding of how they work. Starting the design from scratch was still challenging, and I had to use a lot of trial and error before getting to my final design. This helped me think more critically about the decisions I was making instead of just choosing dimensions without a reason.

I already had experience with statics and equilibrium equations, but this project helped me understand how internal member forces, material strength, and safety factor can be used together to determine the size of a truss member.

I also got more comfortable using Creo to turn my calculations into an actual 3D model. I improved at creating and dimensioning sketches, extruding parts, creating pin joints, assigning materials, and checking mass properties. I also learned how important it is to double-check dimensions and units because one incorrect setting in the CAD model can affect the final results.

Overall, I spent around 10 hours working on this project, including the calculations, CAD modeling, making corrections, and documenting my final design.
