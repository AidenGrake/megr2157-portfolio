# A4 – [Motor Mount]

## Objective
For this assignment, I was tasked with designing a motor mount for a Brushed 24V DC Gear Motor 3.6Kg.cm/46RPM w/ 99.5:1 Planetary Gearbox. Below is an example of what an assembly looks like of the motor with the mount attached. 

<img width="500" height="500" alt="IMG1" src="IMG1.jpeg">

The force that is received on the shaft of the motor is 300 Newtons. We have a safety factor required of 3. The max deformation allowed is 0.30mm. In the figure below, you can see the given dimensions of the gearbox that the motor mount will attach too. These dimensions are crucial for designing features 1 and 2. 

<img width="2000" height="2000" alt="IMG2" src="IMG2.jpeg">

## Feature 1
To design this feature, I started off by listing out all of my known and unknown factors. For my material, I chose PLA for its good yield strength and modulus of elasticity.

For my design of feature #1, I decided to make my length 45mm and my base of the feature to be 35mm. This allows plenty of room for the gearbox to fit securely into the feature. After I decided these factors, I drew out my FBD. After that, I solved the needed height using the deformation and stress equations. I ended up choosing my stress height over my deformation height, as the deformation height stuck out too much in the CAD model and I couldn't fit the shaft of the gearbox. After this, I solved the cross-sectional area of feature #1. In the figure below, are all the knowns and unknowns listed, free body diagram, algebraically and numerically solved equations.

<img width="2000" height="2000" alt="IMG3" src="IMG3.jpeg">

## Feature 2
For designing feature #2, I took a very similar approach as I did to feature #1. I chose my length to be 40mm and base to be 35mm. After this, I listed all of my knowns and unknowns, drew my free body diagram, used the same algebraic equations from feature #1 for feature #2 to solve numerically, and finally solved the cross-sectional area of feature #2. Similar to feature #1, I used my stress height over the deformation height, as the deformation height was a very large number. In the figure below, there are all the knowns and unknowns listed, the free body diagram, and the numerically solved equations.

<img width="2000" height="2000" alt="IMG4" src="IMG4.jpeg">

## Sketch
In the figure below, you can see a drawn out isometric view of the full assembly, combining feature #1 and feature #2. I also marked my important dimensions on the sketch as well.

<img width="2000" height="2000" alt="IMG5" src="IMG5.jpeg">

## CAD Model (Parametric)
I started off with my CAD model for feature #1. The first thing I did was set up my parametric equations as seen in the figure below.

<img width="2000" height="2000" alt="IMG18" src="IMG18.jpeg">

After having my parametric equations set up, I started off with the overall shape of feature #1 using values I previously solved. Afterward, I started off with the overall shape of feature #2 building it off of feature #1. From there, I then made the 18mm indent by making it 2mm deep based off the gearbox dimension. I then created my holes for the feature. I made a 6mm hole in the middle of the shaft, then using the 22mm diameter dimension from the gearbox, I was able to accurately place the 3.4mm boltholes around the indent. I was able to take advantage of Solidworks circular sketch pattern to streamline the process. Then, for feature #2, I made a 3.4mm bolthole and used centerlines around the overall shape to use the symmetric relation to easily have all four boltholes to be the same size and placed in the correct location. Finally, I added a 1.5mm fillet on the inside edge of the mount in order to minimize deflection. In the figures below is the entire CAD process.

<img width="2000" height="2000" alt="IMG7" src="IMG7.jpeg">
<img width="2000" height="2000" alt="IMG19" src="IMG19.jpeg">
<img width="2000" height="2000" alt="IMG20" src="IMG20.jpeg">
<img width="2000" height="2000" alt="IMG21" src="IMG21.jpeg">
<img width="2000" height="2000" alt="IMG22" src="IMG22.jpeg">
<img width="2000" height="2000" alt="IMG13" src="IMG13.jpeg">
<img width="2000" height="2000" alt="IMG23" src="IMG23.jpeg">

In the figure below is the completed assembly model. With both feature #1 and #2 placed and mated in the correct locations.

<img width="2000" height="2000" alt="IMG24" src="IMG24.jpeg">

## Drawings - 2157
With the CAD model complete, I created a Multiview drawing using Solidworks. I included four views; Front View, Right Side View, Top View, and an Isometric View on the sheet. As well as applying ASME standard conventions.

<img width="2000" height="2000" alt="IMG16" src="IMG16.jpeg">

## Lessons Learned
From this assignment, I learned about using the circular sketch feature in Solidworks in order to make my CAD design quicker and more efficient. Another lesson I learned is using the Solidworks drawing feature. Learning how to create drawings took some time but in the end I was able to figure it out. I also learned about reading the instructions carefully and understanding what I needed to do before jumping into an assignment. I needed to resubmit this project as I didn't do everything correctly the first time and was quick to submit. In total, this assignment took me around 4 hours to complete.

## Files

[A4Assembly.SLDPRT](A4Assembly.SLDPRT)
