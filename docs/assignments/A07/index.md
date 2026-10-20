# A7 – [FEA On Bracket]

## Objective
* Use Finite Element Analysis (FEA) to improve the bracket design from previous assignments.
* Ensure high stiffness, strength, and lightweight optimization through iterative design.
* Conduct multiple FEA simulations, refining geometry based on results.
* Perform static stress analysis, including constraints, loading, and meshing selection.
* Interpret data by identifying max stress, displacement, and safety factors.
* Optimize the design by modifying geometry to enhance performance.
* Document the entire process with images, calculations, and insights.
* Reflect on key engineering lessons learned and time spent.

## Analyze
For the initial CAD setup for the FEA, I defined both the fixture of where beam holds up the bracket and the load of the strap distributed over the pin. I applied the fixed geometries to the bottom of the two flanges and then created a split load in order for the load to not act all the way around the pin but only facing down. I set my material to be ATSM A36 as it was assigned in assignment #5 and for the initial mesh I used the SolidWorks base mesh which has a total of 8847 total elements. 

<img width="500" height="500" alt="IMG0" src="IMG0.jpeg">
<img width="500" height="500" alt="IMG1" src="IMG1.jpeg">
<img width="500" height="500" alt="IMG2" src="IMG2.jpeg">

## First Design
My first design is the model I initially created for assignment #5 and #6 and the mesh will be the SolidWorks base mesh. From here, I can make the mesh finer and then find the convergence to these initial values as I continue throughout my design. 

The Max Stress after the simulation was 624,400 psi in section B of the Bracket.
The Max deflection after the simulation was 0.2388 in at the end of part A of the Bracket.
The Mass after the simulation was 0.39 lb.
The Safety Factor after the simulation was 0.058.
The Number of Elements was 8847.

<img width="500" height="500" alt="IMG3" src="IMG3.jpeg">
<img width="500" height="500" alt="IMG4" src="IMG4.jpeg">
<img width="500" height="500" alt="IMG5" src="IMG5.jpeg">

Now that I have the base values for the initial design, I'm going to find a finer mesh and calculate the values convergence with initial values to see if they get within 7% of error. After making the mesh finer, I got my first results and compared to my initial values. The Number of Elements was 24639.

To solve for convergence you must use this equation: CONVERGENCE = ((OLD - NEW) / NEW) * 100%

Max Stress: ((624400 - 411800) / 411800) * 100 = 51.63%

Max Deflection: ((0.2388 - 0.1066) / 0.1066) * 100 = 124.02%

SF: ((0.058 - 0.088) / 0.088) * 100 = 34.09%

Since these values were way off 7%, I will run a finer mesh and compare results to the previous run.

<img width="500" height="500" alt="IMG6" src="IMG6.jpeg">
<img width="500" height="500" alt="IMG7" src="IMG7.jpeg">

The Number of Elements for this was 54944 and the results are:

Max Stress: ((411800 - 485300) / 485300) * 100 = 15.15%

Max Deflection: ((0.1066 - 0.1069) / 0.1069) * 100 = 0.28%

SF: ((0.088 - 0.075) / 0.075) * 100 = 17.33%

<img width="500" height="500" alt="IMG8" src="IMG8.jpeg">
<img width="500" height="500" alt="IMG9" src="IMG9.jpeg">

Despite these results didn't meet the 7% convergence, I decided to my second design.

## Second Design

## Third Design

## Reflection

## CAD Files

