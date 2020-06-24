# PORTAL 2
![Alt text](https://upload.wikimedia.org/wikipedia/it/d/df/Portal_logo.png)

RECREATION OF THE GAME PORTAL.

PORTAL 2 is a Puzzle game-like published by Valve Corporation in 2011. This recreation in javascript using three.js & physi.js wants to be the sincerest form of flattery for
the beatiful masterpiece of videogame that Portal is.

The commands are stated also in the starting Menu,but here will be reported again:

- ![#0000ff](https://via.placeholder.com/15/c8c8c8/000000?text=+) `Use W-A-S-D to move around`
- ![#0000ff](https://via.placeholder.com/15/c8c8c8/000000?text=+) `Hold shift to sprint`
- ![#0000ff](https://via.placeholder.com/15/c8c8c8/000000?text=+) `Grab The Companion Cubes with E`
- ![#0000ff](https://via.placeholder.com/15/c8c8c8/000000?text=+) `Jump with SPACE`
- ![#0000ff](https://via.placeholder.com/15/0000ff/000000?text=+) `Use the LEFT MOUSE BUTTON to shoot the BLUE portal`
- ![#ffa500](https://via.placeholder.com/15/ffa500/000000?text=+) `Use the RIGHT MOUSE BUTTON to shoot the ORANGE portal`
- ![#0000ff](https://via.placeholder.com/15/c8c8c8/000000?text=+) `Use R to turn on/off the light`


![Alt text](https://i.gyazo.com/05ff2d83af11e9547510557b34650990.png)

# Important statement:
The mechanics that I tried to implement are extremely complex, unoptimized(for as it is now..) and very powerful. 
This brings along the major problem that if you force such mechanics,you will be able to break it. For that I implemented some respawn conditions to help the experience. 

***Known Bugs*** :
-I'm aware of how the force imprinted to the companion cubes passing the portals is slightly unstable. Don't worry, the cubes will respawn in the same spot where you found it
if they will break through the wall of the map.

-if you try to enter inside the portals with specific combination of linear velocities-directions, you may not be able to pass by. It happens very,very rarely,but still happen. 

***Fixed bugs*** :
-fixed the camera adjustment when coming out of a portal placed upside down,or with strange angles with respect to the other portal.
-added the possibility to fell forever between two portal in vertical line(signature feature for portal!)
-added the hidden control that does not allow the portals to spawn with partially compenetrated outline on other object. From now on,if you try to create a portal on a surface where there is not enough space for it to appear, the gun will just not fire.

Thanks for trying this game,and remember...

![Alt text](https://i.gyazo.com/8526fde911ebaa483f37ea63eb699a82.png)

# the cake is a lie,but the fun is not. So have fun!
