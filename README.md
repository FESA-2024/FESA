# FESA
  This repository contains repositories created for FESA Teknofest Fighter UAV competition. Some of the repositeries
were designed not specific to competition itself, they were implemented as generic libraries on purpose to enhance
open source community.

## 1. Generic Softwares
### 1.1. [TSML (Thread Safe Messaging Library)](https://github.com/enessanc/TSML)
FESA project uses this library to manage inter thread communication effectively and safely. The multithreading nature of
our software benefits mostly from the hardware concurrency by parallelizing our algorithms. 
### 1.2. [Network Layer](https://github.com/enessanc/NL)
FESA project uses this library to manage communication between two endpoints in a same network. This library utilizes the 
asyncronous approach and ensures that the data is sent over the network by using TCP protocol. 
### 1.3. [FW (Fixed Wing Mavlink Interface)](https://github.com/enessanc/FW)
This library is being developed to be lightweight version of MavSDK by focusing only to fixed wing drones. It uses MavLink protocol
to communicate with autopilots, especially PX4.
## 2. Specific Softwares
### 2.1. [FlightStation](https://github.com/enessanc/FlightStation)
This softare is being written to run in the FESA fixed wing drone's flight computer.
### 2.2. [GroundStation](https://github.com/enessanc/GroundStation)
This software is being written to communicate and manage FESA fixed wing drone in ground station.
### 2.3. [FGSCommon](https://github.com/enessanc/FGSCommon)
This is a common shared library between FlightStation and GroundStation.
  
