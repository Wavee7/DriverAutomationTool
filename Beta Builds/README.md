![MSEndpointMgr Driver Auatomation Tool - BETA Channel](https://msendpointmgr.com/wp-content/uploads/DAT/DAT1.jpg)

# Driver Automation Tool 8 BETA

Welcome to the BETA channel for the Driver Automation Tool.

The binaries contained within this channel will updated with additional functions, and should be used for testing. Feedback should be provided in the GitHub PR's and please make note of the in-work items before posting comments, as the item you are looking for could be in development.

## HP Support Added - 14/03/2024
✅ Current OEM Support: Acer, Dell, HP

✅ Package Type Support: Drivers

✅ Supported Operating Systems: Windows 10, Windows 11

✅ Supported Architectures : x64, x86

## Initial BETA Release - 16/02/2024
The new Driver Automation Tool has a redesigned UI which is designed to be easier to use and allow for more expansion. The initial release is for Configuration Manager ONLY, Intune support will follow in the upcoming BETA release updates. 

### Current functionality
✅ Current OEM Support: Acer, Dell

✅ Package Type Support: Drivers

✅ Supported Operating Systems: Windows 10, Windows 11

✅ Supported Architectures : x64, x86

### In Progress Functionality
🚧 Additional OEM Support - HP/Lenovo/Microsoft (Expected by 20/02/2025)

🚧 Add Microsoft support 

🚧 Previous version removal 

🚧 Intune Support

🚧 Deployment Rings

🚧 New UI for driver additions to existing packages

🚧 Custom driver package UI


<br>

### New UI
Elemeents have been moved to an application style layout, with previously contained tab elements migrated. The UI now supported both "Light" and "Dark"modes;


<img src="https://github.com/user-attachments/assets/dfd465c3-7ac3-4d0c-9b4a-be26674b7ccd" height="300" />


<br>Configuration Manager Environment:


<img src="https://github.com/user-attachments/assets/1ba85731-6a47-4b14-8942-16b3f5cd8365" height="300" />


<br>Configuration Manager Distribtion Point Configuration:


<img src="https://github.com/user-attachments/assets/c95bf097-ce65-4a70-9ead-eafcc518da80" height="300" />


<br>Configuration Manager Package Management:


<img src="https://github.com/user-attachments/assets/110b948e-1a77-40e5-8f32-ee1aacf2561d" height="300" />


<br>Configuration Manager Package Settings:


<img src="https://github.com/user-attachments/assets/709638f8-5e58-4d04-9908-62d1fcbeefe3" height="300" />


<br>Shared Configuration Settings:

<img src="https://github.com/user-attachments/assets/5f088d4a-3b7e-456d-9578-a9ef7e40b862" height="300" />


<br>

### Registry Storage
The Driver Automation Tool now uses the registry to store all of your configuration settings, and critical information about the package build process;

<img src="https://github.com/user-attachments/assets/b3977d45-1492-4636-bf1d-236a4160af8d" height="300" />


<br>Configuration can now be exported and imported from the UI, using registry exports;


<img src="https://github.com/user-attachments/assets/1ff53e1e-a648-475b-ba7e-ac4a5291656a" height="300" />


<br>

### Download Utility
To provide additional feedback and control downloads better, CURL is used by the new release. This is packaged within the MSI.

<img src="https://github.com/user-attachments/assets/dd487337-d489-45fd-9b54-a039e29e8fbf" height="300" />


<br>

### Fully Responsive UI

The Driver Automation Tool now uses background jobs to undertake the majority of actions, and this results in a fully responsive UI, something that I had taken as feedback from previous builds. With this includes the addition to lauch the log file (in CMTrace format) and abort the build process;

<img src="https://github.com/user-attachments/assets/6c31e337-159e-42fa-b689-ff2abb834079" height="300" />












