# Auriga

Auriga is a custom motor controller being developed for Northeastern Electric Racing  to drive the DTI F-MOT. This is a project that I am working on slowly and it's manufacturing will depend heavily on how manufacturing of the 27A competition vehicle goes.

## Motivation

The move to in-hub motors has many advantages for the team that I won't go into here, and the best step for the team is likely simply purchasing the inverters along with the motors. That being said, there are some advantages to developing our own motor controller.
1. Full hardware and packaging control. 
    - DTI has already packaged their inverters and, while it is elegant, their enclosure is not waterproof, meaning that we would have to construct an additional container around the inverters to make them so.
2. Integration of Automotive Ethernet
    - As NER pushes for automotive ethernet on it's PCBs, this capability is left behind on COTS motor controllers, which typically only function over CAN.
    - A custom solution allows for the implementation of automotive ethernet on the motor controller.
3. Full Firmware Control
    - Any and all information can be gathered, evaluated, and tuned by the team. 

## Technical Specifications

