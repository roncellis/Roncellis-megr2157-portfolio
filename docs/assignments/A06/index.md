# A6 – Bracket Drawing

## Objective

The objective of this assignment is to create a solid model and multiview drawing of my bracket while making sure it meets the strength and stiffness requirements. I will use the dimensions I calculated in the previous assignment to create my parametric CAD model. Then, I will make a fully dimensioned multiview drawing and add the correct tolerances. I will also identify an equation that controls one of the dimensions in my model. Lastly, I will choose one dimension that needs a tighter tolerance and one that can have a looser tolerance and explain why each tolerance makes sense based on how the feature works.

## Analyze 
<img width="1058" height="1487" alt="image" src="https://github.com/user-attachments/assets/c573d0ae-f877-4d50-bece-535de97143b8" />
- For Feature A, the stress analysis controlled the design, giving me a diameter of 0.8709 in.
- Feature B was also controlled by stress, with a thickness of 0.15099 in.
- For Feature C, stress determined the height to be 0.7044 in.
- Feature D had a required thickness/length of 0.0662 in based on stress. Lastly, Feature E was controlled by stress, giving me a height of 0.6299 in.

## Parametric Variables and Equations
- <img width="1313" height="1198" alt="image" src="https://github.com/user-attachments/assets/30fe7e99-bcd8-412f-9edd-a90d03a878b7" />
These are the variables and equations that drove the dimensions of my bracket. I used values such as the applied force, yield strength, safety factor, and material properties in the equations to calculate the required dimensions for each feature. This allowed the dimensions in my model to be based on my engineering analysis instead of just choosing values.

## Dimensions

<img width="1576" height="998" alt="image" src="https://github.com/user-attachments/assets/fdcd6ec6-c557-4a87-a609-8492eabe0b5c" />
<img width="1905" height="826" alt="image" src="https://github.com/user-attachments/assets/a3735b7f-1063-4702-bbfe-8bbee621d5b2" />
<img width="1048" height="1501" alt="image" src="https://github.com/user-attachments/assets/cf854392-1a02-4c57-91b7-b5cc8d9f33f4" />
<img width="1330" height="1182" alt="image" src="https://github.com/user-attachments/assets/8aa4e01a-731b-43a7-b411-2d756dec4914" />

## Tolerances 
<img width="840" height="484" alt="image" src="https://github.com/user-attachments/assets/25564467-85d7-48fd-94e0-e543e65f5e5d" />
<img width="867" height="465" alt="image" src="https://github.com/user-attachments/assets/4a3c2352-b914-4f35-abd5-046bceff610d" />
<img width="1105" height="1423" alt="image" src="https://github.com/user-attachments/assets/74280849-10b4-42b6-8f61-2c0752423bab" />

For dimensions a and c, I used a minimum tolerance of 0 because these dimensions control the openings for the mating parts. The openings should not be any smaller than the minimum required size because that could cause interference and make the parts difficult or impossible to fit together. Allowing the tolerance to increase from the minimum size helps make sure there is enough clearance for assembly.
For dimension b, I used a maximum tolerance of 0 because it represents a solid feature that fits inside another part. This feature should not be larger than the maximum allowable size because it could reduce the clearance between the parts and cause interference. Keeping the tolerance below the maximum size helps make sure the parts can fit and move together as intended.

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/3ef779f5-60e9-4775-91c5-250f34e696c7" />
<img width="2106" height="747" alt="image" src="https://github.com/user-attachments/assets/b574ab4c-a6ab-4305-a2bc-18017287180c" />

## Communicate
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/f8f11ebf-2733-46f9-8149-dba8a419bdd3" />

I used the strength equation to control the diameter of Feature A instead of just entering a set dimension. I rearranged the strength equation to solve for the radius and entered that equation into CAD using the force, yield strength, and safety factor values. From there, I set the diameter of Feature A equal to two times the calculated radius. I also linked the width of Feature B to the diameter of Feature A because I designed these two features to line up with each other. This made my model parametric, so if any of the values in the strength equation change, the diameter of Feature A will update automatically, and the width of Feature B will update with it.

<img width="730" height="294" alt="image" src="https://github.com/user-attachments/assets/fafe6de0-343b-44b1-8c1a-db77fc989276" />

I used a looser tolerance for dimension “a” because the previous assignment described this feature as one where high accuracy is not necessary. Since this feature does not need a very close fit to function correctly, I selected an RC5 fit, which gives the mating parts more clearance while still allowing them to work together properly.
For dimension “b,” I used a tighter tolerance because this feature requires a much closer fit. The previous assignment described it as the closest fit that can still run freely, so I selected an RC1 fit. This tighter tolerance helps control the amount of clearance between the mating parts and makes sure they fit together properly without causing interference.
Both “a” and “b” are functional mating dimensions, but they have different tolerance requirements based on how they are supposed to work. Dimension “b” needs more accuracy and a closer fit, while dimension “a” can have more variation without affecting the overall function of the bracket.

## Lessons Learned

I learned how to create tolerance fits and how to determine which analysis governs the main dimensions of each feature.

I spent approximately 7 hours creating my part on CAD and defining tolerances.


