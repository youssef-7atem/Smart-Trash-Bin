# Smart Trash Bin System

## Project Overview
The **Smart Trash Bin System** is an innovative project designed to modernize waste management in smart cities. This system uses **machine vision** to detect and categorize different types of waste, such as plastic, paper, and metal. The trash bin is equipped with **ultrasonic sensors** to detect motion, allowing it to open automatically when a user approaches. Additionally, the system includes a **GPS tracker** that sends notifications to a mobile app when the bin is full, enabling efficient waste collection and improving overall waste management.

## Key Features
- **Machine Vision for Waste Categorization**: Uses a camera and machine learning algorithms to detect and categorize waste with high accuracy.
- **Automatic Lid Opening**: Ultrasonic sensors detect motion and trigger a servo motor to open the bin lid automatically.
- **GPS Tracking**: A GPS module tracks the bin's location and sends real-time updates to a mobile app when the bin is full.
- **Mobile App Integration**: Notifies users and waste collection trucks about the bin's status and location, optimizing waste collection routes.
- **Real-Time Monitoring**: Provides real-time feedback on the bin's status, including waste level and location.

## Technologies Used
- **Machine Vision**: OpenCV, TensorFlow (for waste categorization)
- **Microcontroller**: Arduino or Raspberry Pi (for system control)
- **Sensors**: Ultrasonic sensors (for motion detection), GPS module (for location tracking)
- **Actuators**: Servo motor (for automatic lid opening)
- **Communication**: Wi-Fi/Bluetooth (for data transmission to the mobile app)
- **Mobile App**: Developed using Flutter or React Native (for real-time notifications)

## How It Works
1. **Waste Detection**: When a user approaches the bin, the ultrasonic sensor detects motion and triggers the camera to capture an image of the waste item.
2. **Waste Categorization**: The machine vision system processes the image and categorizes the waste (e.g., plastic, paper, metal) using a pre-trained machine learning model.
3. **Automatic Lid Opening**: Once the waste is categorized, the servo motor opens the bin lid automatically, allowing the user to dispose of the waste.
4. **Waste Level Monitoring**: The system continuously monitors the waste level inside the bin using sensors.
5. **GPS Tracking**: When the bin is full, the GPS module sends the bin's location to a mobile app, notifying waste collection trucks for timely pickup.

## Photos
Here are some visuals of the project:

1. **Project Overview**:
   ![image](https://github.com/user-attachments/assets/7b0d1e9a-0867-4aad-8fe5-8887e5c25906)
   *An overview of the Smart Trash Bin System, showing the bin, camera, and sensors.*

2. **Waste Categorization in Action**:
   ![image](https://github.com/user-attachments/assets/e9bb8ae3-20b8-4b28-8573-9d2b3a594ca5)
   *The system detecting a plastic bottle and displaying the result with high accuracy.*

3. **GPS and Ultrasonic Sensors**:
   ![image](https://github.com/user-attachments/assets/79be8652-94a2-4368-8e3c-3886b0ccc63e)
   *The GPS module and ultrasonic sensors used for location tracking and motion detection.*

## Applications
- **Smart Cities**: Ideal for improving waste management in urban areas.
- **Public Spaces**: Can be deployed in parks, malls, and airports for efficient waste disposal.
- **Recycling Centers**: Helps in automating waste categorization and sorting processes.





