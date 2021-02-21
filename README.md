# trav_sales_alg

﻿define ten x, y coords
visit each point only once, finally returning to starting coord.
two path method.
path_A = start location to closest next point.
path_B = start location to second closest next point.
grow each path by moving to next closest point, switching back and forth.
close the path by connecting path_A and path_B.
total minimum distance calculated through above stated approximation method.

Two clumsy items:
1)  to change dataset, eit coord matrix, run script, from putput script: cut/paste 10x10 distances arraye into main.js, replacing existing Distances array.
2)  to change startin point, edit variable which_arr = from 0 to 9.
