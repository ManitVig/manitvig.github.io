---
title: Compound Stresses (Plane Stress)
parent: Mechanics of Materials
nav_order: 12
---
# Compound Stresses (Plane Stress)  
As discussed earlier the general state of stress at a point is given by a stress tensor consisting 3 unique axial stresses and 3 unique shear stress components. It is mathematically represented using a 3x3 matrix for 3D space. Most mechanical systems of our concern however are coplanar, hence our complexity of analysis can be reduced by having to only analyse the general stress along one plane, called **plane stress.**  
  
The configuration of plane stress at a point A is given diagrammatically and mathematically as follows -  
![Try on](Attachments/7FBC7DC2-7695-41EB-8235-980B083FA632.png)  
## Sign convention  
For axial stresses - tensile stress are taken as positive, compressive stresses are taken as negative.  
For shear stresses - taken as positive when the tend to rotate the element clockwise.  
  
## Stress Transformations  
The value of stresses for a plane stress configuration depend upon the orientation of the plane chosen, and hence changes upon rotation of plane. Upon rotation by some angle the stresses transformations are given by -  
![angle of rotation = o](Attachments/B5FEEA88-1BED-4AD5-9A3F-2D7A23B2E222.png)  
## Matrix Notation for Stress Transformation  
Since Mathematically stress tensors are depicted using matrices, stress transformations can be views as coordinate transformations of the linear space associated with stress matrices. Hence the new state of stress can be obtained by using the rotation matrix -  
![let Q be the rotation matrix for 2nd order](Attachments/FB58487E-A886-4C38-A518-6B3043A43FC1.png)  
## Principle Stresses and Maximum Shear Stresses  
As the magnitude of stresses depend upon the orientation of the plane, in engineering practice it is often important to determine the maximum magnitudes for a stress configuration in order to design systems for it. The values of maximum and minimum normal stresses are called principle stresses, and for shear stress it’s called maximum shear stress.   
![Principle plane orientation -](Attachments/0C4224F5-D0E5-49A3-AACE-3D6782AC32A6.png)  
In the principle plane the shear strain is 0, while in maximum shear plane the normal stresses are equal to the average normal stress.  
##   
## Mohr’s Circle  
Plane stress transformations can be very easily visualised using a graphical tool known as the Mohr’s Circle. It allows us the plot our stress state a circle on 2D plane space with the x-axis depicting normal stresses and y-axis depicting shear stresses.   
![Origin of mohr circle=](Attachments/79C126D7-37D7-4621-9761-E61AABC4BE1A.png)  
Any rotation of the plane stress results in twice that rotation on the Mohr’s circle in the same direction  
  
By just plotting the origin and the two stress coordinates the circle can be drawn easily and hence the principle stresses and maximum shear stresses can be directly obtained from the Mohr’s circle.  
  
## Absolute Maximum Shear stress  
Since the strength of ductile materials depends upon its ability to resist shear stress, it becomes important to find the absolute maximum shear stress in a material when subjected to loading.  
  
Absolute maximum shear stress is obtained by considering the stress affects of a plane stress loading in all three principle plane, i.e. it is obtained for the general 3D stress unlike maximum in plane shear stress which is only for one plane.  
  
The magnitude of absolute maximum shear stress can be obtained by drawing mohr circles for all three principle planes under the plane stress loading.  
  
![*-y plane stress](Attachments/6C2B4896-E6A5-4114-92AF-C4EF64862B30.png)  
  
![Pasted Graphic 15.png](Attachments/B8C4441F-7E1F-4620-A5A2-262F054040E2.png)  
![(Ty2) max](Attachments/4F40F948-FE2C-4A55-B6DB-356AA421CDC1.png)  
  
![In this configuration where both stresses are in the](Attachments/30B1E617-0921-44FD-987D-B6880D3DAFD6.png)  
For the configuration where both the stresses will be of opposite signs, the mohr circles looks like -  
  
![(туz)mаx](Attachments/39CF65BE-2C9D-4E79-91A2-0FC0CFA20097.png)  
  
![The absolute maximum shear stress in this configuration](Attachments/4C1C4B42-8B39-40C8-A14A-F0DA64F5FCEB.png)  
## Combined Loading  
When a member is subjected to a loading state that is a combination of multiple kinds of loads, the analysis of the material response at any point on the member involves firstly determining all the different normal and shear stresses that arise at that point due to the loads.  
  
Then we employ the method of superposition to determine that net state of plane stress at that point by doing an algebraic sum of the different kinds of stresses - the normal stresses in x-direction, the normal stresses in y-direction, and the shear stresses.  
  
Strength of the material is then analysed for principle stresses and the maximum shear stress for the obtained plane stress.   
![For example let's analyse this shaft subjected to both](Attachments/286CC79B-87E3-4025-AE42-C864A931C596.png)  
