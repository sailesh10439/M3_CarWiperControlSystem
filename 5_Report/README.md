<h1> CAR WIPER CONTROL SYSTEM </h2>


<h2> ABSTRACT: </h2>

The STM32F407VG-Discovery board is used to implement a car wiper control system in this project. An electric motor drives the wipers on the windshield. The wiper arms are moved by an electric motor connected to a worm gear that provides the necessary force to a long rod. A wiper is a vital component that removes rainfall or any other liquid from the windscreen of a vehicle. The previous method required manual wiper activation, and raising the wiper was a tough task. As a result, this strategy is suggested as a solution to these problems. The project's purpose is to provide automated transmission to older cars in order to improve their systems. wiping system, to improve the system by adding a sensor and an actuator, and to develop a basic software that would function seamlessly with the framework. The principle of this proposed wiper system is similar to that of other existing conventional wipers.



<h2> OBJECTIVE OF THIS PROJECT: </h2>

The project should be done using timers and the sequence of flashing of LED's RED,GREEN,BLUE and the 4th acc mode either ON or OFF mode using STM32F407,buttons,4 LED's. If we press the buttons for a long period, the car should start or stop, and the wipers' speed mode should vary.

<h2> INTRODUCTION: </h2>

A wiper is a necessary component that cleans rainfall or any other liquid from the windscreen. Wipers are designed and manufactured to remove water from a windshield. Most cars have two windshield wipers, one for the back window, and one for each headlight. The rubber blade, the wiper arm that holds the blade, a spring linkage, and portions of the wiper pivots are all visible from the outside of the car. Under the wiper, there are around six pieces called pressure points or claws, which are little arms. As part of the literature assessment for this project, two innovations were examined. Both were created with different concepts and functioning mechanisms, but the identical goal of the automobile wiper working principle. The rain sensor was a multifunctional device for automatically washing a vehicle's windscreen when it became wet from moisture, precipitation, or even dirt. It functioned by reflecting light rays in a pleasing pattern within the windscreen. When raindrops hit the windscreen, the harmony light is disrupted, causing the light beam intensity to decline. The wipers were then switched to full automatic mode by the system. It has a 0.1-second response time.It allowed for a speedy response when there were abrupt droplets of water that rendered the driver completely blind when the incident occurred. The motorist can avoid an accident by using the automatic wiper. During high traffic, such as in town, city, school zones, and other public locations, the automatic wiper is essential. Bad weather, risky driving conditions, and exhaustion can all cause a motorist to become distracted. By making driving more comfortable, the Rain Sensor lessened the driver's load. Following a wet car is no longer a bother because even 0.005 millilitres of water can be detected.


<h2> COMPONENTS AND SUPPLIES: </h2>

- STM32F407 Discovery Board.


<h2> ADVANTAGES </h2>

- It is quite simple to use.
- Less energy is consumed.
- Rain sensor-based systems are extremely simple to install.
- Individual rain sensors are fairly inexpensive.


<h2> DISADVANTAGES </h2>

- The rain sensor is activated when water falls directly on it.
- When more components, such as a rain sensor, are required, the total cost of the system rises.
- To avoid false rain detection, rain sensors must make a judgement within a few minutes.


<h2> 4W & H (WHO,WHAT,WHEN,WHERE,HOW) </h2>

<h3> WHAT: </h3>


The operational speed of a vehicle wiper is controlled by a wiper speed control mechanism based on rain conditions. To generate, the control system incorporates a rain sensor (30) that detects rain conditions. The amplitude of an analogue signal depends on the detected rain conditions.


<h3> WHY: </h3>


To keep the windscreen clean enough to give adequate view at all times. #WHEN
The windshield wipers remove rain and snow from the windshield, while the headlights improve visibility at night.


<h3> WHO: </h3>


A wiper speed control system for an automobile manages the wiper's functioning speed in response to weather conditions.


<h3> HOW: </h3>


You can adjust the speed of the car wiper system according to the rainfall


<h3> WHERE: </h3>


In general, car wipers are controlled by the stalk on the right side of the steering wheel.


<h1> SWOT ANALYSIS: </h2>


<h3> STRENGTHS: </h3>

- Low Budget.
- Big Influence on the market.
- High Bargaining Power Supliers.


<h3> WEEKNESS: </h3>

- Structural Inertia.
- High Transaction Cost.
- No Focus on Private Sector.


<h3> OPPORTUNITIES: </h3>

- Emerging New Markets.
- Technological Development.
- Demand for Saver Equipments.
- Technological Lock in of Product.


<h3> THREATS: </h3>

- Low Bargaining Power Buyers.
- Highly REgulated Industry.
- Ethical Pressure.
- Econimical Crisis.

<h2> STM32F407 DISCOVERY BOARD </h2>

This project provides practically all of the necessary information to get started with the STM32F407 Discovery Board, as well as driver code development.

- STM32F4 DISCOVERY kit was used; for further details, see STM32F4 DISCOVERY kit.
- STM32CubeIDE is a software tool; for further details, go to STM32CubeIDE.
- Because this microcontroller has many sophisticated functions, and the main goal of this project is to obtain all fundamental insights, just the needed functionalities are introduced during driver creation, and other complex functionality is left out. In the future, I may upgrade the driver and additional features.


![Schematic diagram](https://user-images.githubusercontent.com/101562643/168474421-546e9aaf-3c4e-46f8-a1c4-65d04af17ce4.png)



The STM32F407 Discovery board is powered by an STM32F407VGT6 Microcontroller with an ARM Cortex-M4F Processor that can run at up to 168MHz. This MCU has GPIO ports, TIMERS, ADCs, DACs, Flash Memory, SRAM, SPI, UART, and other peripherals. BUS-Interface is used to communicate between the processor and peripherals. There are three buses to choose from.

I-BUS (Instruction Bus) D-BUS (Data Bus) S-BUS (System Bus) I-BUS The Instruction bus of the Cortex®-M4 with FPU (Floating point unit) core is connected to the BusMatrix through this bus. The core uses this bus to get instructions. The memory carrying code (internal Flash memory/SRAM or external memories through the FSMC/FMC) is the bus's target.

<h2> HIGH LEVEL REQUIREMENTS: </h2>

| ID | DESCRIPTION | STATUS |
|:---| :---------- | :----- |
|HL1 | CAR ON and OFF | IMPLEMENTED |
|HL2 | LED GLOWING IN SEQUENCE | IMPLEMENTED |
|HL3 | WIPER SYSTEM USING STM32F407VG | IMPLEMENTED |


<h2> LOW LEVEL REQUIREMENTS: </h2>

| ID | DESCRIPTION | STATUS |
|:---| :---------- | :----- |
|HL1 - LL1 | PUSH BUTTON | IMPLEMENTED |
|HL2 - LL2 | RED, GREEN, BLUE LED's | IMPLEMENTED |


<h2> FLOWCHART: </h2>



![FLOWCHAT](https://user-images.githubusercontent.com/101562643/168219051-dbe3bbf0-a0bd-45c2-87f6-09c9803e5b6e.png)



<h2> BLOCK DIAGRAM: </H2>



![BLOCKDIAGRAM](https://user-images.githubusercontent.com/101562643/168219110-1b48449c-64df-49f8-91d3-42ef72dfc5d8.png)



<h2> SCHEMATIC DIAGRAM <h2>
  
  
  
  ![Schematic diagram](https://user-images.githubusercontent.com/101562643/168474421-546e9aaf-3c4e-46f8-a1c4-65d04af17ce4.png)

  
  
<h2> TESTCASES: </h2>

<h3> HIGH LEVEL TESTCASE: </h3>

| Test ID	| Description |	Exp.i/p	| Exp.o/p |	Actual o/p | STATUS |
| :------ | :---------- | :------ | :------ | :--------- | :----- |
| 1 | If the BUTTTON is pressed |	program execution |	Microcontroller/Engine starts |	LED ON(RED) |	PASS |
| 2	| If the BUTTTON is pressed |	program execution	| WIPER starts | LED ON(BLUE)	| PASS |
| 3	| If the BUTTTON is pressed |	program execution |	WIPER starts | LED ON(GREEN) |	PASS |
| 4	| If the BUTTTON is pressed	| program execution	| WIPER starts	| LED ON(ORANGE) |	PASS |
| 5	| If the BUTTTON is pressed	| -	| Microcontroller/Engine stops	| LED TURNED OFF |	PASS |


<h3> LOW LEVEL TESTCASE: </h3>

| Test ID	| Description |	Exp.i/p	| Exp.o/p	| Actual o/p | STATUS |
| :------ | :---------- | :------ | :------ | :--------- | :----- |
| 1	| If the BUTTTON is pressed	| program execution	| Microcontroller/Engine starts	| LED ON(RED) |	PASS |
| 2 |	If the BUTTTON is pressed | program execution |	WIPER starts and speed of wiper is slow	| LED ON(BLUE)	| PASS |
| 3 |	If the BUTTTON is pressed | program execution	| WIPER starts and speed of wiper is moderate |	LED ON(GREEN)	| PASS |
| 4 |	If the BUTTTON is pressed | program execution | WIPER starts and speed of wiper is good	| - | PASS |
| 5	| If the BUTTTON is pressed | - |	Microcontroller/Engine stops | LED TURNED OFF	| PASS |


<h2> OUTPUTS: </h2>

1.Push Button and hold it for two seconds.


![OUTPUT-1](https://user-images.githubusercontent.com/101562643/168225720-9d5b2ed9-0354-4d92-b20a-40496dfb7f81.png)




2.Wiper speed :- low


![OUTPUT-2](https://user-images.githubusercontent.com/101562643/168225894-fc116685-d2f4-47ee-9e17-481821b78870.png)




3.Wiper speed medium


![OUTPUT-3](https://user-images.githubusercontent.com/101562643/168225970-5c6fea46-2cb5-4e7a-b2a7-a4f2583fa3e9.png)




4.Wiper speed is high


![OUTPUT-4](https://user-images.githubusercontent.com/101562643/168226008-47936713-6485-4a31-811f-1e20cebf463d.png)




5.User button is pressed and held for 2 seconds, the LED is off


![OUTPUT-5](https://user-images.githubusercontent.com/101562643/168226041-a23370ec-cc3f-464d-b56d-9f9d1f8ebc72.png)

