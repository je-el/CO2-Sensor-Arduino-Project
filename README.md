## CS241: CO2 Arduino Sensor Project  
### Table of Contents
- [Group Members](#group-members)
- [Required Libraries and Reading](#required-libraries-and-reading-for-this-project)
- [Usage](#what-will-the-project-be-used-for)
- [Approach](#approach-and-final-design)
- [Future Development](#improvements-and-inspiration-for-the-future)
- [Components](#hardware-and-components)



### Group Members:
- Wyatt Bush
- Jewel Maldonado

#### Hardware and Components:
- Arduino Uno
- [ATLUS SCIENTIFIC EZO-UART/I2C CO2 Sensor](https://atlas-scientific.com/probes/co2-sensor/)
- 16 x 2 LCD 
- [Plastic Enclosure](https://www.amazon.com/gp/product/B075X17M4T/ref=ppx_yo_dt_b_asin_title_o03_s00?ie=UTF8&th=1)

#### Required libraries and Reading for this Project:
- [The EZO_I2C_Library](https://github.com/Atlas-Scientific/Ezo_I2c_lib)
- [The Liquid Crystal Library](https://www.arduino.cc/reference/en/libraries/liquidcrystal/)
- [EZO CO2 Sensor Manual](https://atlas-scientific.com/files/EZO_CO2_Datasheet.pdf)  

#### Inspiration for the project:
- In support of Wyatt's ASG Project Proposal of an Advance Visual CO2 Sensor.  
![imgs/ ASG_WyattBushAdvanced_Visual_Sensor.png](https://github.com/je-el/CO2-Sensor-Arduino-Project/blob/main/imgs/%20ASG_WyattBushAdvanced_Visual_Sensor.png)

#### What will the project be used for
- This CO2 sensor meter will be used to detect the actual CO2 measurements in parts per million. 

#### Approach and Final Design
- For this project we wanted to create something that would be used in a lab. So we wanted to create an interface that would be simple to use without any complex bells and whistles. We decided to opt for an enclosure and made it so that the device could be positioned well and would not interfere with the seperate measurement tools that will be used to appropriately <finish me>  

#### Improvements and Inspiration for the future
- Hardware:  
In the next iteration we hope to improve the design of the enclosure and use a better display for the output read. We hope to add a fwe components as well such as a button functionality such as changing measurement methods and turning the device on and off, a seperate battery or DC, an SD card port so that the data can be stored onto th eSD card directly, a camera sensor that can take stills of the chemical and with this we would be able to process the data by relating the measurments in ppm to the image results.  

- Code:  
Ability to output data to seperate file and save it to the SD card device attached, improve response speeds/throughput of the data, and reduce latency between the arduino and output to the display. 

