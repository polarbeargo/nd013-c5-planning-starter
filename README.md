### Project: Motion Planning and Decision Making for Autonomous Vehicles  
[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)  

This repository contains the starter code to launch in the SDC Planning course workspace. 

In this project, we will implement two of the main components of a traditional hierarchical planner:  
- The Behavior Planner  
- The Motion Planner  

To be able to:

- Avoid static objects (cars, bicycles and trucks) parked on the side of the road (but still invading the lane). The vehicle must avoid crashing with these vehicles by executing either a “nudge” or a “lane change” maneuver.  
- Handle any type of intersection (3-way, 4-way intersections and roundabouts) by STOPPING in all of them (by default)  
- Track the centerline on the traveling lane.  

## Run Carla Simulator to verify our result

Open new window
```
su - student
// Will say permission denied, ignore and continue
cd /opt/carla-simulator/
SDL_VIDEODRIVER=offscreen ./CarlaUE4.sh -opengl
```
## Compile and Run the Controller

Open new window
```
cd nnd013-c5-planning-starter/project
./install-ubuntu.sh
cd starter_files/
cmake .
make` (This last command compiles your c++ code, run it after every change in your code)
```
## Testing

To test your installation run the following commands.
```
cd nd013-c5-planning-starter/project`
./run_main.sh`
This will silently fail ctrl + C to stop
./run_main.sh again (again)
```
Go to desktop mode to see CARLA

If error bind is already in use, or address already being used
```
ps -aux | grep carla
kill id
```
### Result:    
https://youtu.be/FoQ_T81wBMM  
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/FoQ_T81wBMM/0.jpg)](https://youtu.be/FoQ_T81wBMM)



