# SWENG837-Course-Project---IoT-Simplicity
Homeowners who buy IoT devices need a centralized system that can control these IoT devices, such as lighting, temperature, and security, in their home. This system should allow for multiple users to interact with it, be easy for users to interact with, be continuously available, and be able to utilize all functionality of the IoT devices.

# 1. Use Case Diagram
<img width="451" alt="image" src="https://github.com/user-attachments/assets/620ecd19-0159-4fb4-87e3-ca123151f2da" />
 
# 2. Domain Model
<img width="452" alt="image" src="https://github.com/user-attachments/assets/a63b38f0-62fd-4c69-992f-61bf8b952b2c" />

** See Class Diagram **
 
# 3. Class Diagram
<img width="432" alt="image" src="https://github.com/user-attachments/assets/d40e47ab-9760-443e-908a-aa7da89362bb" />

**Name: User**

User’s Attributes

·      ID #: Unique ID created by the system for each user

·      Username: Unique String created by user

·      Password: Unique protected password created by user

User’s Methods:

·      openApp(ID): Uses the user’s ID to open the app

·      login(ID, username, string): A user can login to the app by using their username and password. This either grabs an existing ID or creates a new ID for the user.

**Name: Device using App**

Device using App’s Attributes

·      Serial Number: The serial number of the device

·      MAC Address: The MAC Address of the device

·      List of IoT Devices: A list of IoT devices connected to the app

Device using App’s Methods:

·      displayIoTDevices(listOfIoTDevices): Shows available IoT Devices

**Name: Wi-Fi Router**

Wi-Fi Router’s Attributes

·      Wi-Fi Address: Wi-Fi address of the Wi-Fi router

·      Name: Name of the Wi-Fi router created by the provider and able to be adjusted by the user

·      Provider: Provider of the Wi-Fi router

·      Security Type: Security type for the password on the Wi-Fi Router

·      Password: Protected password of the Wi-Fi router

Wi-Fi Router’s Methods:

·      acceptWiFiLogin(password: password): Uses the password given to it to login a user

**Name: IoT Device**

IoT Device’s Attributes

·      ID #: Unique ID created by the system for each IoT device

·      Name: Name of the device created by the manufacturer and able to be adjusted by the user

·      Manufacturer: Name of the company who created the IoT device

·      Device Type: Type of IoT Device (e.g. Light, Thermostat, etc.)

·      Capabilities: List of functions that the device can do

IoT Device’s Methods:

·      doFunction(ID, capability): A user selects a capability of a device that they want the device to do. 
 
# 4. Sequence Diagrams 
## 4.1 connectSystemToWiFi
<img width="455" alt="image" src="https://github.com/user-attachments/assets/ab5bce1e-09d2-48a9-a82e-5ba2ca4b25c2" />

## 4.2 connectIoTDeviceToWiFi
<img width="469" alt="image" src="https://github.com/user-attachments/assets/c31ce420-129c-4dce-bfbc-2072bbca1cfa" />
 
## 4.3 interactWithIoTDevice
<img width="460" alt="image" src="https://github.com/user-attachments/assets/3bf4258d-d3de-4913-80ce-c79fe7f209ec" />
 
# 5 UML State Diagram: IoT Device 
<img width="414" alt="image" src="https://github.com/user-attachments/assets/745ffa72-61d5-46a4-a9d2-de9b6135530d" />

# 6 UML Activity Diagram (Swimlane Diagram) 
<img width="443" alt="image" src="https://github.com/user-attachments/assets/86f544df-fecc-4195-bfa8-f772924b0760" />

# 7 UML Component Diagram
<img width="458" alt="image" src="https://github.com/user-attachments/assets/2ba48258-2aa0-4ad2-9198-23fa22190b3b" />

# 8 Cloud Deployment Diagram 
<img width="421" alt="image" src="https://github.com/user-attachments/assets/7346e46f-7bdf-457f-8164-eab37a888f84" />
