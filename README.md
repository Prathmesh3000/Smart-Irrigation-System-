# Smart-Irrigation-System-
The advancement of technology has paved the way for the development of various smart systems aimed at improving efficiency and sustainability in different fields. The agriculture sector, in particular, can greatly benefit from smart irrigation systems, which utilize automation and data-driven decision-making to optimize water usage. 
Introduction to the
 
 “Smart Irrigation System Using Arduino Uno”:

1.1	Background
The agricultural industry is of vital importance to global food security and the economy. However, traditional irrigation practices often result in excessive water usage, leading to environmental concerns and financial inefficiency. To address these challenges, smart irrigation systems have emerged as a sustainable solution by employing advanced technologies to optimize water delivery to crops. Arduino Uno, a versatile microcontroller platform, offers an accessible and cost-effective option for building such systems.

1.2	Objectives
The primary objective of this report is to present the design, development, and implementation of a smart irrigation system using Arduino Uno. Key goals include:

- Integration of soil moisture sensors for real-time monitoring.
- Utilization of weather data to optimize irrigation schedules.
- Development of decision-making algorithms for precise water delivery.
- Control of irrigation valves based on sensor inputs.
- Evaluation of system performance, efficiency, and economic benefits.

1.3	Scope
This report focuses on the design and implementation of a smart irrigation system using Arduino Uno as the central control unit. The system integrates various sensors, actuators, and communication modules to enable real-time monitoring and intelligent decision-making. The study emphasizes the importance of precise water delivery in agriculture and explores the potential benefits of adopting smart irrigation systems.

2. Literature Review:

2.1 Smart Irrigation Systems

2.1.1 Challenges in Traditional Irrigation Methods
Traditional irrigation methods suffer from inefficiencies due to imprecise water delivery, resulting in water wastage, increased energy consumption, and decreased crop yield. This subsection highlights the challenges faced by traditional irrigation systems.

1. Inefficient water usage: Traditional irrigation methods, such as flood irrigation or open channel irrigation, tend to be less precise and result in a significant amount of water wastage. Water is often applied uniformly to the entire field, leading to overwatering in some areas and underwatering in others.

2. High labor requirements: Traditional irrigation methods often require manual labor for tasks such as opening and closing gates, monitoring water flow, and maintaining the irrigation infrastructure. This can be time-consuming and labor-intensive, especially for larger agricultural fields.

3. Limited control over water distribution: With traditional methods, it can be challenging to control the precise amount of water delivered to each plant or crop. This lack of control can result in uneven crop growth, reduced yields, and increased susceptibility to diseases and pests.

4. Energy consumption: Some traditional irrigation methods, such as pumping water from wells or using diesel-powered pumps, can consume significant amounts of energy. This adds to the operational costs and environmental impact of irrigation systems.

2.1.2 Benefits of Smart Irrigation Systems

Smart irrigation systems offer several advantages over traditional methods, including improved water efficiency, enhanced crop yield, reduced environmental impact, and cost savings. This subsection discusses the potential benefits of implementing smart irrigation systems.

1. Water conservation: Smart irrigation systems use advanced sensors and weather data to optimize watering schedules based on real-time conditions. By monitoring soil moisture levels and weather patterns, they can avoid overwatering and adjust irrigation accordingly. This leads to significant water savings and helps conserve this precious resource.

2. Cost savings: By efficiently managing water usage, smart irrigation systems can reduce water bills. They prevent unnecessary watering during rainy periods or when the soil is already adequately moist. Additionally, they can detect and alert users about leaks or faulty irrigation components, allowing for timely repairs and preventing water wastage.

3. Improved plant health: Smart irrigation systems deliver the right amount of water at the right time, promoting healthier plants. They prevent under or overwatering, which can stress plants and lead to diseases, root rot, or stunted growth. By maintaining optimal soil moisture levels, these systems help plants thrive and produce better yields.


4. Time savings: With traditional irrigation systems, manually adjusting watering schedules and monitoring soil moisture can be time-consuming. Smart irrigation systems automate these tasks by using sensors and timers. This saves significant time for homeowners, landscapers, and farmers, allowing them to focus on other essential activities.


2.2 Arduino Uno and its Applications

2.2.1 Overview of Arduino Uno
Arduino Uno is a popular microcontroller board known for its simplicity, versatility, and wide range of applications. This subsection provides an overview of Arduino Uno, its specifications, and its suitability for smart irrigation systems.

 
2.2.2 Advantages of Using Arduino Uno in Smart Irrigation Systems
Arduino Uno offers numerous advantages in the context of smart irrigation systems, including ease of use, cost-effectiveness, compatibility with various sensors and actuators, and flexibility for customization. This subsection elaborates on the benefits of using Arduino Uno as the microcontroller platform for the smart irrigation system.

2.3 Sensor Technologies for Soil Moisture Monitoring

2.3.1 Soil Moisture Sensors
The second type of smart irrigation controllers includes soil moisture sensor controllers .  Instead of using weather data, soil moisture sensor controllers utilize a soil moisture sensor placed belowground in the root zone of lawns to determine water need.  The soil moisture sensor estimates the soil volumetric water content.  Volumetric water content represents the portion of the total volume of soil occupied by water. The controllers can be adjusted to open the valves and start irrigation once the volumetric water content reaches a user-defined threshold.  The appropriate threshold value depends on soil and vegetation type and usually ranges from about 10 percent to 40 percent.  Soil moisture sensors must be installed in a representative area of the turf; far enough from sprinkler heads, tree roots, sidewalks and walls.

3. System Architecture and Design

3.1 Overview of the Smart Irrigation System

This section provides an overview of the smart irrigation system, highlighting its components, functionality, and objectives. It describes the key components of the system, including Arduino Uno, sensors, actuators, and communication modules.

Plants require really low maintenance and can be left for days without supervision but our long trips extending over a week or 2 can be detrimental for the health of plants due to the lack of moisture in the soil. In such situations, the plant may wither or die due to the absence of proper watering. In order to solve this problem, in this project, we are making an Automatic Irrigation System with an Arduino Uno which will irrigate your plants automatically and keep them healthy even when you are out of the town for weeks or months. In this project, a Moisture sensor will be used to maintain the optimum level of moisture for your plants. This system can be implemented, both for your garden or for your Indoor plants thus taking care of your leafy pets when you are away.

The logic of this system is very simple. In this system, the moisture sensor senses the moisture level of the soil and when the sensor senses a low moisture level it automatically switches the water pump with the help of a microcontroller and irrigates the plant. After supplying sufficient water, the soil gets retains the moisture hence automatically stopping the pump.

3.2 Hardware Components

3.2.1 Arduino Uno
Arduino Uno serves as the central control unit of the smart irrigation system. This subsection presents an in-depth analysis of Arduino Uno, its specifications, and its role in the system.

3.2.2 Moisture Sensor 
Various sensors, including soil moisture sensors, weather sensors, and other environmental sensors, are integrated into the system for data acquisition and monitoring. This subsection discusses the selection criteria for sensors and their integration with Arduino Uno.

3.2.3 5v relay module
Relays are the most commonly used switching device in electronics. Let us learn how to use one in our circuits based on the requirement of our project.
Before we proceed with the circuit to drive the relay we have to consider two important parameters of the relay. Once is the Trigger Voltage, this is the voltage required to turn on the relay that is to change the contact from Common->NC to Common->NO. Our relay here has 5V trigger voltage, but you can also find relays of values 3V, 6V and even 12V so select one based on the available voltage in your project. The other parameter is your Load Voltage & Current, this is the amount of voltage or current that the NC,NO or Common terminal of the relay could withstand, in our case for DC it is maximum of 30V and 10A. Make sure the load you are using falls into this range.

3.2.4 6v Mini Water Pump

This is a low cost, small size Submersible Pump Motor which can be operated from a 2.5 ~ 6V power supply. It can take up to 120 litres per hour with a very low current consumption of 220mA. Just connect tube pipe to the motor outlet, submerge it in water and power it. 
 

Make sure that the water level is always higher than the motor. The dry run may damage the motor due to heating and it will also produce noise.

SPECIFICATIONS:

Operating Current : 130 ~ 220mA
Flow Rate : 80 ~ 120 L/H
Maximum Lift : 40 ~ 110 mm
Continuous Working Life : 500 hours
Driving Mode : DC, Magnetic Driving
Material : Engineering Plastic
Outlet Outside Diameter : 7.5 mm
Outlet Inside Diameter : 5 mm
3.3 Software 

3.3.1 Firmware Development for Arduino Uno
The firmware plays a vital role in controlling the system's operations. This subsection discusses the development of firmware for Arduino Uno, including programming languages, libraries, and software tools used for coding and compiling.

3.3.2 Data Acquisition and Processing
Data acquisition involves collecting sensor data, while data processing includes filtering, calibration, and interpretation. This subsection explores the methods and algorithms used for data acquisition and processing in the smart irrigation system.

3.3.3 Decision-Making Algorithms
Decision-making algorithms are responsible for analyzing sensor and weather data to determine optimal watering schedules and control water delivery. This subsection presents different algorithms, such as threshold-based algorithms, fuzzy logic, and machine learning techniques, for decision-making in the smart irrigation system.

3.4 Integration of Sensors and Actuators
This subsection discusses the integration of sensors and actuators with Arduino Uno, including wiring connections, signal conditioning, and synchronization for real-time monitoring and control.

3.5 Communication Modules
Communication modules enable data transmission between the smart irrigation system and external devices, such as smartphones or cloud platforms. This subsection explores the selection and integration of communication modules, along with the configuration of wireless communication protocols.

4. Results and Analysis
4.1 Performance Analysis
4.1.1 Comparison with Traditional Irrigation Methods
This subsection compares the performance of the smart irrigation system with traditional irrigation methods, highlighting the advantages of the smart system in terms of water savings, crop yield, and efficiency.

4.1.2 Efficiency and Water Savings
This subsection analyzes the efficiency and water savings achieved by the smart irrigation system. It presents data on water consumption, water loss reduction, and irrigation schedule optimization.

4.1.3 Crop Yield Enhancement
The smart irrigation system aims to improve crop yield through precise water delivery. This subsection evaluates the impact of the system on crop growth, yield, and overall productivity.

5. Circuit diagram 

Circuit Diagram of the Arduino Automatic irrigation system
The complete circuit diagram for the Arduino Automatic irrigation system is shown below:
Arduino Automatic Irrigation System Circuit Diagram
In this section, I will explain all the details with the help of the schematic diagram. The Arduino UNO is the brain of this whole project. It controls the motor pump according to the moisture in the soil which is given by the moisture sensor.

To power the circuit, I am using an external Battery. You can use any 9v or 12-volt battery. The battery is connected to the Vin and ground pins of Arduino and we can also connect the motor to this battery via a relay. Moisture sensor output is connected to the analog pin of Arduino. Do remember to use the Arduino’s 5volt pin to power the sensor and relay module.
6.Working of project
           The working of the soil moisture sensor is very easy to understand. It has 2 probes with exposed contacts that act like a variable resistor whose resistance varies according to the water content in the soil. This resistance is inversely proportional to the soil moisture which means that higher water in the soil means better conductivity and hence a lower resistance. While the lower water in the soil means poor conductivity and will result in higher resistance. The sensor produces an analog voltage output according to the resistance.

The sensor comes with an electronic module that connects the probe to the Arduino. The module has an LM393 High Precision Comparator which converts the analog signal to a Digital Output which is fed to the microcontroller. We have covered an in-depth Arduino soil moisture sensor tutorial which covers the working of soil moisture sensor module and how to use it with the Arduino,

We need a small pump to irrigate the plant, but in the case of a garden, we need to drive a larger pump that can provide a higher volume of water depending on the size of your garden which can't be directly powered by an Arduino. So in case you need to operate a larger pump, a driver is necessary to provide enough current for the pump, to show that I am using a 5v relay.
7.Advantages and Disadvantages 
  Advantages of Automatic Irrigation System:

Efficient water usage – Automatic irrigation systems use sensors and technology to accurately measure and distribute water, reducing water waste and ensuring plants receive the right amount of water they need.
Convenience and time-saving – Automatic irrigation systems can be scheduled to run at specific times, saving farmers the time and effort of manually watering their crops.
Customizable irrigation – Automatic irrigation systems can be customized to suit different crops, soil types, and weather conditions, providing the flexibility needed for optimal growth.
Monitoring and control – Automatic irrigation systems allow farmers to remotely monitor and control their irrigation systems, making it easy to make adjustments as needed.
Cost-effective – In the long run, automatic irrigation systems can be more cost-effective as it reduces water wastage and labor costs, thus increasing the yield and profitability of the farm.
Disadvantages of Automatic Irrigation System

High initial cost – Automatic irrigation systems can be expensive to install, making it difficult for some farmers to afford.
Dependence on technology – Automatic irrigation systems rely on technology, which can malfunction or break down, interrupting the irrigation process.
Requires maintenance – Automatic irrigation systems require regular maintenance and repairs to ensure they are functioning properly.
Limited flexibility – Automatic irrigation systems may not be suitable for certain crops or soil types, limiting the flexibility of irrigation.
Lack of human touch – Automatic irrigation systems remove the human touch in irrigation, which may result in less efficient watering and less attention to the specific needs of the plants
8.Application:

With numerous benefits of Arduino in Agriculture, it can be installed and used in various sectors of agriculture with quite successful results in the end. Some of those applications are described below.

8.1  Moisture and other Sensors:
Sensors installed in agriculture bring quite impressive results. It helps the farmer to analyze the condition of soil, water, crop, and weather. Its aim is to control production efficiently without wasting natural resources.

8.2  Demand For Irrigation:
Water is no doubt an inseparable aspect of agricultural fields. But if an excessive amount is given to the field, it might ruin the plantation process. That is why it is essential to know where water needs more and where it does not. In such a situation, IoT devices come handy, which analyze the water in the soil and trigger the irrigation system automatically where necessary.

8.3  Soil Correction:
The IoT devices used for controlling irrigation processes are also used for analyzing the condition of the soil, including quality, soil nutrients, and PH levels. This helps the farmers to identify which part of the soil needs correction, like cathe or fertilizer. 

8.4  Crop Diagnosis:
Using drones in crops provides various solutions and benefits since drones have Internet, sensors, and GPS, which helps them to analyze the conditions more precisely and helps you make decisions at a better level.

This ensures the diagnosis of the crop health without causing any laboring efforts as farmers don’t require to travel miles away for checking. Thus drones aid in saving resources and time.


8.5  Smart Greenhouse:
The state of humidity, temperature, and luminosity can easily be controlled and managed in greenhouses. Generally, this management can be handled manually through sparse, covers, and other means. 

However, IoT devices help you in connecting or unify all the greenhouses in one system. Thus making the situation more controllable and less complicated. 



9.  ARDUINO CODE:

//Tech Trends Shameer
//Smart Irrigation System

int sensor_pin= A0;
int output_value;

void setup(){
  pinMode(3, OUTPUT);
  Serial.begin(9600);
  Serial.println("Reading from the Moisture sensor…");
  delay(2000);
}

void loop()
{
  output_value= analogRead (sensor_pin);
  output_value= map (output_value,550,10,0,100);
  Serial.print("Moisture:");
  Serial.print(output_value);
  Serial.println("%");

  if (output_value<0)
  {
    delay(1000);
    digitalWrite(3, HIGH);
  }

  else
  {
    delay(1000);
    digitalWrite (3,LOW);  
  }

  delay (1000);
}
