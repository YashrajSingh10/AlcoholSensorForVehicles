# AlcoholSensorForVehicles
Project Overview
This project aims to enhance road safety by integrating an alcohol detection and alert mechanism into a vehicle’s ignition system. An Arduino Nano, combined with a MQ-3 alcohol sensor and a DHT11 humidity sensor (used for demonstration), monitors the driver's breath for alcohol content and provides real-time alerts using LEDs and a buzzer.

Objective
Develop a low-cost, microcontroller-based alcohol detection system that:

Identifies if the driver's blood alcohol level (BAL) exceeds the safe limit (~0.03% W/V).

Provides a visual and auditory alert mechanism.

Ensures only sober drivers can operate the vehicle.

Hardware Components
Arduino Nano (controller)

MQ-3 Alcohol Sensor (measures alcohol concentration in breath)

DHT11 Humidity Sensor (used for demonstration)

LED Indicators:

Safe to Drive: Glows when BAL < 0.03%

Not Safe to Drive: Glows when BAL ≥ 0.03%

Blow Here: Glows when the sensor needs to be activated

Buzzer (audible alert when over limit)

Resistors and Circuitry for signal conditioning

Features
Real-time detection of alcohol levels using the MQ-3 sensor.

Visual alerts via LEDs:

Green LED: Safe state (BAL < 0.03%).

Red LED: Not safe (BAL ≥ 0.03%), triggers the buzzer.

Yellow LED: Prompt to blow into the sensor.

Humidity data from DHT11 for demonstration and environmental context.

Working Principle
The person blows air towards the MQ-3 sensor.

The sensor measures the alcohol vapor and sends an analog signal to the Arduino Nano.

The microcontroller:

Determines if the BAL is above the threshold (0.03% W/V).

Activates the relevant LEDs:

Red LED + Buzzer for alcohol detected.

Green LED for safe levels.

Yellow LED for prompting breath input.

The DHT11 sensor captures humidity data (for demonstration), providing an additional environmental metric.

Outcome
The project demonstrates how a cost-effective alcohol detection system can be implemented to:

Prevent drunk driving incidents.

Enhance safety measures in vehicles.

Integrate seamlessly with existing automotive electronics.
