# Drone-101
Hey Drone enthusiasts!! If you are a beginner in dronetech then it is the ultimate guide to start your drone journey. So ladies and gentlemen, welcome aboard Drone 101. Please tighten your seat belts and get ready for takeoff as we embark on an exciting journey into the world of drones. 🚀

# What is Drone and why should we learn about drones ??
An unmanned aerial vehicle (UAV), commonly known as a drone, is an aircraft without any human pilot, crew, or passengers on board.Drones, or Unmanned Aerial Vehicles (UAVs), offer significant benefits across various industries by providing unique aerial perspectives for photography and videography, precise mapping and surveying capabilities, and efficient agricultural monitoring. They enhance safety and efficiency in inspection and maintenance of hard-to-reach infrastructure, support disaster management and search and rescue operations, and facilitate environmental monitoring and scientific research. Additionally, drones streamline delivery services, assist in law enforcement and security, and provide new entertainment and recreational opportunities. Their cost-effectiveness, speed, and precision make them invaluable tools for improving productivity and achieving tasks that were previously difficult or impossible.
Basically, a drone is a flying robot which can be under remote control or fly autonomously via software-controlled flight plans in its embedded systems, working in collaboration with onboard sensors and GPS.

![](https://github.com/Bhaveshmeghwal21/GIFs/blob/main/gif_summer_camp/Screenshot%202024-06-02%20114027.png)

## Type of drones
Basically, there are two main types of drone platforms: rotor and fixed-wing. In particular, rotor type is then divided into single-rotor or multi-rotor such as tricopters, quadcopters, hexacopters, and octocopters. While, on the other hand, the fixed-wing genre includes the hybrid vertical takeoff and landing drones that don’t call for runways.
for more details check out [Everything you need to know about drones](https://droneforbeginners.com/drones-guide/)

# Components of drones
## Propellers 
As we know it, every UAV need some kind of device to convert engine power to usable form term thrust. With few exceptions nearly all of the early practical UAV designs used propellers to create a necessary thrust.

A propeller normally consists of two or more blades attached to a central hub which ts mounted on a brushless DC motor or engine crankshaft. The purpose of the propeller is to convert rotation power to useful thrust. The blades, which are actually rotating wings have a leading edge, traillng edge, tip, shank, face and back as shown in Figures. The fixed-pitch propeller is the most Widely used propeller design in aviation. A fixed-pitch propeller may be made of wood, aluminum, or steel and is considered to be of one-piece construction with a blade angle that cannot normally be changed.

![](https://github.com/Bhaveshmeghwal21/GIFs/blob/main/gif_summer_camp/propeller%20labelled.jpg)

For advance info about propellers check out [Aircraft propellers and controls](https://shashibgroup.org/elearning/PDF/General-Books/Aircraft-propeller-controls-by-Frank-Delf.pdf)
## Frame
A drone frame is the structural chassis or body of the drone that supports and holds all its components together, including the motors, propellers, flight controller, battery, and payload. The frame is typically made from materials like carbon fiber, aluminum, plastic, or composite materials, chosen for their strength, durability, and lightweight properties.
- Structural Integrity:
The frame provides the necessary strength and rigidity to withstand the forces and stresses experienced during flight, including impacts and vibrations. A well-designed frame ensures the drone remains stable and intact.
- Weight Management:
The frame’s material and design significantly influence the drone’s overall weight. A lightweight yet strong frame is essential for optimizing flight performance, increasing flight time, and enhancing maneuverability.
- Component Support and Protection:
The frame securely holds all the drone’s components in place, ensuring they function correctly. It also provides protection to sensitive parts like the flight controller, cameras, and sensors from damage during crashes or rough landings.
- Aerodynamics:
The frame design affects the drone’s aerodynamics, impacting its efficiency, stability, and speed. A streamlined frame reduces air resistance, allowing for smoother and more efficient flight.
- Customization and Modularity:
Many drone frames are designed to be modular, allowing for easy customization and upgrades. This flexibility enables users to add or replace components, such as different types of cameras, sensors, or payloads, to suit specific applications.
- Durability and Longevity:
A high-quality frame made from durable materials can extend the drone’s lifespan by withstanding wear and tear. This durability is crucial for drones used in demanding environments or for professional purposes.
- Safety:
A robust frame contributes to the overall safety of the drone by ensuring that critical components remain protected during operation. It also helps prevent parts from coming loose or getting damaged, which could lead to malfunctions or accidents.
![](https://github.com/Bhaveshmeghwal21/GIFs/blob/main/gif_summer_camp/Screenshot%202024-06-03%20000613.png)


## Brushless Motors -
A brushless DC motor (also known as a BLDC motor or BL motor) is an electronically commuted DC motor which does not have brushes. The controller provides pulses of current to the motor windings which control the speed and torque of the synchronous motor.
In reality, all the most recent drones utilize a brushless electric “out-runner” genre, making it one of the essential components of a drone. This is more reliable, more efficient, and quieter compared to a brushed motor. Motor with higher efficiency not only saves battery life but also gives the operator more flying time.
 It uses an electronic controller to switch DC currents to the motor windings producing magnetic fields that effectively rotate in space and which the permanent magnet rotor follows. 
 For working principle of BLDC motor check out [BLDC](https://www.automate.org/motion-control/blogs/what-is-a-brushless-dc-motor-and-how-does-it-work#:~:text=A%20brushless%20DC%20motor%20is%20essentially%20flipped%20inside,stator%20to%20rotate%20the%20rotor%20a%20full%20360-degrees.)


**Understanding BLDC motor specifications**
Brushless motors use a standard numbering scheme to describe their physical size and Kv rating. For example: let's assume we have a 5055-3000Kv Brushless Outrunner Motor. We break the numbers out as follows:  [50] [55] - [3000]
- [50] The first two numbers represent the diameter of the motor's housing in millimeters; in this example 50mm
- [55] The second two numbers represent the length of the motor housing in millimeters; in this example 55mm
- [3000] The numbers after the dash represent the Kv rating of the motor; in this example 3000Kv. The Kv rating (not to be confused with kilo-volt) is the RPM of the motor (k) per volt (V) with no load. For example, a brushless motor with a Kv rating of 3000 powered by a 12V power source would be capable of 36,000 RPMs (multiply 3000x12). This is the max RPMs that this motor can reach under no load. A motor with a higher Kv will have more top end speed, but not as much acceleration/torque. A motor with a lower Kv will not be as fast, but will accelerate faster and have more torque.

**Note:**
- The ideal number of rpm of a motor for you is dependent on what type of copter you’re looking for. For example, if you’re looking for a high performance, acrobatic copter, a high rpm motor is the one for you, meaning of course a high Kv rating. This is intuitive because these acrobatic copters are generally of the smaller variety, meaning a smaller motor, leading to smaller propellers. When you have these smaller propellers, the motors need to produce more rpm in order to produce the necessary thrust. However, this means that these motors use up more power than others, and so are less efficient.
- On the other hand, if you would like your copter to use the least amount of power as possible, and so last longer and be more stable, then motors with lower rpm are ideal. An example for when these types of motors would be useful is in taking aerial photos. Again, this is partly due to the fact that the type of copters used for this these tasks are bigger in order to carry the necessary equipment, meaning larger propellers, which will create more thrust when rotated. They therefore require fewer rpm.

for more info check out[Brushless motors - how they work and what the numbers mean](https://www.dronetrest.com/t/brushless-motors-how-they-work-and-what-the-numbers-mean/564)

for eg check out this [emax mt2213-935Kv](https://robu.in/product/emax-mt2213-935kv-bldc-motor-ccw-prop1045-combo-original/)

 ![](https://github.com/Bhaveshmeghwal21/GIFs/blob/main/gif_summer_camp/mt2213.jpg)
 
## Electronic speed controller
The electronic speed controller (ESC) is an essential part of an electric propulsion system’s hardware. It acts like the brain of the system by telling the motor how fast to go based on data signals it receives from the throttle controller.For smaller applications like drones and RC vehicles, this controller has the name ‘ESC’, whereas for larger manufacturing applications it may be called an electronic control unit, inverter, or motor controller. Also, it plays a role in converting DC battery power into 3-phase AC for running brushless motors.

The mechanism within the ESC as well as its interaction with the battery and motor are quite fascinating.(you can check out [this article](https://www.tytorobotics.com/blogs/articles/what-is-an-esc-how-does-an-esc-work)
The good-quality ESC gives a reliable and smooth flight experience. Several factors are considered while selecting the ESC, and they are as follows:
1. Current Rating
2. Input Voltage Rating
3. Weight and Size
4. ESC Firmware
5. BEC
6. Connection of ESC
7. ESC processors
8. ESC Protocols

### 1. Current Rating-
The first thing to consider when selecting an ESC is the current rating (ampere rating).  Motors draw current when they spin; if you draw more current than your Electronics Speed Controller's capacity, then it will start to overheat and eventually damage. You should decide on the current rating of the ESC after selecting a suitable motor size for your requirements. 
Mostly 3 things can increase the current draw of your esc:
- High KV ratings of the motor
- Larger propellers (length and pitch)
- Larger motor size (stator width and height)
There are two current ratings of ESC, and they are continuous and burst. The continuous current rating indicates the maximum continuous current that ESC can handle safely. The burst rating means the maximum current that the ESC can handle for a short period (e.g., 10 seconds) without damaging the ESC itself.

### 2. Input Voltage
The voltage rating of an ESC is the maximum amount of voltage that your ESC can handle safely.  Some of the ESCs support 3S–4S battery voltage, while others can support 6S battery voltage. Here, make sure that they are compatible with the LiPo battery voltage. Powering your ESC with excessively high voltage will damage your ESC as well as the motor.

### 3. Weight and Size 
The weight and size of an ESC are dependent on its current rating. It is challenging to make ESCs lighter and smaller without losing their performance and effective cooling. Mostly, single standalone ESCs are designed with a weight of around 4 grams to 6 grams, and the 4-in-1 ESC weighs around 12 grams to 15 grams. Generally, the lighter ESCs have lower heat dissipation, which leads to concerns about overheating.

### 4. Electronic Speed Controller Firmware
ESC firmware is the software that is running on each ESC. It determines the performance of the ESC. The ESC firmware gives information about its supported protocols and configuration interface. There are different types of ESC firmware available.
- BLHeli ESC.
- BLHeli_S ESC
- SimonK ESC
- KISS firmware
- BLHeli_32

Out of these, BLheli firmware and Simonk firmware are open sources, and KISS firmware is closed source, meaning it can run with only KISS ESC.
### 5. BEC 
BEC stands for Battery Elimination Circuit. The BEC provides the constant current at a specific voltage. It has a 5V output for powering the flight controller, a radio receiver (RX), and other 5V components. But nowadays, in the quadcopter system, the power distribution board is used, so we don’t need ESCs with BEC.
The ESC without BES is known as the Opto ESC. Without the 5V BEC, your flight controller and RX will require a separate power source. As per the above image(1), an Optp ESC doesn't have the “red” servo wire. It uses only the signal and ground wire.

![](https://github.com/Bhaveshmeghwal21/GIFs/blob/main/gif_summer_camp/EMAX-BLHELI-30A-600x600.jpg) 
(1)
![](https://github.com/Bhaveshmeghwal21/GIFs/blob/main/gif_summer_camp/without%20BEC%20esc.jpg)
(2)

### 6. Connection of Electronics Speed controller with Motor
ESC uses a LiPo battery to power up. The signal received from the flight controller controls the speed of the motor. A brushless ESC has three wires that it directly plugs into or gets soldered to the 3 wires of the motor.  The below image shows the single standalone ESC with LIPO battery, RC receiver, and brushless motor.

![](https://robu.in/wp-content/uploads/2021/01/SimonK-30A-BLDC-ESC-1-1.jpg)

### 7. ESC Protocols
Protocols are like the operating system of the ESC. They determine how fast communication happens between the ESC and FC (flight controller), which plays a major role in the handling and performance of a quadcopter.

Here is a list of current protocols used on quadcopters, from oldest to latest:

- Standard PWM
- Oneshot125
- Oneshot42
- Multishot
- DShot
- ProShot
To know more about it refer to [Electronics Speed controller calibration Protocol](https://robu.in/what-is-oneshot-and-multishot-in-esc-difference-between-oneshot-and-multishot-esc-esc-calibration-protocol/)
### 8. ESC Processors
Most ESCs use processors from ATMEL, Silabs, and ARM Cortex. All these processors have different features and specifications and support different firmware.

- ATMEL 8-bit is compatible with both SimonK and BLHeli firmware
- SILABS 8-bit is compatible with  BLHeli or BLHeli_S only
- ARM Cortex 32-bit (e.g. STM32 F0, F3, L4)  can run with BLHeli_3
I hope this article helps you learn about the basics of ESCs. With the help of this article, you can easily choose the perfect ESC for your multirotor.

To calibrate your ESC with the motor and RC transmitter, refer to the tutorial, [Connecting motors and calibrating ESCs](https://robu.in/connecting-motors-and-calibrating-escs/)

_**[Reference](https://robu.in/how-to-choose-esc-for-your-quadcopter/#Electronics_Speed_Controller_Firmware)**_

