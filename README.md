# Real-Time Risk Assessment in Surveillance Footage

## Project Overview
This project demonstrates the application of advanced computer vision and machine learning techniques to analyze surveillance footage for real-time risk assessment. The system identifies and categorizes individuals based on their behavior and other predefined criteria, assigning labels such as "High Risk" and "Low Risk".

## Features
- **Risk Assessment**: Automatically assess the risk level of individuals in real-time.
- **Visual Labeling**: Highlight individuals with visual cues and risk labels directly in the video output.
- **Surveillance Optimization**: Enhance surveillance systems with AI-driven insights to improve safety and monitoring efficiency.

## How It Works
The system processes video streams using a sophisticated AI model that detects individuals and evaluates their behavior against a set of criteria to determine risk levels:
1. **Detection**: The system detects individuals in the video using object detection algorithms.
2. **Analysis**: Each detected individual is analyzed to assess risk based on movement, proximity to others, and other relevant factors.
3. **Labeling**: Individuals are labeled in the video according to their assessed risk level.

## Visual Overview
The following animation demonstrates the system's capability to analyze and label individuals in a surveillance video:
![Risk Assessment in Action]https://github.com/nupurrathod/SafeSpace-Monitor-Social-Distance-Monitoring-System-/blob/main/output.gif


## Setup and Operation
To set up and run this project:
1. Clone the repository.
2. Ensure you have the necessary Python packages installed: `opencv-python`, `numpy`, `tensorflow` (or `torch`), depending on the specifics of the implementation.
3. Run the script with the appropriate parameters:
   ```bash
