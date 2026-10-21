# A7 – FEA Iterative Process

Objective

![](Part_Features_Diagram.png)

## Study Constraints and Loads

For each iteration of FEA studies, the part is constrained by a fixed connection at feature E as shown below. The load is 1000 pounds of force distributed across feature A uniformly, as shown below. 

![](combined-image(6).jpg)

Study 1 (Original Design Testing)

Once constraints and loads were set, I began by creating a course mesh and running the study. I proceeded to create more mesh sizes with varying element counts and checking the convergence. I completed multiple convergence tests between the mesh sizes. Finally resulting in the use of the fine mesh data with 64,232 elements. The convergence tests and the results of the multiple mesh tests are available below. The fine mesh data is highlighted green.

![](study_1_excel.jpg)

![](combined-image(3).jpg)


![](combined-image(4).jpg)


![](combined-image(5).jpg)


The image below shows the point of maximum stress and deflection on study 1. These locations are the subject of future design changes for study 2 to improve the part.

![](combined-image(7).jpg)

After completing the first study it was apparent that the original formulas used to create the part were not sufficient when tested. The bending occurring at feature B would have to be addressed to work toward the required safety factor and max deflection. 

## Study 2 (Second Vertical Support Added)

Study 2 Geometric Changes- The major failure of the part during study 1 was the deflection of feature A. In order to minimize deflection, I am adding another support opposite of feature B that will make feature A behave more like a beam fixed at both ends as opposed to a cantilever beam. This will lower the bending of feature B which was the location of maximum stress. 

![](study_2_excel.jpg)
![](study_2_screenshots(4).jpg)
![](study_2_screenshots(5).jpg)
![](study_2_screenshots(6).jpg)
![](study_2_screenshots(7).jpg)
![](study_2_Geometry.png)

Study 3 (Fillet Added)

Study 3 Geometric Changes- The failure point in study 2 was the joint between feature B and feature C. Particularly in the outer most edges. To combat this, I am adding a fillet at those joints. I made radius changes to the fillet after beginning study 3 when I realized that a large radius would be required to lower stresses and increase the safety factor. 
![](study_3_attempt.png)
![](study_3_excel.jpg)

Below are the results from study three. These are taken from the enlarged fillet model. They show improvements in the failure points of study two but also show where improvements can still be made. If further iterations are completed, these stress and deflection maximums are where I would target improvements. 

![](study_three(1).jpg)
![](study_three(2).jpg)
![](study_three(3).jpg)
![](study_three(4).jpg)

2157 Portion-


