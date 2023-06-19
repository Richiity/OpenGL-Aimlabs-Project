# OpenGL-Aimlabs-Project

This was a project based on the game AimLabs. The goal of aimlabs was to test a players shooting accuracy as well as their response time
to targets appearing and dissapearing.
We wanted to recreate this type of simulation in VR. To accomplish this, we used things like SteamVR's API, OpenVR alongside Oculus OS software 
to make and test our enviroment and functionality.

## Startup
From start up we wanted a user to be met with 3 panel screens with different functionality. Due to time constraints in class we simplified the boards to just be placeholders
that when shot would dissapear and allow a player to begin interacting with shooting the balloons in the range further down.

![image](https://github.com/Richiity/OpenGL-Aimlabs-Project/assets/39109271/9fc4c1a8-7a7d-4af9-a526-40aa11fe32aa)

<img width="440" alt="image" src="https://github.com/Richiity/OpenGL-Aimlabs-Project/assets/39109271/b8963737-15d2-474b-92bc-8f8b35e7f9e0">


## Shooting range

Upon shooting the panels, players can proceed to shoot the baloons. We used a vector to simulate the bullet path of the pistol along side some collision functions in OpenGL libraries that upon colliding with the balloons would display a yellow hitmarker circle to indicate a hit.
Pressing `Spacebar` would cause the balloon to dissapear and reappear someplace new. We designated a 3 x 3 section for baloons to randomly appear in to keep variety in spawn locations.


<img width="445" alt="image" src="https://github.com/Richiity/OpenGL-Aimlabs-Project/assets/39109271/f22b54be-b5ba-4df5-b871-c1ab4b29183e">



## Overview of Project

We did experience difficulties in doing this project such as learning and understanding how OpenGL works. Since it's more low level graphics engine compared to something like Unity or Unreal engine, a lot of the functionality we had to flesh out and figure out ourselves. It was a good experience though since it helped us better understand how meshs, textures and such work on a lower level. Creating our own functions and libraries gave us more freedom with what we wanted to do with the project, but also came with some compatability issues. Such as with the orientation of our eyes in VR, we still were not able to fix the cross-eye effect in the VR aspect as well as mapping the fire action to the buttons in the oculus controllers. Overall though it was a rewarding experience to get exposure into gaming libraries and hardware.
