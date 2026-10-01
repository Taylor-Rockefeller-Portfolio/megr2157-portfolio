# A6 – Multiview Drawing

## Objective

For this assignment I need to create a Multiview drawing of the A5 assignment. The drawing must be dimensioned with appropriate tolerances to match the fitment cases described in the original A5 assignment. 

![](IMG_0342.jpg)


![](IMG_0343.jpg)


![](IMG_0344.jpg)


![](IMG_0345.jpg)


![](IMG_0346.jpg)



## Parametric Design

The variables and equations shown below were created in assignment A5 in order to dimension the part parametrically. The selected equations were the thickest minimum required dimensions when evaluating for maximum stress and deflection. 

The equation for the variable "d3" is written below as it does not show fully on the image. 

= ( ( "W" * "l3" * 3 ) / ( "b3" * "stressAllowable" * 2 ) ) ^ ( 1 / 2 )

![](screenshot(255).png)


## Drawing

Below are the given dimensions of the T beam that the part will contact. The descriptions of clearances are found in Machinery's Handbook on page 651 and the accompanying tables with this fit class are on pages 654 and 655. The T beam requires various levels of sliding fits. The "a","b",and "c" dimensions are labeled with their appropriately described fits. 


![](Screenshot(256).png)

![](IMG_1600.jpg)


The dimensions of the fits vary in size and in their individual fits. I assessed each dimension of the T beam individually and determined what dimension range on the bracket would allow for the proper clearances. I found these dimension ranges by finding the tolerance that the T beam is manufactured to and the proper clearance for their fit classes. With this information I was able to create a range of dimension of the bracket that allowed their fitment relationship to stay within the allowed range with either parts maximum or minimum sizes. The tolerances will be shown on the Multiview drawing to enable manufacturing of the part to the proper specifications. 


![](IMG_1601.jpg)

![](IMG_1602.jpg)

![](IMG_0347.jpg)

![](IMG_0348.jpg)

![](IMG_0349.jpg)



## Reflections

As shown above, The equation for the variable "d3" is written below

= ( ( "W" * "l3" * 3 ) / ( "b3" * "stressAllowable" * 2 ) ) ^ ( 1 / 2 )

This is the equation for the dimension of the thickness of "Feature C", which is the lower portion of the bracket that runs along the bottom of the T beam. This dimension itself is driven by the load applied to the bracket and the depth of the bracket which I made to be 0.75 inches. If another this equation allows for an automatic update, as do all of my other equations. 

For all of the mating surfaces I applied tighter than the standard tolerances listed on the drawing. I did this to maintain fit class requirements. All other dimensions have a much lower level of precision. (usually two decimal places) I did this to allow for ease of manufacture as those faces of the part do not come into contact with the T beam or the applied load. Only drastic changes to these dimensions would have an effect on the integrity of the bracket. But the standard tolerances will keep the bracket far from the true point of failure becaue of the robust safety factor. 


## 2157 Assignment (Drawings)

# Parametric Design

For this part I found the critical dimension that I need to design my part around which was the minimum thickness due to allowable stress. I found that a cross-sectional area of 1/9 in^2 was acceptable. Using a standard 1/4" thickness I allow the width of the part to be determined. Once the largest hole diameter is determined I will know the width. My holes diameters are driven by the parametric size of the bracket and by the fitment class required of both holes. The upper hole that connects to the bracket will have a running/sliding fit (RC class), while the lower hole will have light assembly pressure (FN1). For the upper hole, the diameter currently is about 0.75 inches. As long as the diameter stays within 0.71 to 1.19 the hole needs to have a one-sided tolerance of (+) 1.2 thousandths. This is in line with an RC5 class, which will be a middle ground of precisions and ease of assembly. The lower hole will be 1" (+) 0.0005. This is based off of the 1" shaft and a fit class of FN1.

# Drawing

https://github.com/Taylor-Rockefeller-Portfolio/megr2157-portfolio/raw/refs/heads/main/docs/assignments/A06/So.Design.A6.2157.SLDPRT

https://github.com/Taylor-Rockefeller-Portfolio/megr2157-portfolio/raw/refs/heads/main/docs/assignments/A06/So.Design.A6.2157.Drawing.SLDDRW

# Reflections



![](IMG_1600.jpg)
![](IMG_1601.jpg)
![](IMG_1602.jpg)
![](screenshot(255).png)
![](IMG_0342.jpg)
![](IMG_0343.jpg)
![](IMG_0344.jpg)
![](IMG_0345.jpg)
![](IMG_0346.jpg)
![](Screenshot(256).png)


