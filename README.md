# Toy Scary: A first person virtual reality survival shooter game
Course Project for EE267

![Game Logo](https://github.com/AdityaDusi97/Toy_Scary-First-Person-Virtual-Reality-Survival-Shooter-Game/blob/master/New_game.png)

This game was create as a course project for the course- EE 267: Virtual Reality at Stanford Univsersity. 
Our brief project report and key features can be found here:
https://drive.google.com/open?id=1UZtJ9otjEWJiZ83sJq35pp51lHmUopjl

# Requirements:  
* Unity 2018.3.12f1
* A desktop with a Graphics Processing Unit

We implement a survival shooter game in Virtual Reality on the HTC Vive. You play as a completely controllable character, navigating through the map and killing waves of zombie bunnies, bears and elephants. You have two weapons: 
* Assult Rifle with infinite ammunition
* Infinite number of grenades

We use both the controller of the VIVE.
* Left: Use the touchpad to move and the trigger to launch grenades.
* Right: Use to aim and pull the trigger to fire the rifle.

# Setup:
All the packages and assets needed to run the game are in provided, except SteamVR, which can be downloaded from the Assets store in Unity. The game will still run without SteamVR but it won't be rendered in stereo. The last thing to do is to set the key bindings on the controller. 

* Left controller: Options as they appear in the key bindings screen in Unity.


Control Name | Action | Type | Variable Name
------------ | ------------- | ------------ | -------------
Grip | Use as button | Click | Grab Grip
Menu | Use as button | Click | reset
Trigger | Use as trigger | Pull | grenadethrow
Trackpad | Use as button | Click | Teleport
Trackpad | Use as trackpad | Position | touchpadtouch

* Right controller: 


Control Name | Action | Type | Variable Name
------------ | ------------- | ------------ | -------------
Grip | Use as button | Click | Grab Grip
Menu | Use as button | Click | pausemenu
Trigger | Use as trigger | Pull | squeeze
Trackpad | Use as button | Click | Teleport
Trackpad | Use as trackpad | Position | touchpadtouch

Next, click *Edit Action Poses* and map *Left Hand Raw* to *Pose* and leave the rest as *Unused*. Similar thing for the right hand.

# Debugging:
* If you see compilation errors, just reimport all assets and try again
* While setting up the HTC Vive, make sure you set it up for the *Standing Only* configuration.
* Feel free to email us if you have any questions/ comments: {slorenzo, adusi}@stanford.edu

The executable game can be found here: 
https://drive.google.com/open?id=1BMHK4VwB9EHtyp_-H6MqSrEAYZjFd8zK

The source with all assets can be found here:
https://drive.google.com/open?id=1M4CVaW3OJDi9yb7v5eO5NK98x8FIrl4Q

Detailed Instructions on the game and setting can be found here:
https://drive.google.com/open?id=1acQe7frJCkgjOVa681ef5bvOoBCrcOry
