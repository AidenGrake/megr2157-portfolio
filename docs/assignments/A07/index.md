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

Now that I have the base values for the initial design, I'm going to find a finer mesh and calculate the values convergence with initial values to see if they get within 7% of error. After making the mesh finer, I got my first results and compared to my initial values. The Number of Elements was 24,639.

To solve for convergence you must use this equation: CONVERGENCE = ((OLD - NEW) / NEW) * 100%

Max Stress: ((624400 - 411800) / 411800) * 100 = 51.63%

Max Deflection: ((0.2388 - 0.1066) / 0.1066) * 100 = 124.02%

SF: ((0.058 - 0.088) / 0.088) * 100 = 34.09%

Since these values were way off 7%, I will run a finer mesh and compare results to the previous run.

<img width="500" height="500" alt="IMG6" src="IMG6.jpeg">
<img width="500" height="500" alt="IMG7" src="IMG7.jpeg">

The Number of Elements for this was 54,944 and the results are:

Max Stress: ((411800 - 485300) / 485300) * 100 = 15.15%

Max Deflection: ((0.1066 - 0.1069) / 0.1069) * 100 = 0.28%

SF: ((0.088 - 0.075) / 0.075) * 100 = 17.33%

<img width="500" height="500" alt="IMG8" src="IMG8.jpeg">
<img width="500" height="500" alt="IMG9" src="IMG9.jpeg">

Despite these results didn't meet the 7% convergence, I decided to move onto my second design.

## Second Design
For my second design, I doubled the thickness in section B of the bracket due to the fact that the majority of the stress is located there. The thickness was originally 0.0876in and now the new thickness is 0.1752in. In the screenshots below are my initials values found from the tests. The Number of Elements was 57,197 and the Safety Factor was 0.088.

<img width="500" height="500" alt="IMG10" src="IMG10.jpeg">
<img width="500" height="500" alt="IMG11" src="IMG11.jpeg">
<img width="500" height="500" alt="IMG12" src="IMG12.jpeg">
<img width="500" height="500" alt="IMG13" src="IMG13.jpeg">

Now that I have the base values for the second design, I can begin to try and get these values within 7% of a finer mesh. The Number of Elements was 93,432 after the second mesh. In the screenshots below are my  values found from the tests.

Max Stress: ((411800 - 485300) / 485300) * 100 = 15.15%

Max Deflection: ((0.1066 - 0.1069) / 0.1069) * 100 = 0.28%

SF: ((0.088 - 0.075) / 0.075) * 100 = 17.33%

<img width="500" height="500" alt="IMG14" src="IMG14.jpeg">
<img width="500" height="500" alt="IMG15" src="IMG15.jpeg">

With two of the three values didn't meet the 7% convergence, I'm going to make the mesh finer. The Number of Elements was 176,967 after the third mesh. In the screenshots below are my values found from the tests.

Max Stress: ((485300 - 515400) / 515400) * 100 = 5.84%

Max Deflection: ((0.1069 - 0.1074) / 0.1074) * 100 = 0.47%

SF: ((0.075 - 0.070) / 0.070) * 100 = 7.14%

<img width="500" height="500" alt="IMG16" src="IMG16.jpeg">
<img width="500" height="500" alt="IMG17" src="IMG17.jpeg">

Despite one of these results didn't meet the 7% convergence, I decided to move onto my third design.

## Third Design
For my third design, I added fillets to the design. I rounded off the edges of the bracket to be 0.10in to cut out weight where it wasn't needed. After doing that, I added a 0.20in to the connection of the bracket of B to the pin of A to increase strength. Finally, I added a 0.15in fillet to the connection from B to C to increase strength as it was still the higher concentrations of stress. I chose to add fillets as they don't add much weight. In the screenshots below are my initials values found from the tests. The Number of Elements was 56,888 and the Safety Factor was 0.13.

<img width="500" height="500" alt="IMG18" src="IMG18.jpeg">
<img width="500" height="500" alt="IMG19" src="IMG19.jpeg">
<img width="500" height="500" alt="IMG20" src="IMG20.jpeg">
<img width="500" height="500" alt="IMG21" src="IMG21.jpeg">

Now that I have the base values for the third design, I can begin to try and get these values within 7% of a finer mesh. The Number of Elements was 94,001 after the second mesh. In the screenshots below are my values found from the tests.

Max Stress: ((284200 - 288900) / 288900) * 100 = 1.63%

Max Deflection: ((0.09784 - 0.09797) / 0.09797) * 100 = 0.13%

SF: ((0.13 - 0.13) / 0.13) * 100 = 0.00%

Now below is the table filled out with all the values completed. 

<img width="500" height="500" alt="IMG22" src="IMG22.jpeg">

## Reflection

## 2157

## CAD Files

