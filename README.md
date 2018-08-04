# DS3231
RTC variations

Introduction 
DS3231 is equipped with integrated TCXO and crystal, which makes it a cost-effective I2C real time clock with high precision. 
The device carries a battery input, so if you disconnect the main power supply, it can still maintain accurate timing. 
The integrated oscillator ensures the long-term accuracy of the device and reduces the number of components. 
DS3231 provides both commercial and industrial temperature range and supports 16 pins small-outline package (300mil). 
The module itself can adapt to the system of 3.3V and 5V without level switch, which is quite convenient! 

Specification 
Temperature range: -40 to +85; 
Timing accuracy : ± 5ppm (±0.432 seconds / day) 
Provide battery backup for continuous timing 
Low power consumption 
Device package and function compatible with DS3231 
Complete clock calendar function contains seconds and minutes, hour, week, date, month, and year timing and provides leap year compensation until 2100. 
Two calendar clock Output: 1Hz and 32.768kHz 
Reset output and Input Debounce of Pushbutton  
High speed  (400kHz), I2C serial bus Supply voltage: +3.3V to +5.5V  Digital temperature sensor with a precision of±3℃ Working temperature: -40 ~ C to +85 ~ C   16 pins Small Outline Package (300mil) Certified by American Association of Underwriters Laboratories (UL)  Size: 30*20mm Weight: 4g 

Circuit connection 
This module adopts the IIC test method, so we only need to connect ‗SDA‘ to Arduino A4, ‗SCL‘ to A5, ‗+‘ to VCC and ‗-‘ to GND as follows: Connection for unoR3: 
Syntax Coloring Map for NewSoftSerial
Datatypes (KEYWORD1): Sodaq_DS3231, DateTime	
Methods and Functions (KEYWORD2): second, minute, hour, date, month, year, active, dayOfWeek, get, begin, setDateTime, enableInterrupts, disableInterrupts, clearINTStatus, convertTemperature, getTemperature, now
Instances (KEYWORD3): rtc	
Constants (LITERAL1): EverySecond, EveryMinute, EveryHour, EveryMonth
