# Dinosaur-AR-App-Unity

## Project Name: Dinosaur-AR-App-Unity
### Augmented Reality Dinosaur Application

### Group Details

Member Details:

| Name          | Student ID  | Username  |
| --------------| ------------| ----------|
| Ariyasena P.P.S. | IT20657864 | IT20636524 |
| De Zoysa R.L.   | IT20650834 | Lakshikz  |

## Project Description

This project involves building an augmented reality (AR) application using Unity and Vuforia. The application allows users to interact with 3D dinosaur models in an augmented reality environment. The goal is to create an immersive AR experience that can be deployed on mobile devices.

## Technologies

- **Game Engine**: Unity
- **AR SDK**: Vuforia

## Setup Instructions

### 1. Clone the Repository

First, clone the repository to your local machine using Git:

    
    git clone https://github.com/IT20636524/Dinosour-AR-App-Unity.git
    cd Dinosaur-AR-App-Unity

### 2. Install Git LFS

Ensure Git LFS is installed and initialized:

    git lfs install
    git lfs pull

### 3. Open the Project in Unity

Open Unity Hub.
Click on the Add button and select the cloned repository folder.
Open the project by selecting it from the list in Unity Hub.

### 4. Import Vuforia Package

Since the Vuforia package is not included in the repository due to size constraints, you'll need to download and import it manually:

Download Vuforia Package:
    Go to the Vuforia Developer Portal and download the Vuforia Engine package (com.ptc.vuforia.engine-10.22.5.tgz).

Add Vuforia Package to Project:
    Place the downloaded .tgz file in the Packages directory of the project.
    Open Unity and navigate to Window -> Package Manager.
    Click on the + icon and select Add package from tarball....
    Navigate to the Packages directory and select the com.ptc.vuforia.engine-10.22.5.tgz file to import it into your project.

### 5. Configure Vuforia

Add Vuforia License Key:
    Go to Edit -> Project Settings -> Vuforia.
    Enter your Vuforia license key, which you can obtain from the Vuforia Developer Portal.

Set Up AR Camera and Image Targets:
    In the Unity Editor, add an AR Camera to your scene by right-clicking in the Hierarchy and selecting Vuforia -> AR Camera.
    Add Image Targets by right-clicking in the Hierarchy and selecting Vuforia -> Image.

### 6. Build the Project

To build the project for mobile devices, follow these steps:

Open Build Settings:
    Go to File -> Build Settings.

Select Platform:
    Select your target platform (e.g., Android, iOS).
    Click on Switch Platform to apply the change.

Add Scenes to Build:
    Add the scenes you want to include in the build to the Scenes in Build list by clicking Add Open Scenes.

Configure Player Settings:
    Click on Player Settings and configure the settings for your target platform, including Company Name, Product Name, and other settings relevant to your platform.

Build and Run:
    Click Build and Run to build the project and deploy it to your connected device, or click Build to create a build that you can manually transfer to your device.

Video Demonstration

For a video demonstration of the application, please watch the following video:

[Video Demonstration Link][(https://www.youtube.com/your-video-link)](https://drive.google.com/drive/folders/1Crxxk-hmv5_6Jb0FELuGGNDmxa_asdTG?usp=sharing)

Links

- [GitHub Repository](https://github.com/IT20636524/Dinosour-AR-App-Unity)
- [Vuforia Developer Portal](https://developer.vuforia.com/)



