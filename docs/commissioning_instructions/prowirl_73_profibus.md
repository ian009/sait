

## Prowirl 73 Profibus



**** Need prwirl config settings *****
**** hadware has been addressed ***

1 / 7864 reset
tag & addiional info change

Manufacturer View .. Operating Menu .. Transmitter Info .. Transmitter Data
Tag Descriptor	PIT-xxx
Additional Info	FlowRun1

Manufacturer View .. Operating Menu .. Basic Setup
Measuring Mode	Pressure
Press. Eng. Unit	psi

Operating Menu ..Transmitter Info..Transmitter Data
Tag PIT-xxx
Descriptor FLOWRUN1



2712 address reset if in SW mode.  
**procedure in manual - couldn't get address to change - always greyed out **


Hardware addressing

Unscrew front cover & remove display
Hardware addressing is configured as follows:
1. Set DIP switch 10 (SW/HW) to "Off" (Down) = Hardware Addressing
2. Configure the address with DIP switches 1 to 7.
3. You have to wait 10 seconds for a change in address to take effect. The device is restarted.

DIP-Switch		1		2		3		4		5		6		7
Binary Weighting	1		2		4		8		16		32		64

Examples
Dip-Switches 3 & 4 "On" (Up) remaining Dip-Switches "OFF"(Down) : Address = 4+8 = 12


