# Air Quality Classification System using Random Forest Algorithm using IoT based MQ7 and MQ13 Sensor
This project aims to create a system that can detect air quality index using MQ-7 and MQ-135 sensors with Random Forest algorithm to classify the results into three types of classes "Good", "Bad", or "Toxic" that can be accessed on a PC monitor in real time.

## Tools
- Arduino Nano
- MQ-7 Sensor
- MQ-135 Sensor
- ESP 32
- Bread Board
- Jumper
- Figma
- Arduino IDE

## Goals  
The goal of this project is to develop an IoT-based air quality classification system that utilizes MQ-7 and MQ-135 sensors to monitor air quality in real time. By implementing the Random Forest algorithm, the system classifies air quality into three categories: “Good,” “Bad,” or “Toxic.” This project aims to provide accurate and accessible air quality data through a PC interface, supporting environmental monitoring and health awareness.

## Step 1:  Requirement Analysis
- Define system requirements, including hardware (MQ-7 and MQ-135 sensors, microcontroller) and software (Random Forest algorithm implementation, real-time data visualization).
- Identify target environments and the purpose of air quality monitoring.

## Step 2: Hardware Selection and Setup
- Select the MQ-7 (carbon monoxide detection) and MQ-135 (air quality and hazardous gas detection) sensors.
- Choose a microcontroller to process sensor data and transmit it for analysis.
  
![Screenshot 2024-12-16 094303](https://github.com/user-attachments/assets/70766c69-8e95-4772-9aef-9b7bb52bf769)

## Step 3: Data Collection
- Gather real-time data from the sensors in various environments with different air quality levels.
- Store the collected data for preprocessing and model training purposes.

## Step 4: Data Preprocessing
- Clean the data by removing noise and handling missing values.
- Normalize the sensor outputs for consistent input to the classification algorithm.
- Label the data into predefined categories: “Good,” “Bad,” and “Toxic,” based on air quality standards.

## Step 5: Algorithm Implementation
- Implement the Random Forest algorithm to classify air quality based on the sensor data.
- Train the algorithm using the preprocessed dataset to achieve optimal accuracy.
- Validate the model using a test dataset and fine-tune hyperparameters if necessary.

## Step 6: System Integration
- Write a program to integrate the sensor hardware and the classification algorithm using the microcontroller.
- Enable real-time data transmission and processing to classify air quality instantly.
- Develop a simple interface for displaying classifications on a PC monitor.
  
![Desktop - 2](https://github.com/user-attachments/assets/dce7077b-f4f6-4624-a0d9-11707e12cc52)

## Step 7: Testing and Validation
- Test the system in different real-world environments to evaluate its performance under varying air quality conditions.
- Verify the accuracy and reliability of the classification results.
![image](https://github.com/user-attachments/assets/96bae0ed-2be4-4884-bf16-8793d418d4d1)
