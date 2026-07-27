# Distance Sensor
![](img/DistanceSensor03.jpg)

## **Introduction**
<font style="color:rgb(44, 44, 54);">The distance sensor detects the distance between objects and the sensor, with a detection range of 0~255 cm.  </font>

<font style="color:rgba(0, 0, 0, 0.85);">Using laser reflection principles, the sensor measures the round-trip time of laser signals to calculate the absolute distance between the sensor and the target. The sensor emits laser at a wavelength of 940 nm and completes distance measurements up to 2 meters in under 30 ms.  </font>

_**<font style="color:#8A8F8D;">Note:</font>**__<font style="color:#8A8F8D;"> The VL6180X measures distance based on </font>__**<font style="color:#8A8F8D;">Time-of-Flight (ToF)</font>**__<font style="color:#8A8F8D;"> technology. Therefore, its measurement accuracy is affected by the target's surface reflectivity, material properties, and orientation.</font>_

1. _**<font style="color:#8A8F8D;">Target Reflectivity:</font>**__<font style="color:#8A8F8D;"> Black or highly light-absorbing materials can significantly reduce the maximum measurable distance. </font>_
2. _**<font style="color:#8A8F8D;">Ambient Light:</font>**__<font style="color:#8A8F8D;"> Strong sunlight or infrared interference may affect measurement consistency. </font>_
3. _**<font style="color:#8A8F8D;">Angle of Incidence:</font>**__<font style="color:#8A8F8D;"> When the target surface is not perpendicular to the sensor (incidence angle > 10°), reduced reflected light intensity may introduce measurement errors. </font>_
4. _**<font style="color:#8A8F8D;">Temperature Drift:</font>**__<font style="color:#8A8F8D;"> Changes in the sensor's internal temperature may cause slight variations in the absolute distance measurement. </font>_
5. _**<font style="color:#8A8F8D;">Optical Cover and Window Material:</font>**__<font style="color:#8A8F8D;"> If an external lens or protective window is used, factory calibration and compensation are recommended to ensure optimal measurement accuracy.</font>_


## Structure  
![](img/DistanceSensor04.png)

| No.   | Name   | Description   |
| :---: | :---: | :---: |
| ① | Icon | Green imprint for module type identification   |
| ② | Pinhole | <font style="color:rgb(44, 44, 54);"> Connects and secures building blocks via pinholes  </font> |
| ③ |  RJ11 Port   | <font style="color:rgb(44, 44, 54);">Applicable to the crystal head connecting cable  </font> |
| ④ |  Groove   | <font style="color:rgb(44, 44, 54);">Connects and secures building blocks via grooves  </font> |


## Specifications  
| Item |  Description   |
| :---: | :---: |
| Name |     B0100004 |
| Code | ICBricks Distance Sensor   |
| Dimensions   | 31.8x31.8x28 mm |
| Weight   | 15 g |
| Material   | ABS |
| Operating Voltage   | 3.3 V |
| Operating Voltage   | RJ11 Port   |
| Communication   | I<sup>2</sup>C |
| Detection Data   | 0~255 |


## Usage Instructions  
| Type |  Description   |
| :---: | --- |
|  Application Modes   | Logic control mode, programming control mode. |
|   Connection Method    | Establish a connection with the hub through the Crystal Head Connector.  |
| <font style="color:rgb(44, 44, 54);"> Status Detection  </font> | <font style="color:rgb(44, 44, 54);"> Detects the distance between objects and the sensor to adjust the corresponding actuator or character accordingly.  </font> |


