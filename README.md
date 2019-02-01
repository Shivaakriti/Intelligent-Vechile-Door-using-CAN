# Intelligent-Vechile-Door-using-CAN
Implementing the Real Time application using FreeRTOS and CAN bus protocol between the two nodes
In this respository I have provide code for one node(STM32F407) with CAN transreceiver.

-----------------------STM32F407-------------------------------------


This node consists of :-
  1.CAN Transreceiver(CAN bus interface)
  2.UltraSonic Sensor
  3.Accelerometer(SPI Interface)
  4.Connected to BeagleBone Black
  
For Accelerometer(LSI3DSH) is interface with the help of LSI3DSH library which in return use HAL Driver API
