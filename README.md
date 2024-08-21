# Soldier-Heathcare-and-Position-tracking-system
In modern military operations, the health and safety of soldiers on the battlefield are of paramount importance. Monitoring vital signs and tracking the location of soldiers in real-time provides critical data that can assist in ensuring their well-being and effective mission execution. This project aims to develop a compact and reliable Soldier Health Monitoring and Location Tracking System that continuously records and transmits vital health information and GPS coordinates of soldiers to the squadron leader's node.

The system integrates a body sensor network (BSN) comprising a temperature sensor (LM35) and a pulse sensor (RC-A-4015) to monitor the soldier’s body temperature and pulse rate, respectively. The GPS module (NEO-6M) is employed to track the precise location of the soldier. The data from these sensors is processed by an Arduino UNO microcontroller, which then transmits the information wirelessly to the squadron leader's node using an RF transceiver module (HC-12).

The squadron leader's node, located within a short range of the soldier’s node, receives and displays the transmitted data, allowing for real-time monitoring of the soldier's health status and location. The implementation of this system provides a crucial tool for maintaining situational awareness on the battlefield, ensuring that the squadron leader can make informed decisions based on the health and location data of their soldiers.

This project is a scaled-down version of a larger system designed to ensure the safety and efficiency of military personnel in the field. The simplicity of this system, combined with its effectiveness, makes it a viable solution for real-time monitoring in various field conditions.

1.	Components Required : Soldiers Unit
•	Arduino UNO R3 SMD x 1
•	Temperature Sensor (LM35) x 1
•	Pulse Sensor (RC-A-4015) x 1
•	GPS Module (NEO-6M) x 1
•	HC-12 RF Transceiver Module x 1
•	Breadboard x 1
•	Jumper Wires (Male-to-Male) x 20+
•	9V Battery and Battery Clip x 1
 2.  Components: Squadron’s Unit
•	Arduino UNO R3 SMD x 1
•	HC-12 RF Transceiver Module x 1
