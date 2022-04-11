# Voice-Controlled-Mecanum-Based-Forklift-(VOCMEF)-

Skills : Mechatronics , IoT , Robotics , Electronics , Machine Learning , Communication

This project is made by me (Manali Pawar ) , Shivansh Dubey , Vishal Gosain and Ayush Agarwal . The CAD files, ML model and its weights , Proteus , Arduino files have been uploaded in this repository itself . This project was made under a time span of 14 days . This project also secured 3rd rank in Robotics Conclave , a competition held under Technex , tech fest of IIT BHU Varanasi

## Introduction and the problem statment taken by us :
After an analysis of videos of the traditional forklifts availaible online , it was observed by that the present forklift model used in the factories has certain drawbacks which I could solve . Some of those are :

Forward toppling of the goods being carried
Sideways toppling of the goods being carried
Overturning / Toppling of the forklift itself
Injuries to the human operating the machine
Wasteage of large amount of industrial goods
Reference videos :

https://www.youtube.com/watch?v=GEMyqZ3ShFs

https://www.youtube.com/watch?v=zwOa-dB-t3g

## The VOCMEF (VOice Controlled Mecanum based Forklift )
image

The above image shows the structure of the VOCMEF as made by me on the CAD software .

The VOCMEF has rollers , 2 DoF Robotic arm like structure , Normal forklift lifting part with additional belt rollers , scissor lifter , double wishbone suspension , Mecanum wheels , central plate like structure , microprocessor etc .

## Operation of the VOCMEF
The VOCMEF is optimised to lift both boxed goods as well as collection of smaller goods ( which I saw was also one of the things forklifts were used for in the videos ) .

For the boxed goods , the vocmef approaches from the roller side . First the robotic arms squeeze and hold the box from the side , then the roller rolls , thus making the box lie down on the central plate . This gives the box low center of gravity thus giving advantages which I will explain in the next part . Then , while unloading , the central plate moves up to the height required and the robotic arms push the box , thus being optimised to put the goods at a height too .

For a collection of objects (say a bunch of metal sheets ) , we can use the side of the structure that is similar to the original forklift . However , unlike the former forklift , there are belt rollers on it , so that first the object is put on it , then it is rolled to the center plate , which keeps the goods more stable , hence gives advantages which I will explain in the next session .

## Advantages over the traditional forklift
Prevents the sideways toppling : Since there is a robot arm on the side , the extended rod like structure prevents the sideways toppling of the goods .
Prevents the forward toppling : Since the goods are now closer to the center of the forklift , thus providing more stability compared to the traditional forklift where the goods used to fall off the edge due to disbalance .
Boxes optimisation : VOCMEF is optimised to differently lift boxes and stacks . While lifting boxes it can provide even lower center of gravity due to keeping it sideways (lying position ) , thus even more topple free conditions .
Reduces Forklift Toppling : As the goods are kept more towards the center , just above the stability zone , hence avoids the toppling of the forklift itself .
Reduces Human Injury : Since VOCMEF is voice controlled , hence there is no human worker requires 'on' the machine , hence preventing human injury which happened in the existing forklifts .
More capacity : Since there is no human operator on the machine itself , there is more space on the machine , hence it can carry more goods at a time .
WFH for factory workers : VOCMEF even enables the factory workers to do work from home , given that they are given the live surveillance footage of the warehouse / factory , since the machine can be controlled by voice only or even by sending signals using phone .
Better motion and stability : Usage of Mecanum wheels allows VOCMEF to move in all directions which is suitable since most warehouses might not have the space to make a full turn like the ackerman or any other normal steering system and the double wishbone suspension is an indepedent suspension , meaning both wheels have a suspension independent of the other side wheel , thus introducing even more stability to the VOCMEF .
image

Mechatronic model of the VOCMEF :
image

Machine Learning part of the project :
Datasets :

http://storage.googleapis.com/download.tensorflow.org/data/mini_speech_commands.zip
https://www.kaggle.com/c/tensorflow-speech-recognition-challenge/data
ML model along with weights have been uploaded in this repository . Details best explained in slides :

image

image

Electronics part of the project (Arduino and Proteus) :
image

image

Robotics part of the project (Mecanum wheels dynamics ) :
image

Communication part (Hamming Code ) :
Hamming code is a self correcting code , i.e. it can detect as well as correct 1 bit errors in the digital message transferred . It has been used here to ensure error free transmission of the digital information regarding the commands .

image

Mechanical Design part (CAD model pictures) :
image

Simulation part :
For simulation part of the project , see the video which has been uploaded in this repository .
