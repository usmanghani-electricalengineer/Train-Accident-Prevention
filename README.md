# Train Accident Prevention System

A **microcontroller-based safety system** designed to prevent railway accidents by detecting approaching trains using **ultrasonic sensors**, and alerting nearby pedestrians and drivers with **LED and buzzer warnings**.

## Objective
Enhance **railway safety** by providing an early warning mechanism to prevent train-related accidents at unmanned crossings.

## System Overview
This system uses an **Arduino UNO** microcontroller integrated with **ultrasonic sensors**, **LED indicators**, and a **buzzer** to detect an approaching train and trigger visual and audible alerts.

## Working Principle
1. **Train Detection:** Ultrasonic sensors emit sound waves and detect echoes from approaching trains.  
2. **Distance Measurement:** The Arduino calculates the train’s distance using time-of-flight data.  
3. **Threshold Check:** When the train is within a predefined danger zone (e.g., 50 meters), a warning is activated.  
4. **Warning Activation:**  
   - LEDs light up to provide a **visual alert**.  
   - Buzzer sounds for an **audible alert**.  
5. **Continuous Monitoring:** The system stays active as long as the train remains in range, ensuring real-time safety alerts.

## Components Used
| Component | Description |
|------------|-------------|
| Arduino UNO | Main microcontroller |
| Ultrasonic Sensor (HC-SR04) | Measures train distance |
| LEDs | Visual warning |
| Buzzer | Audible alert |
| Resistors | Current limiting for LEDs |
| Power Supply (5V) | Powers circuit |
| Wires | Circuit connections |

## Testing & Results
- When an object approaches within the danger threshold, **LEDs and buzzer activate**.  
- When it moves away, both **automatically turn off**.  
- The system successfully simulates **real-time train detection and alerts**.  

## Conclusion
A **low-cost, reliable, and effective** safety solution that can be implemented at unmanned railway crossings to **reduce collisions and save lives**.




