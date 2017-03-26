## Make an autonomous robot that performs the following tasks:
1. The robot starts from **START** position of the arena representing a warehouse (Refer to [Figure 1](https://github.com/meanmachin3/Warehouse-Management-Using-Firebird-V/blob/master/arena.png)).
    * Thermocol blocks are used to represent packages. Three colors Red (R), Blue (B), or Green (G) are used to represent different **types** of packages.
    * There are twelve **pick-up points** in the warehouse where packages are placed on arrival to the warehouse.
      Each pick-up point can contain:  
        (i) **No package** – when the pick-up point is empty  
        (ii) **Valid package** – when a package of one of the colors – Red (R), Blue (B), or Green (G) – is at the pick-up point or  
        (iii) **Invalid package** – when a Black package is at the pick-up point which should not be picked up.  
      Number of valid packages to be picked up from the pick-up points can vary from 3 to 7.
    * There are five **Deposition Zones** numbered 1 to 5. 
      Each deposition zone has an associated color – only packages of that color can be deposited in that deposition zone. 
      A **deposition table** provides the information on the designated color for each deposition zone. 
      For example, if deposition zones 1 and 2 are designated as R, only red packages can be deposited in these deposition zones. 
      Each deposition zone can take a maximum of 2 packages only.
2. The robot traverses the path around the warehouse and does the following:
    * Checks pick-up point for a package.
    * If the package is **Invalid**, sounds a buzzer and moves on.
    * If the package is **Valid**, does the following:
        1. Indicates the color of the package by turning on the appropriate color in the RGB Light Emitting Diode (LED) provided with the kit.
        2. Picks up the package and deposits it in the appropriate deposition zone.
    * Robot repeats the above protocol till it picks up and deposits all the valid packages on the arena.
    * After depositing the last package at the appropriate zone, the robot sounds the buzzer continuously.
    * Sound of the continuous buzzer indicates END of task.

## Video Link
<a href="http://www.youtube.com/watch?feature=player_embedded&v=Th7MJ_w13_M
" target="_blank"><img src="http://img.youtube.com/vi/Th7MJ_w13_M/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>
