 <img width="3188" height="1202" alt="frame (3)" src="https://github.com/user-attachments/assets/517ad8e9-ad22-457d-9538-a9e62d137cd7" />


## Blink Detector🎯

## Team Name: Binary Bandits


### Team Members
- Member 1:  Anna Sara Joji - Model Engineering College
- Member 2: Deeya Maria Sajeev - Model Engineering College

### Project Description
This is an interactive web-based project that uses the Mediapipe FaceMesh API to detect eye blinks in real-time via webcam. Each blink triggers chaotic visual and audio effects with randomized alerts and sound distortions. The project combines computer vision, JavaScript, and creative UI to simulate a humorous “chaos protocol” on blink detection.

### The Problem (that doesn't exist)
It is very hard to live not knowing how many times you blink . 

### The Solution (that nobody asked for)
 Our application counts the number of times you blink your eyes when it is running anda also roasts you for blinking.

## Technical Details
### Technologies/Components Used
For Software:
 Languages Used:HTML, CSS, JavaScript

 Libraries used: MediaPipe FaceMesh – for real-time facial landmark detection
                 MediaPipe Camera Utils – for handling webcam input

 Tools Used:Web browser (for deployment and testing)
           AudioContext API (for sound processing and effects)
           HTML5  – for drawing video and overlays
           GitHub or VS Code (if applicable for development)


### Implementation
For Software:
# Installation
#  1. Clone the repository (or download the HTML file)
git clone https://github.com/your-username/blink-chaos-mode.git
cd blink-chaos-mode
# 2. Open the HTML file in your browser
start index.html        
# Run
start index.html

### Project Documentation
For Software:

# Screenshots (Add at least 3)
1.[alt text](image.png)
  Before the website starts working. It starts working when the 'start chaos' button is pushed.

2.[alt text](image-1.png)
  The website has started working and no blinks have been detected.

3.[alt text](image-2.png)
  It has counted how many times I have blinked.
  
 
# Diagrams
            ┌───────────────┐
            │ Start Button  │
            └──────┬────────┘
                   │
                   ▼
       ┌────────────────────┐
       │  Access Webcam     │
       └────────┬───────────┘
                ▼
     ┌────────────────────────┐
     │ Video Frame Captured   │
     └────────┬───────────────┘
              ▼
   ┌─────────────────────────────┐
   │ MediaPipe FaceMesh detects  │
   │ facial landmarks (eyes)     │
   └────────┬────────────────────┘
            ▼
 ┌────────────────────────────────┐
 │ Calculate Eye Aspect Ratio     │
 │ (to detect blink)              │
 └────────┬───────────────────────┘
          ▼
 ┌────────────────────────────────────┐
 │ Blink Detected?                    │
 └───────┬──────────────┬─────────────┘
         │ No           │ Yes
         ▼              ▼
  (continue frames)   ┌──────────────────────────┐
                      │ Increment Blink Count    │
                      │ Show Roast Message       │
                      │ Play Distorted Sound     │
                      │ Flash Background         │
                      └──────────┬───────────────┘
                                 ▼
                  ┌─────────────────────────────┐
                  │ Update Blink Count on Page  │
                  └─────────────────────────────┘


### Project Demo
# Video
[Add your demo video link here]
*Explain what the video demonstrates*

# Additional Demos
[Add any extra demo materials/links]

## Team Contributions
- Anna Sara Joji : Html, Documentation
- Deeya Maria Sajeev :  CSS, Javascript
 

 