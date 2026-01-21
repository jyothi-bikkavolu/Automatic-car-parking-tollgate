# Automatic-car-parking-tollgate
The Automatic Car Parking Toll Gate is an Arduino-based system designed to automate vehicle entry and exit in parking areas. It eliminates manual intervention by detecting vehicles, controlling a gate using a servo motor, and managing parking access efficiently.
🎯 Objectives

Detect vehicle entry and exit automatically

Control gate opening and closing using a servo motor

Reduce manual work in parking management

Provide a scalable base for real-time parking systems

🛠️ Components Required

Arduino UNO

Ultrasonic Sensor

Servo Motor

Jumper Wires

Breadboard

Cardboard / Gate Model

Power Supply / USB Cable

🔍 Sensors Used

Ultrasonic Sensor – Detects vehicle presence by measuring distance

(Optional for future enhancement)

IR Sensors – Vehicle counting

RFID Module – Automated toll collection

⚙️ Working Principle

The ultrasonic sensor continuously measures distance.

When a vehicle comes within a defined range:

The Arduino triggers the servo motor.

The gate opens to 90°.

After a short delay:

The gate automatically closes back to 0°.

The process repeats for every vehicle detected.

🧠 Programming Logic

Read distance values from the ultrasonic sensor

Compare distance with threshold value

Rotate servo motor accordingly

Add delays to allow smooth vehicle movement

🔌 Circuit Connections

Ultrasonic Sensor:

Trig → Arduino Digital Pin

Echo → Arduino Digital Pin

Servo Motor:

Signal → Arduino PWM Pin

VCC → 5V

GND → GND

⚠️ Ensure all grounds are common.

🧪 Testing Procedure

Assemble hardware components properly

Upload Arduino code (.ino file)

Place an object in front of the ultrasonic sensor

Verify:

Gate opens when vehicle is detected

Gate closes after delay

Adjust distance threshold and delay if required

📁 Project Files

1carparkinggate.ino – Arduino source code

Automatic Car Parking Toll Gate.pptx – Project presentation

README.md – Project documentation

🚀 Future Enhancements

Add LCD display for parking status

Integrate RFID for automated fee collection

Use IoT for real-time parking monitoring

Store parking data in cloud or database

📚 Applications

Shopping mall parking systems

Office and apartment parking areas

Smart city parking solutions

🧑‍💻 Team Details

Presented by: Batch 1

23A31A04P8

23A31A04P9

23A31A04Q0

23A31A04Q1

23A31A04Q2

23A31A04Q4

📜 Conclusion

This project demonstrates how Arduino can be used to build an efficient automatic parking toll gate system. With further enhancements, it can be scaled into a full-fledged smart parking solution.
