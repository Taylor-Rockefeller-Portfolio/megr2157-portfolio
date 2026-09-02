# A2 – Truss Stress Analysis

## Objective
-Design a lightweight planar truss using A500 steel or an alternative material.

-Create free body diagrams (FBDs) for joints and critical pins.

-Calculate the required cross-sectional area of truss elements with a safety factor.

-Determine pin sizes based on shear forces with a safety factor.

-Solve equations symbolically and numerically for both truss and pin design.

-Estimate the total weight of the truss and pins.

-Create a CAD model with accurate dimensions and connections.

-Compare CAD weight predictions with hand calculations.

-Document key engineering lessons learned from the process.

## Truss Geometry and Static Analysis

![](IMG_0283.jpg)

Before conducting any analysis, I first decided on the geometry of the truss I would build. I settled on using an angled member from both supports down to the location that the loads were applied to. Three equal length members run from one support to another, with their pinned connections above the applied loads. This leaves two vertical members connecting the upper cord of the truss to the lower. Using this geometry allows for minimal members to be used, creating a lighter truss. I initially used a truss geometry that mirrors the current design about the axis between the supports and had an additional member that ran vertically down to support the applied load. This was more aesthetically pleasing but used more members and had 4 member joints. The final design will be lighter weight and accomplish the same goal. 

![](IMG_0265.PNG)
![](IMG_0266.PNG)

## Statics Analysis
With the geometry of the truss decided I moved onto the statics analysis to find the forces in the members in order to analyze the highest force member. 

![](IMG_1545.jpg)

## Solid Analysis

Once I found the highest force member, I determined what the minimum cross-sectional area would be for my member. In order to do this, I chose a material that is available on the CAD program I am using, SolidWorks, and found its yield strength. Then I used the required safety factor to find the cross-sectional area. 
With the cross-sectional area determined I moved to finding the diameter of the pins I would need to connect my members. I used the highest shear force pin location which is the connections with the diagonal member. I then used the supplied yield force and the safety factor of 4 to determine the minimum pin diameter in order to avoid the pin shearing. 

![](IMG_1550.jpg)

## Member Dimensions and CAD Modeling
With that decided I moved to constructing the CAD models of the members. This is where I realized that I would need to create members of varying lengths and different ends in order to connect to one another. And with one joint having three members coming together I knew that I needed to design a way for three members to connect without making their cross-sectional areas smaller than required.

![](IMG_1551.jpg)

After designing the appropriate members, I moved to assembling them. This is where I realized that I had designed my members to connect perfectly when straight with one another but not when coming together at an angle. My assembly joints with angled members had parts overlapping one another, so I needed to go back to these parts and modify them in order to maintain structural integrity of the member while also allowing for a connection that would work. 

![](Screenshot(212).png)
![](Screenshot(213).png)
![](Screenshot(214).png)
![](Screenshot(216).png)

## Truss Geometry Version 2

After reassessing the assignment, I realized that I made a mistake when checking the updated assignment constraints. I failed to see that the direction of one of the applied loads had been turned to face upward. I analyzed the current truss geometry and found that it would not satisfy the constraints. I began designing a new truss geometry that is more conventional and will withstand the applied forces in their current state.

![](A2_directions.png)

## Truss Static Analysis

Below is the new overall truss geometry FBD, conducting static analysis to determine reaction forces in terms of the applied force P.

![](IMG_0269.jpg)

## Internal Truss Member Analysis

Conducting internal truss static analysis to determine internal forces on every member. Due to the symmetry of the geometry the loads will be identical in magnitude, but opposite in direction because of the modified loads. Making assumptions on compression and tension before carrying out joint analysis. 

![](0270_1.PNG)

## Method of Joints

Solving for internal forces at each joint in terms of applied force P

![](IMG_0271.jpg)
![](IMG_0272.jpg)
![](IMG_0273.jpg)

Solving for the magnitude of internal forces by substituting my chosen P value. The largest forces are on the two inner diagonal members. One in compression and one in tension. 

![](IMG_0274.jpg)

## Solid Analysis

Determining the minimum required cross-sectional area for the members. Utilizing the largest internal force on a member so that the members will all be within the safety factor given. Rounding down when necessary for the total stress allowed to keep below the safety factor and rounding up on cross-sectional area to have a marginally stronger beam than required. I am using a width of 25mm to have a clean number to dimension my pins with. 

![](IMG_0275.jpg)
![](IMG_0276.jpg)

Evaluating the center pinned connection to find the resultant force on the pin. Using the supplied yield strength, density, and safety factor to find the minimum area that the pin can have. 

![](IMG_0278.jpg)
![](IMG_0279.jpg)

## Truss and Pin Weight Calculations

Evaluating the expected weight of the truss and pins to compare with the SolidWorks values I get.  
![](IMG_0280.jpg)
![](IMG_0281.jpg)
![](IMG_0282.jpg)

## Updated CAD Modeling

Creating my second CAD model I am sticking to the basics of the requirements which required the truss members to be modeled as one part so instead of making individual members I am modeling all truss members as one piece. They will have a uniform cross section except at the pinned connections where the cross-section will be enlarged to maintain structural integrity of the truss.

![](Truss_2.0.png)
![](Truss_pin_2.0.png)
![](Truss_assembly_2.0.png)

## Lessons Learned

Throughout this project I have been challenged to step past purely analyzing givens structures and had to create my own truss system to support a load. This is the first time that I have had to solve such a problem, and through failing to check the updated assignment instructions, I had the opportunity to do it twice. This was a great learning experience because it showed me that you can design something to support a specific load, but it can fail when the loading is changed. My new design would support either loading patterns better than the original one. I had the opportunity to further my skills in SolidWorks as well by creating individual members and assembling them and realizing dimensional constraints too late. In the future I will know to adjust my member dimensions to properly fit all joints. 

