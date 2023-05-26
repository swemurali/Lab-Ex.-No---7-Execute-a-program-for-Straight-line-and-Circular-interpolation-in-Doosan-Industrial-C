# Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-cobot
## Aim : To Execute a program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio.

## Components Required:

*Doosan Industrial Collaborative Robot

*DRL (Doosan Robotics Language) Studio Software

### Theory 
INTERPOLATION

Interpolation, which is necessary for any type of programming, consists of generating data points between given coordinate axis positions. Within the Machine Control Unit (MCU), a device called an interpolator causes the drives to move simultaneously from the start to the end of the command. The interpolator is either an electronic hardware device for a NC system, or a software program for a CNC system. An interpolator provides two functions:

It calculates individual axis velocities to drive the tool along the programmed path at the given feed rate.

It generates thousands of intermediate coordinate points along the programmed path between the start point and the end point of the cut.

During positioning, all programmed axes move simultaneously at the specified feed rates until each axis has reached its destination. All drives start together, but without an interpolator individual destinations are reached successively according to the path traveled. However, an interpolator coordinates these axis motions in such a way that the programmed path is constantly maintained from the beginning to the end of the movement.

Linear and circular interpolation are most commonly used in CNC programming applications:

Linear interpolation is used for straight-line machining between two points.

Circular interpolation is used for circles and arcs.

Helical interpolation, used for threads and helical forms, is available on many CNC machines.

Parabolic and cubic interpolation are used by industries that manufacture parts having complex shape such as aerospace parts, and...

## Procedure:

Manipulate the end effector as per the given configuration. Movement Should Initiate in P1 and progress till the end point. Travel path should be in sequence as stated below.


Circular Interpolation

### output
![241122861-602f1f4d-0998-4d80-acde-93a3fc671576](https://github.com/swemurali/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/94165336/08b0475a-6455-4e58-80be-b2f8f13c7302)

![241122884-3af7b607-a6c4-4dde-8ef7-d7afb4d2301f](https://github.com/swemurali/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/94165336/e3ce0d07-584e-4f95-ae4b-1397109bece1)

![241122903-b891a34d-a403-4a4c-a737-3e596a890727](https://github.com/swemurali/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/94165336/7345fed3-64f1-48c9-bc1d-b056101097e9)

![241122936-0761b8a1-3662-49ef-aa97-a93cb2b2cad8](https://github.com/swemurali/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/94165336/07ef0a26-0e0e-47bf-a0b7-1d32f4b52ca6)

![241122960-4a1ebf20-e057-4512-a8cc-56a88da28da3](https://github.com/swemurali/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/94165336/7a99676b-1c54-468c-aa30-69a865a4e160)

### Linear Interpolation
![241123018-560fb2ee-8b24-489a-8915-23af7637095a](https://github.com/swemurali/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/94165336/70677221-31cd-4f6d-86c6-376d5bcd1aa6)

### Circular Interpolation
![241123110-90543cda-8e4a-4696-a6da-612b15f3ba64](https://github.com/swemurali/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/94165336/74588beb-13d2-49c8-a51a-c4d0b7753f18)

### Results 
A program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio has been executed successfully..


 
