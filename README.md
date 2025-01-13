# spinali-flow-design
Design files for flow module using 2-wire automotive enet and CANFD.

## Folder Layout
### kicad
Do not forget to add the [associated kicad library](https://github.com/CogniPilot/spinali_kicad_libs).

Folder layout for kicad 8 based projects
- ***flow_afbr:*** Broadcom AFBR distance based unit
- ***flow_vl53:*** ST VL53 distance based unit
- ***flow_max:*** Two flow sensors and two distance sensors (close and far)

### docs
- ***mcu:***
	- ***mcxn:*** NXP mcxn datasheets
- ***sensors:*** 
	- ***distance:*** 
		- ***broadcom:*** broadcom afbr distance sensor datasheets
		- ***stm:*** stm vl53 distance sensor datasheets
	- ***imu:***
		- ***tdk:*** invensense imu datasheets
	- ***optical_flow:*** 
		- ***pixart:*** pixart flow sensors datasheets
