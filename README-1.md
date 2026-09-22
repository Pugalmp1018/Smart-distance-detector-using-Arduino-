# **Smart Distance Detector Using Arduino**

##  **Project Description**

The **Smart Distance Detector Using Arduino** is an electronic project designed to measure the distance between an object and a sensor. It uses an **Arduino board** and an **HC-SR04 ultrasonic sensor** to detect objects and calculate their distance.

## **Objective**

* To measure the distance of nearby objects.  
* To understand ultrasonic sensing technology.  
* To interface an HC-SR04 sensor with Arduino.  
* To display or indicate the detected distance.  
* To develop a simple and low-cost distance monitoring system

##  **Working Principle**

The **HC-SR04 ultrasonic sensor** sends ultrasonic sound waves toward an object. When the waves hit the object, they are reflected back to the sensor.

The Arduino measures the time taken for the ultrasonic waves to return and calculates the approximate distance of the object.

**Basic working flow:**

**Object → Ultrasonic Sensor → Arduino → Distance Detection → Output/Alert**

## **🔌 Main Components and Functions**

| Component | Function |
| ----- | ----- |
| Arduino Uno | Controls the complete system |
| HC-SR04 | Measures distance using ultrasonic waves |
| LED | Provides visual indication |
| Buzzer | Provides sound alert when required |
| Breadboard | Used for circuit connections |
| Jumper Wires | Connects the components |
| Resistor | Provides required current limitation  **PROGRAM int trig \= 9; int echo \= 10; void setup() {   Serial.begin(9600);   pinMode(trig, OUTPUT);   pinMode(echo, INPUT); } void loop() {   digitalWrite(trig, HIGH);   delayMicroseconds(10);   digitalWrite(trig, LOW);   long result \= pulseIn(echo, HIGH);   Serial.println(result);   delay(1000); }**  |

##  **Conclusion**

The **Smart Distance Detector Using Arduino** is a simple and useful embedded-system project that demonstrates how ultrasonic sensors can be used for contactless distance measurement. It provides a basic platform for developing more advanced **robotics, automation, IoT, and smart sensing applications**.

### **RESULT**
![result](https://github.com/Pugalmp1018/Smart-distance-detector-using-Arduino-/upload/main)
