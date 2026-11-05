# Digital Speedometer for Bike / Car

## Project Overview

The Digital Speedometer is a web-based software prototype developed to demonstrate the working principle of a digital vehicle speedometer.

The system calculates vehicle speed using wheel RPM (Revolutions Per Minute) and wheel diameter. The RPM is simulated using control buttons, and the corresponding speed is displayed digitally in kilometres per hour (km/h).

It also includes START, STOP, RESET controls and a trip distance display.

## Objectives

- To develop a digital speedometer using Python Flask.
- To calculate vehicle speed using wheel RPM and diameter.
- To display speed in km/h.
- To simulate different RPM values using buttons.
- To demonstrate the basic principle of digital speed measurement.

## Technologies Used

- Python
- Flask
- HTML
- CSS
- JavaScript

## Key Features

- Digital speed display.
- RPM adjustment using buttons.
- Real-time speed calculation.
- START and STOP controls.
- RESET functionality.
- Trip distance monitoring.
- Simple and user-friendly interface.

## Working Principle

The system calculates vehicle speed using wheel RPM and wheel circumference.

**Formula:**

Speed (km/h) = (RPM × π × D × 60) / 1000

Where:
- RPM = Wheel revolutions per minute
- D = Wheel diameter in metres
- π = 3.14159

The prototype uses a wheel diameter of 0.66 m.

## Future Scope

- Integration of a Hall-effect sensor for actual RPM measurement.
- Microcontroller-based hardware implementation.
- LCD or OLED display integration.
- GPS-based speed measurement.
- Speed warning alerts.
- Mobile application development.

## Conclusion

The Digital Speedometer demonstrates the basic concept of digital speed measurement through a software-based prototype. It can be further developed into a real-time hardware speedometer by replacing simulated RPM input with actual sensor measurements.

## Project Type

Academic Software Simulation Project.

**Note:** This is currently a software prototype. It does not use a physical wheel sensor or directly measure the speed of a real vehicle.
