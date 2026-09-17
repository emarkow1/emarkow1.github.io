# Lightning Board

![Lightning Board](Lightning_Board.png)

## Motivation

FSAE rules require a tractive system status indicator to be present on the top of the vehicle. This indicator must show solid green when there are no faults in the tractive system and must flash red whenever there is a fault indicated by either the IMD or the BMS. NER's solution for the 2025 Competition was fully analog, which limited the ability of the indicator to cope with startup and edge cases. The Lightning board implements an MCU to communicate with the VCU over the CAN bus to ensure that faults are accurately represented and that the indicator does not show a fault simply because the car has not completed it's POST sequence.

Taking advantage of it's position on the car Lightning Board also implements a suite of motion sensors to provide the mechanical team with data on the car's orientation and acceleration. Lightning Board is so named due to the inclusion of an AS3935 lightning sensor, which is used to detect lightning strikes in the vicinity of the car. Lightning Board also implements a MIPI serializer to allow for the use of a camera on the car.

## Technical Specifications

- STM32H563 MCU
- CAN communication
- IMU, gyroscope, and magnetometer
- AS3935 Lightning Sensor
- Red, Green, and Amber LEDs for tractive system status indication
- MIPI serializer for camera communication

## Schematics

![Lightning_Board_PDF-01](Lightning_Board_PDF-01.png)
![Lightning_Board_PDF-02](Lightning_Board_PDF-02.png)
![Lightning_Board_PDF-03](Lightning_Board_PDF-03.png)
![Lightning_Board_PDF-04](Lightning_Board_PDF-04.png)
![Lightning_Board_PDF-05](Lightning_Board_PDF-05.png)
![Lightning_Board_PDF-06](Lightning_Board_PDF-06.png)
![Lightning_Board_PDF-07](Lightning_Board_PDF-07.png)
![Lightning_Board_PDF-08](Lightning_Board_PDF-08.png)
![Lightning_Board_PDF-09](Lightning_Board_PDF-09.png)
![Lightning_Board_PDF-10](Lightning_Board_PDF-10.png)
![Lightning_Board_PDF-11](Lightning_Board_PDF-11.png)
![Lightning_Board_PDF-12](Lightning_Board_PDF-12.png)
![Lightning_Board_PDF-13](Lightning_Board_PDF-13.png)
![Lightning_Board_PDF-14](Lightning_Board_PDF-14.png)

## Layout

![Lightning_Board_Layer_1](Lightning_Board_Layer_1.png)
![Lightning_Board_Layer_2](Lightning_Board_Layer_2.png)
![Lightning_Board_Layer_3](Lightning_Board_Layer_3.png)
![Lightning_Board_Layer_4](Lightning_Board_Layer_4.png) 