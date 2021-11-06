# Coordinated-motion-planning
https://cgshop.ibr.cs.tu-bs.de/competition/cg-shop-2021/#problem-description

Given a set of n axis-aligned unit-square robots in the plane, a set S = {s_1, ...,s_n} of n distinct start pixels (unit squares) of the integer grid, and a set T = {t_1, …,t_n} of n distinct target pixels of the integer grid. During each unit of time, each robot can move (at unit speed) in a direction (north, south, east or west) to an adjacent pixel, provided the robot remains disjoint from all other robots during the motions.
This condition has to be satisfied at all times, not just when robots are at pixel positions. For example, if there are robots at each of the two adjacent pixels 
(x, y) and (x+1, y), then the robot at (x, y) can move east into position (x+1, y) only if the robot at (x+1, y) moves east at the same time, so that the two robots remain in contact, during the movement, but never overlap.

In addition, for some instances, there may be given a set of obstacles, consisting of a number of stationary, blocked pixels that cannot be used by robots at any time.

The task is to compute a set of feasible trajectories for all n robots, with the trajectory for robot i moving it from s_i to t_i.

The project was done under the supervision of Lucas casteli aleardi (Assitant professor at Ecole Polytechnique http://www.lix.polytechnique.fr/~amturing/). It was a group project that I did with my classmate Didier Ngatcha.
