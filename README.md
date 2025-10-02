# Customizable VR Therapy Environment

## Keywords

Unity, Mental Health, School Project, C#

## Project Abstract

My prototype is a VR application that a user can use to provide themselves with a therapeutic experience within a controlled context by the user.

## High Level Requirement

Users should be able to easily install unity project to run in their Oculus Quest 2 Headset via the Oculus Link Cable as an external application.

## Conceptual Design

This project was conceptualized extensively in this [report](Concept_Design_Paper.pdf).

The application is split into 7 zones that introduce different functions in the first six rooms, while the final one is a "playroom" that allows you to explore all the concepts at once.

1: Besides your eyes, your hands are the 2nd human entity that your brain connects with in VR. The Oculus Quest 2 is able to use the 4 cameras to accurately track controller movement but can also track when fingers are pressed and/or released in-sync with in-game animations. 
<img width="1249" height="666" alt="hand" src="https://github.com/user-attachments/assets/b8a424e0-c9db-4ce1-a915-387bdfec2b41" />

2: Movement is one of the most challenging elements to implement in VR design because it relies heavily on the user being in control. In this prototype, I implemented a teleportation-based and a continuous movement based system.
<img width="1251" height="655" alt="movement" src="https://github.com/user-attachments/assets/3bfbf494-685c-4d2a-b8f6-61633ddf2276" />

3: While the previous rooms were important, interaction is the first leap to truly showing the essence and potential of VR. In this prototype, I implemented a hands-on (this room) and a "hands-off" ray interaction (the next room) system
<img width="1249" height="664" alt="grab" src="https://github.com/user-attachments/assets/e3690f33-d629-4c58-84e1-897327b70638" />

4: Ray interaction acts as a cruical extension of normal hands-on interaction. It allows the user to interact with both 2D and 3D elements from a distance using the controllers.
<img width="1249" height="661" alt="ray" src="https://github.com/user-attachments/assets/aaefdc9c-61e0-4f88-a7c9-2a79164c52ad" />

5: Music triggers and the general class of triggers are a nice aesthetic touch to providing a maliable environment for the user. In this room are threee music triggers they can engage with.
<img width="1251" height="661" alt="music" src="https://github.com/user-attachments/assets/5bfd8673-4e75-4364-bfec-4e544ee881e9" />

6: Finally, I wanted to expand on the realistic edge of a possible VR space for patients/users. Maybe in future prototypes, the patient could customize their VR space to fit their real-life environment, to create a more recognizable environment.
<img width="1250" height="657" alt="furniture" src="https://github.com/user-attachments/assets/694112c1-8d2c-44e4-bd39-02fa400a9c3e" />

7: This room serves as a combination of all the concepts/functions from the previous room.
<img width="1251" height="663" alt="play" src="https://github.com/user-attachments/assets/a766bf19-c6ba-4554-abe6-1ce322358d8d" />

## Live Video demo

https://youtu.be/d2dChKUb08c

## Background

This project's main solution was identified extensively in this [report](Identify_and_Define_a_Problem.pdf)

## Required Resources

o Experience in Unity Engine (editor version 2020.3.26f1)

o Access to a Oculus Quest 2 and Oculus Link Cable

o Access to a high performance gaming computer (GTX 1660/Radeon RX 590 minimum) 

o Access to ample physical space to move around environment

