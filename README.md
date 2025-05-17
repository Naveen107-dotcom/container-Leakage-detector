Project Title:
Automated Container Leakage Detector System

🎯 Project Objective:
To design and implement an automated system for detecting and rejecting leaky plastic containers on a conveyor line in a packaging process, aiming to improve product quality and reduce manual inspection errors.

🏭 Industry Motivation:
This project was initiated in response to a real-world challenge faced by Polypak Secco (Pvt) Ltd, a company specializing in the manufacturing of plastic packaging products. The existing manual inspection process for detecting leakage in plastic containers was inefficient and inconsistent. Automation was identified as the solution to improve reliability, speed, and consistency in quality control.

⚙️ System Overview:
The Automated Container Leakage Detector System is an electromechanical setup that detects containers with leakage (during or after filling) and automatically rejects them from the conveyor path using air-release actuators. It is controlled using a Schneider PLC programmed in ladder logic.

🧩 Key Components:
1. Sensors:
Photoelectric Sensors (S1):
Used for container detection, position tracking, and leakage evaluation points.

2. Actuators:
A1–A5:
Mechanisms that control air nozzles and other reject mechanisms.

P1 (Air Release Valves):
Used to blow out or reject leaky containers detected on the conveyor.

3. PLC (Programmable Logic Controller):
Brand: Schneider Electric (Zelio)

Function: Receives inputs from sensors and executes the logic to control actuators based on container status.

4. Conveyor Motor:
Drives the movement of containers along the detection and rejection path.

5. Control Panel:
Includes Start/Stop/selector buttons for operational control.

6. Custom Fabricated Sealing Head:
Mechanically fabricated to simulate container sealing under pressure, which helps detect even small leaks.

🧠 Working Principle:
Start Sequence:

Operator presses the start button. Conveyor begins moving containers.

Detection Phase:

As each container passes the photoelectric sensors, the system verifies its presence and tracks its position.

Leak Test:

The container is sealed momentarily using a custom sealing head.

If pressure drops or leak detection criteria are triggered, the PLC marks the container as defective.

Rejection Mechanism:

When the defective container reaches the rejection point, the air-release actuator (R1) is activated.

The leaky container is blown off the conveyor into a rejection bin.

Restart/Stop Functions:

The system can be restarted or stopped anytime for maintenance or troubleshooting using the control panel.

👨‍🔧 My Contributions & Responsibilities:

🧩 PLC Ladder Programming:

Developed a complete control algorithm using Schneider PLC to automate the process, synchronize sensor data, and trigger rejection mechanisms.

🔌 Electrical Wiring and System Integration:

Renewed and reorganized the wiring for all components, including the PLC, sensors, motor, and actuators, ensuring safe and efficient operation.

🛠️ Sealing Head Fabrication:

Designed and fabricated a mechanical sealing head to simulate pressure sealing, enabling more accurate leakage detection.

🧪 Testing and Debugging:

Conducted extensive testing under various scenarios to fine-tune system accuracy, actuator timing, and error-handling responses.

🧾 Learning Outcomes:
Gained hands-on experience with Schneider PLC programming.

Learned practical skills in sensor-actuator integration and ladder logic design.

Improved knowledge of industrial automation systems, pneumatic actuators, and mechanical design for detection.

Developed troubleshooting skills and the ability to collaborate with industry professionals.

🙏 Acknowledgment:
Special thanks to Polypak Secco (Pvt) Ltd for inspiring this project and providing valuable industrial insight.
Heartfelt appreciation to Mr. Lasantha Kurukulrachchi, Mr. Nalin Dhammika, and Mr. Shakthi Indrasekara for their guidance, technical support, and mentorship throughout the project
