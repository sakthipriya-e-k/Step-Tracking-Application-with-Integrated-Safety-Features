# Step-Tracking-Application-with-Integrated-Safety-Features
Smart Step Tracker with Emergency Alert System - MIT App Inventor Project

**#Project Overview**
Step Tracking application with integated safety features is an advanced mobile application developed using MIT App Inventor. The application focuses on user safety and daily activity monitoring by combining:
            Step count analysis using mobile sensors
            Daily target tracking
            Emergency live location sharing via SMS

The app is developed with real world usability in mind, making it suitable for personal safety, fitness monitoring and emergency response scenarios.

**#Problem Statement**
Many existing fitness applications focus only on step counting and ignore user safety during emergencies. In real-life situations, users may require a quick and reliable way to share their live location with trusted contacts.

My project addresses this problem by integrating activity tracking with an emergency alert system ensuring both wellness monitoring and personal safety.

**#Key features**
        Secure Login and Signup system
        Persistent user data storage using TinyDB
        Daily step target setting
        Real-time step counting using Pedometer sensor
        Remaining steps calculation
        Emergency button for instant location sharing
        Manual share option to send location to any contact
        Automatic Google Maps location link generation
        Data persistence even after app restarts

# MIT App Inventor Components Used

### Maps
- Google Maps link generated using live GPS latitude and longitude

### Sensors
- **Pedometer**: Used for real-time step counting
- **LocationSensor**: Used to fetch live user location

### Social
- **Texting Component**: Used to send emergency SMS alerts

### Storage
- **TinyDB**:
  - Stores user credentials
  - Stores emergency contact number
  - Stores step targets and step count progress

### Connectivity
- GPS-based location tracking
- SMS-based communication

### Screens Included:
- Login Screen
- Signup Screen
- Dashboard Screen

## Backend Logic & Data Handling

### Authentication
- Username used as a unique key
- Password validation using TinyDB

### Data Storage
- Emergency contact stored with tag format:

### Step Tracking Logic
- Steps incremented using `Pedometer.WalkStep`
- Remaining steps calculated dynamically
- Target achievement handled with conditional logic

### Emergency Logic
- Automatic emergency mode:
        - Sends SMS directly to stored emergency contact
- Manual share mode:
        - Opens messaging app for user-selected contact
        - Live GPS location embedded in Google Maps link

## Tools & Technologies Used
- MIT App Inventor
- Android Sensors
- Google Maps URL API
- TinyDB (Local Storage)
- SMS Communication

## Application Screenshots
Screenshots of the application are available in the `screenshots/` folder:

## How to Download and Access the Application

This project is developed using MIT App Inventor and is provided as a `.aia` project file.

### Steps to Access the Application:

1. Download the `.aia` file from the GitHub repository:

2. Open your browser and go to:
https://ai2.appinventor.mit.edu

3. Sign in using your Google account.

4. Click on Projects → Import project (.aia) from my computer.

5. Select the downloaded `Step Tracking application with Integrated Safety Features.aia` file.

6. The project will be loaded into MIT App Inventor and is ready to run or modify.

### To Run the App on Mobile:
- Install MIT AI2 Companion app from Google Play Store.
- Connect your mobile phone and laptop to the same Wi-Fi network.
- In MIT App Inventor, click Connect → AI Companion.
- Scan the QR code using the mobile app.

## How to Use the Application

### 1️⃣ User Signup
- Open the application.
- Click **New User? Sign Up**.
- Enter:
  - Username
  - Password
  - Emergency contact number
- Click **Sign Up**.
- A success message will be shown and the app will return to the login screen.

## Login Page
![Login_Page](https://github.com/user-attachments/assets/e156a4ab-d98b-4c01-8282-53dd250a1a79)

## SignUp Page
![Sign_Up_Page](https://github.com/user-attachments/assets/1bbe5a9b-3869-41fb-9dc5-ee3eb4d131a2)

## SignUp Page Example
![Sign_Up_Example](https://github.com/user-attachments/assets/11ac2218-8505-42a3-9233-c0bebf1da6cb)

## SignUp Success
![Sign_Up_Success](https://github.com/user-attachments/assets/eac8f6a1-0460-492e-8780-4f09bf7e7284)

### 2️⃣ User Login
- Enter the registered username and password.
- Click **Login**.
- Upon successful authentication, the user is redirected to the Dashboard screen.

## LogIn Page
![Login_Page](https://github.com/user-attachments/assets/51fc83b3-f539-4806-bdac-1941c214c4a5)

## LogIn Page Example
![Login_Page_Example](https://github.com/user-attachments/assets/27c7926b-f511-41cd-ad3e-6d0665f9f0a5)

## Dashboard Screen
![Dashboard_Screen](https://github.com/user-attachments/assets/cfcbb75d-29c3-4b2a-9827-7bdd222a69c1)

### 3️⃣ Setting Daily Step Target
- On the Dashboard screen:
  - Enter the desired daily step target.
  - Click **Set Target**.
- The target and remaining steps are displayed.
- Target data is saved automatically.

## Creating Target Step
![Entering_Target_Step](https://github.com/user-attachments/assets/4e602616-ae99-4d57-bc83-925d694932f6)

## Target Step Created Successful
![Target_Step_Creation_Successful](https://github.com/user-attachments/assets/f78adf6a-d487-4aca-a9af-8e06ccde1bb8)

### 4️⃣ Step Counting
- Keep the phone with you while walking.
- The app uses the mobile **Pedometer sensor** to count steps.
- Steps taken and remaining steps update automatically.
- Step progress is saved even if the app is closed.

## Step Counting Begins
![Step_Counting_Begins](https://github.com/user-attachments/assets/86c16329-c4a5-478b-9595-132680494373)

## Step Counting 1
![Step_Counting_1](https://github.com/user-attachments/assets/15f8808b-74aa-4b1e-af83-d1b4aabedb48)

## Step Counting 2
![Step_Counting_2](https://github.com/user-attachments/assets/0495e575-7065-4491-af67-c95529680432)

## Step Counting 3
![Step_Counting_3](https://github.com/user-attachments/assets/b4317a24-ccbd-45b9-b5db-58d5e8c6d606)

## Step Counting 4
![Step_Counting_4](https://github.com/user-attachments/assets/55bdd8e9-9868-4b56-8746-13f6df124c27)

## Target Step Achieved Success
![Target_Step_Achieved_Success](https://github.com/user-attachments/assets/0e7bda3f-1fd2-4bb5-a963-cc438d8d5841)

### 5️⃣ Emergency Location Sharing (Auto Mode)
- Press the **Emergency** button.
- The app fetches live GPS location.
- A Google Maps link is generated.
- Emergency SMS is sent **directly** to the registered emergency contact without opening the messaging app.

## Dashboard Screen
![Dashboard_Screen](https://github.com/user-attachments/assets/989e8863-52d8-4385-a25a-4a30e459e579)

## Emergency button is clicked
![Once_Emergency_Option_Is_Clicked](https://github.com/user-attachments/assets/49fa9d01-e507-4547-bddd-571faee6a676)

## Location Send
![Location_Send](https://github.com/user-attachments/assets/ef6141cc-b4ed-4450-8e22-5947cf5ea35e)

## Location In Map
![Location_In_Map](https://github.com/user-attachments/assets/2c2c738c-84a7-49b0-8c76-5bf751b6e06e)

### 6️⃣ Manual Location Sharing
- Press the **Manual Share** button.
- The messaging app opens.
- User can select **any contact**.
- Live location link is shared manually.

## Dashboard Screen
![Dashboard_Screen](https://github.com/user-attachments/assets/18d09267-483d-4a4a-af81-b6a4741726b9)

## Manual Option Click
![Manual_Option_Click](https://github.com/user-attachments/assets/4af757c5-4aa8-4418-9aab-31bada3feb94)

## Share Location To Selected Number
![Manual_Option_Click](https://github.com/user-attachments/assets/a3250265-a5cb-4b83-a3fa-118c42420b4a)

## Manual Location Share In Map
![Manual_Location_Share_In_Map](https://github.com/user-attachments/assets/d957dbeb-6ffb-4ac0-87ef-c61f78e27230)

### 7️⃣ Data Persistence
- User data such as:
  - Step count
  - Target steps
  - Emergency contact
is stored using TinyDB and retained across sessions.

## Conclusion
Step Tracking Application with Integrated Safety Features is a practical, real-world mobile application that demonstrates advanced use of MIT App Inventor components.  
It successfully integrates sensors, storage, connectivity, and social components into a single cohesive solution.

## Developed By
**Sakthi Priya E K**  
