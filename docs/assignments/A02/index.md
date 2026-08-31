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

# 2ii. – Free Body Diagrams

I created free-body diagrams of the truss joints to identify the forces acting on each member. I also calculated the support reactions and found \(A_x=0\), \(A_y=8.33\) kN, and \(B_y=-8.33\) kN. These reactions were then used with the Method of Joints to solve for the internal member forces.

# 2iii. – Symbolic Internal Forces

I used the equilibrium equations \(\sum F_x=0\) and \(\sum F_y=0\) at each joint to symbolically solve for the member forces. The forces were kept in terms of \(P\), \(a\), and \(b\) before substituting numerical values. This allowed me to determine which members were in tension and which were in compression.

# 2iiii. – Numerical Internal Forces

Using \(P=25\) kN, \(a=0.4\) m, and \(b=0.3\) m, I calculated the member forces. AB was 11.11 kN in tension, BC was 13.89 kN in compression, CD was 33.33 kN in tension, AD was 41.67 kN in tension, and CA was 47.47 kN in compression. Therefore, CA had the largest internal force and controlled the member design.
## Communicate

