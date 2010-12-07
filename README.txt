LaserBot
Copyright 2010 Cheng-Lung Lee
This repository contains dsPIC33 code for read and control XV-11 lidar data

LaserBot spec.:
MCU           : dsPICFJ64MC802
Motor         : PITTMAN GM9434H128R2 24V DC ,GEAR RATIO=19.7:1 , @ 24V max speed 313 RPM
ENCODER       : MTL MEH-17-300, 300 PPR
WHEEL Diameter: 9.6 cm
H-Bridge      : L298 Dual H-Bridge Motor Driver, 2A max each channel.
LDS motor is power by TIP102 NPN Darlington Transistor(Low side drive). Motor only need around 3.3V 65mA to operate.
OS            : Running FreeRTOS V6
Communication: BGB203 Bluetooth(Sparkfun) @115200BPS







Licensing

 Licensed under the Apache License, Version 2.0 (the "License");
 you may not use this file except in compliance with the License.
 You may obtain a copy of the License at

      http://www.apache.org/licenses/LICENSE-2.0

 Unless required by applicable law or agreed to in writing, software
 distributed under the License is distributed on an "AS IS" BASIS,
 WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 See the License for the specific language governing permissions and
 limitations under the License.

