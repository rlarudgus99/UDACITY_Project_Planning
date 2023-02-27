# UDACITY_Project_Planning
### Prod by KyeongHyeon Kim.

### Execution
> Terminal 1
```{.bash}
cd /opt/carla-simulator/ && ./CarlaUE4.sh
```

> Terminal 2
```{.bash}
git clone https://github.com/rlarudgus99/rlarudgus99-UDACITY_Project_Planning
```
```{.bash}
cd /project/rlarudgus99-UDACITY_Project_Planning/project && ./install-ubuntu.sh
```
```{.bash}
cd starter_files/ && cmake .
```
```{.bash}
make
```
```{.bash}
cd .. && ./run_main.sh
```

### Project Requirements
> behavior_planner_FSM.cpp
1. Lookahead distance
2. Goal behind the stopping point
3. Goal speed at stopping point
4. Goal speed in nominal sptate
5. Maintain the same goal when in DECEL_TO_STOP state
6. Calculate the distance
7. Use distance rather than speed
8. Move to STOPPED state
9. Maintain the same goal when in STOPPED state
10. Move to FOLLOW_LANE state

> cost_functions.cpp
1. Circle placement
2. Distance from circles to obstacles/actor
3. Distance between last point on spiral and main goal

> motion_planner.cpp
1. Perpendicular direction
2. Offset goal location

> velocity_profile_generator.cpp
1. Calculate the distance
2. Calculate the Final speed

> planning_params.h
1. Set the number of paths
2. Set the number of points in the spiral

https://user-images.githubusercontent.com/98406354/221494397-bc7aeaea-7bd8-42fa-9cfe-e8706eec6b14.mp4




