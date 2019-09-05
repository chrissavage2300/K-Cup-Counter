# K-Cup-Counter

![Idea](/idea.jpg)

This will be a small project to collect data on the number of K-Cups used in the office. It will be mounted
on top of a 5 gallon home depot bucket. 
* Battery Powered-18650 Battery since I have a few of these on hand
* 3V to 4.2V
* Integrated Charger (500mA)
* Low Battery Warning using Reset IC Chip (+1 DI)
* Reset PB (+1 DI)
* Small I2C Display
* Use Opto sensor to sense when a k-cup has entered the bucket
* Wake on signal. Use sleep mode to save power

## Display Text
* Text saying "K-Cup Counter"
* Text saying "XXXX Cups"
* Low Battery Warning 

## Possible Parts to be used
* Microcontroller: PIC18F13K22
* Microcontroller: PIC16F1503
* Microcontroller: PIC16F15323
* Battery Charger: MCP73831T-2ACI/OTCT-ND
* Low Battery Detect: APX803S-31SA-7DICT-ND
* Display: SSD1306 (I2C)

## I/O List
* Digital Inputs
	* Reset Pushbutton 
	* Low Battery Warning
	* Opto/Signal in 
	* PGD
	* PGC
	* MCLR
* Analog Inputs
	* None So Far
* Outputs
	* SCL (I2C)
	* SDA (I2C)
## Notes
* Opto Sensor may not need debouncing.
* Slot for K-Cup will be 3D printed

