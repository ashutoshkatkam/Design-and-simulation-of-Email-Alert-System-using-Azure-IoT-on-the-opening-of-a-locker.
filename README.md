# Design-and-simulation-of-Email-Alert-System-using-Azure-IoT-on-the-opening-of-a-locker

Project Title: 
Design and simulation of Email Alert System using Azure IoT on the opening of a locker.

Problem Statement/Opportunity*:
Lockers in the house need to be monitored carefully to safeguard our precious items. So here in this era of connected devices and smart things around us it is easy to remotely monitor the locker. We need to create an alert system that indicates us when our locker is opened and also gives us the complete stats of the locker access.


Project Description*:
In this project, I created a custom device template in the Azure IoT Central having a parameter named "open" a telemetry Boolean variable that stores the status of locker opening. I have used the simulation service of Azure IoT for sending simulated sensor values to the device.  Then added a rule to alert the owner by email whenever the locker is opened. The status of the locker door is displayed on the device page indicating "True" for locker opening and "False" for closed locker. The rule is set to send an email alert on parameter open == "True". 
Conclusion:
I have successfully created and simulated a locker alert system using Azure IoT central service.
Future Scope:
This project in the future can be attached with several other azure cognitive services to capture the image of the person opening the locker and alert only if the person is not authorized.
