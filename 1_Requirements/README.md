**Seat Heating Application:**


The buttons have to be switched on before the app starts working. Potentiometer acts as temperature sensor.
It gives signal which is converted by ADC and used to make a PWM signal pf corresponding duty cycle, as seen in the oscilloscope.
As potentiometer is varied, message containing detected temperature is shown in serial monitor.

**SWOT ANALYSIS:**
   
STRENGTHS:

	1. User  friendly
	
	2. Easy to change temperature
	
	3. Low cost
	
	4. Can be installed easily
  
WEAKNESS:

        Applicable to cold countries.
    
OPPORTUNITIES:

        Can be used for other applications by changing the sensors.
     
Threats:

        Not suitable for high temperature  regions.
     
     
**Challenges faced and How was it Overcome:**


|No.|	Challenge|	Solution|
|----------|:-------------:|:------------|
|1.|	On the simulide on version where some requirements are not available|	Solved in the connect session|
|2.|	Issues in running the code|	Solved by exploring in futureskills platform|
|3.|	Issues in workflows on make file|	Solved by taking out my files from the implementation part and I kept them in separate files|

**4W's and 1H:**

what:

seat Heating Application

when:

At Low temperature

Where:

At Automative Industries

**High Level Requirements:**

In the high level requirement, we must have the knowledge of Microcontroller ATmega328.

ATMega328 microcontroller: 

The ATmega 328 microcontroller is the current top of the line in the 28-pin ATmega x8 series. It has 32kB flash memory,2kB RAM,and 1kB
EEPROM. It can be considered a step up from the ATmega8. It will run at 3.3V with a 16MHz crystal, although it is not recommended due 
to the possibility of corrupting the EEPROM contents. It has 32 general purpose working registers, three flexible timer/counters with 
compare modes, internal and external interrupts, serial programmable USART, a byte-oriented 2-wire serial interface, SPI serial port, 
6-channel 10-bit A/D converter, programmable watchdog timer with internal oscillator, and five software selectable power saving modes. 
The device operates between 1.8-5.5 volts. Its maximum operating frequency is 20MHz. This is the CPU (Central Processing Unit) of our 
project. We use microcontroller ATMega328for reading the temperature and holding the monitoring and the controlling program. It receives 
the analog voltage signal coming from the sensor. After the conversion into digital signal, it checks whether the sensed value is in the 
set value. If the data doesnot come under the set parameter, then the microcontroller starts its controlling action.

![image](https://user-images.githubusercontent.com/94346768/144083604-d9c00ff7-81db-49ee-93d0-eca6ed65a257.png)






