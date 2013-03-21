WPI_WAVE_Thruster_Controller
============================

A six channel motor controller based on STMicro's VNH5019 h-bridge IC capable of 12 amps continuous 
current draw per channel with 30 amp peak. Each channel has current sensing via the built in current
sensor on the VNH5019 h-bridge IC. Current sense data is ready via SPI using the Microchip MCP3208 ADC.
The controller was designed for WPI's WAVE platform controlling 6 motors at 18.5v. Control signals are
broken out to three 10 pin headers for each of the three pairs of VNH5019s. 

Specs:
- 6 DC Brushed motors
- 12 Amps continuous current draw per channel
- Max 30 Amp peak per channel
- SPI ADC for current sension on each channel
- LEDs indicating motor direction
- 5v and 3.3v logic compatible

Released as 100% Open Source under
Creative Commons Attribution-ShareAlike 3.0 Unported License
http://creativecommons.org/licenses/by-sa/3.0/us/
