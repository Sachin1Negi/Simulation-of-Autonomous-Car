
# Self Driving Car Simulation
Starting the CARLA Simulator in a new command prompt window ( Launching CARLA at 30 fps in a windowed screen in server mode and opening one of the default maps in the simulator that is race track)
![cd2](https://user-images.githubusercontent.com/65862893/119714852-f7f43480-be80-11eb-88aa-45cf445924da.JPG)

Now connecting the CARLA server with a python client which will run the main controller2d.py code ( this will control the vehicle and it will self drive through the race track). The simulation has been started! :-

![cd1](https://user-images.githubusercontent.com/65862893/119715102-40135700-be81-11eb-8c01-3e7647c166b9.JPG)




Car navigating along the racetrack alongwith the live plotting of its forward speed vs time, throttle force vs time, brake force vs time, steer angle vs time curves :-

![cd3](https://user-images.githubusercontent.com/65862893/119716139-6be30c80-be82-11eb-98a7-f687e9eaa728.JPG)

Live plotting of the trajectory curve of the vehicle along the waypoints(graph shows current coordinates of vehicle) :-

![cd4](https://user-images.githubusercontent.com/65862893/119716853-3854b200-be83-11eb-8c4c-9b6225542751.JPG)


A grader command :-
# [python grade_c1m7.py racetrack_waypoints.txt controller_output\trajectory.txt] 
can be run in the command prompt(in the same directory as the coursera final project to verify the accuracy of the solution and the following output is obtained)

The vehicle speed is compared with the reference speed(desired speed which was expected from the simulation). It is found that the autonomous car operates at a speed nearly equal to the reference speed.

![Figure_2](https://user-images.githubusercontent.com/65862893/119717153-92557780-be83-11eb-866a-10694a0868f9.png)

The path traversered by the final project solution (obtained through this siumlation) is compared with the waypoints of the racetrack in this graph. It was found that almost 100% waypoints were satisfied :-

![Figure_1](https://user-images.githubusercontent.com/65862893/119722957-88834280-be8a-11eb-90b5-433a7b49e0e8.png)

Link for demo video of the simulation:-
https://drive.google.com/file/d/1gnKZD60DnolTCnG7s8Wpk-GAXQKkfbH8/view?usp=sharing





