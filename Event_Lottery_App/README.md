# Event Lottery System Application

*This project was developed collaboratively with 5 other students as part of a course.*

## Description  
The **Event Lottery System Application** is a simple, attractive, and accessible Android application designed to provide a fair and convenient way for individuals to sign up for community events. The system utilizes a lottery mechanism to allocate event spots, ensuring inclusivity and removing the pressure of first-come, first-served systems. It is built to be flexible and extendable, accommodating future enhancements or migrations.

Insert appropriate Google API Key in:
1. trojan0_horse/Trojan0Project/app/google-services.json
2. trojan0_horse/Trojan0Project/app/src/main/AndroidManifest.xml

---

![CMPUT301F24trojan0_storyboard-Page-1 drawio_11zon](https://github.com/user-attachments/assets/4493bc24-a5fb-4def-be12-ad94507e688a)


## Features  

### Core Features  
- **Pooling System**: Organizers can randomly select participants from a waiting list.  
- **QR Code Scanning**: Users can scan QR codes to view event details and join waiting lists.  
- **Firebase Integration**: Real-time event management and data storage.  
- **Multi-User Roles**: Supports roles for entrants, organizers, and administrators, each with unique privileges.  
- **Event Poster Upload**: Organizers can upload images to promote events.  

### Optional Features  
- **Geolocation Verification**: Allows optional verification of a user's location when joining a waiting list.  

---

## Scenarios  

### Entrant Perspective  
- **Swimming Lessons**: Join a waiting list for swimming lessons and receive notifications on selection status.  
- **Piano Lessons**: Register for events via QR codes and await selection from the lottery pool.  

### Organizer Perspective  
- **Event Creation**: Create an event, set registration parameters, and generate a QR code for promotions.  
- **Lottery Management**: Monitor waiting lists, select participants, and notify them of their status.  

---

## User Stories  

### Entrants  
- **Join/Leave Waiting List**: Easily join or leave event waiting lists.  
- **Manage Profile**: Update personal details and upload/remove profile pictures.  
- **Receive Notifications**: Get notified of lottery outcomes and event updates.  

![CMPUT301F24trojan0_UI_explained-Page-2 drawio](https://github.com/user-attachments/assets/4c62af4a-685f-4d6e-bf6f-585f2f22a7d7)


### Organizers  
- **Create Events**: Define event details, manage entrants, and handle lotteries.  
- **Notifications**: Notify entrants of their selection status or event changes.  

![CMPUT301F24trojan0_UI_explained-Page-3 drawio](https://github.com/user-attachments/assets/02d346ce-91c7-4c91-8f4e-4a036b9b184c)


### Administrators  
- **Content Management**: Remove events, profiles, and images that violate app policies.  
- **Event Monitoring**: Browse and manage events, profiles, and images in the app.  

![CMPUT301F24trojan0_UI_explained-Page-1 drawio (1)](https://github.com/user-attachments/assets/ed07c075-4e58-40b7-b586-17f1750ba818)


---

## Technologies Used  
- **Android Studio**: Development platform.  
- **Firebase**: Backend for database and real-time notifications.  

---

## Future Enhancements  
The application is designed with flexibility for future upgrades, including enhanced accessibility features and extended role-based functionalities.  

---

## Emulator Testing
To run UI tests, we have implemented a Mock Firebase via Firebase Emulator Suite. 
### NOTE: You will need openJDK.

```
EmulatorFiles % java -version                                             
openjdk version "21.0.2" 2024-01-16 LTS
OpenJDK Runtime Environment Temurin-21.0.2+13 (build 21.0.2+13-LTS)
OpenJDK 64-Bit Server VM Temurin-21.0.2+13 (build 21.0.2+13-LTS, mixed mode)
```

### Test Commands

```
[Assuming the firebase tools are not currently within the testing machine]
curl -sL https://firebase.tools | bash     
```
```
firebase emulators:start --project cmput301f24trojan0horse
```



