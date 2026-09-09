# A3 – [Parametric and FEA]

## Objective
* Use axial deflection modeling to to design the dimensions
* Parametric design to determine a bars length
* Introduce us to FEA (Finite Element Analysis)
* Introduce us to nking dimensions to appropriate parameters in CAD
* Compare and contrast different analysis

<img width="2000" height="2000" alt="IMG_9984" src="IMG1.jpeg"> directions

## Analyze
I started off this assignment by writing out the parameters given to me, and choosing parameters that were unknown. I chose my force to be 400lbf, the diameter to be 0.25in, and the Young's Modulus to be 9.2x10^6. After deciding all my parameters, I did my hand calculations in the image below.

<img width="2000" height="2000" alt="IMG_9984" src="IMG1.jpeg"> math

I then started a new CAD file in Solidoworks and set up all of my parametric equations based off the hand calculations. In the image below displays all of the parametric equations set.

<img width="2000" height="2000" alt="IMG_9984" src="IMG1.jpeg"> parametric

After all the dimensions were setup into SolidWorks, it was time to to design my bar. I started off with my cross-sectional area using my diameter dimension. After, I used the extrude feature and used my length dimension to complete my bar.

<img width="2000" height="2000" alt="IMG_9984" src="IMG1.jpeg"> circle
<img width="2000" height="2000" alt="IMG_9984" src="IMG1.jpeg"> extrude

Now that the bar was complete, I added a material property to the bar before doing the FEA. I decided to choose 6061-T4 (SS) out of all the options, as the Yield Strength and Elastic Modulus were close to the values I decided. The material properties for 6061-T4 (SS) and the weight of the bar are shown below.

<img width="2000" height="2000" alt="IMG_9984" src="IMG1.jpeg"> 6061
<img width="2000" height="2000" alt="IMG_9984" src="IMG1.jpeg"> weight

From here, I started my FEA design. First I added a fixed geometry fixture on one end of the cross-sectional area and then a external force with it set to 400lbf force on the other end of the cross-sectional area. I had my force direction the opposite direction from my fixture. Following adding the features, I turned my bar into a mesh by using the mesh feature. Below are images displaying these features added.

<img width="2000" height="2000" alt="IMG_9984" src="IMG1.jpeg"> fixture
<img width="2000" height="2000" alt="IMG_9984" src="IMG1.jpeg"> force

Now that everything was setup, it was time to run the FEA tests. I ran a test for stress (von Mises), Displacement and Strain. The results of the texts are shown below.

<img width="2000" height="2000" alt="IMG_9984" src="IMG1.jpeg"> stress
<img width="2000" height="2000" alt="IMG_9984" src="IMG1.jpeg"> displace
<img width="2000" height="2000" alt="IMG_9984" src="IMG1.jpeg"> strain


## Reflection
Now that all the tests were complete, I checked the that the maximum stress is lower than the strength of Aluminum and calculated the safety factor below. I also calculated the difference in deflection based off the data gathered from my test. The calculations are shown in the image below.

<img width="2000" height="2000" alt="IMG_9984" src="IMG1.jpeg"> saftey factor

There is a meaningful discrepancy between the two deflections. I would say the root cause of the discrepancy is the material property difference. There is a meaningful difference between the Young's Modulus and the Yield Strength from the hand calculations and the actual from the 6061-T4 (SS). With this big disparity, I believe it will cause this discrepancy. I would trust the FEA results more for this design, as it actually takes into account real properties and gives real data that tested in the real world, would be very similar. 

## Lessons Learned
I learned a lot from this project. I have never used FEA before and not on Solidworks, so, learning how to setup was a difficult learning curve as I was having trouble how to add my fixed geometry in the correct dimension. I was also having trouble with my units, I didn't realize at first I could convert the units in the FEA analysis in Solidworks automatically. 

## CAD File

[SophD_25mm_Pin.SLDPRT](SophD_25mm_Pin.SLDPRT)

## Modify Design Parameters
