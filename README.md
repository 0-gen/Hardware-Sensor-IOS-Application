# README  
# Hardware-Sensor-IOS-Application
**Created by Eugen Feng 50173001**  
**For EE426 Wearable Sensors**

---

### Requirements

To run this code, you need a **MacOS Mojave** version 10.14.6.

If you are **not running this code** and just reading it, feel free to skip the following:

### Software Needed:
- **iPhone iOS 12.4** or older
- **Xcode 10.3** (Need this exact version)
    - Reason: Xcode 10.3 is the last version that supports **Swift 5.0** and iPhone iOS 12. Newer versions like Xcode 11+ support an entirely different SDK, and as it's a relatively new version, there are fewer tutorials available.

### Running the Code:
1. Drag the entire folder onto MacOS and open the `Sensored.xcodeproj` file.
2. On the left panel where all the files are listed:
    - The main code is in `ViewController.swift`
    - Code assigning labels/buttons/scroll/etc. is in `SensorView.swift`
    - The UI/Interface display is in `Main.storyboard`
    - The sensor data display window is in `Sensor.xib`
    - `RootPageViewController` allows swiping between screens.
    - Other files were generated when the app was first created.
  
3. To run the code on your phone:
    - In Xcode, next to the **Play/Run** button at the top left, find "Sensored>", scroll to the top, and select your device (ensure your device is connected to the computer).
    - Then click **Run**, and the app will download and open on your device.

**Note:** Running the code in simulation or a simulated device will not work since the simulated environment is static and won't produce actual data.

---

### Reading the Code:
To read the main code, navigate to the folder:  
`50173001_Feng/Sensored/ViewController`

### File Descriptions:

- `.../Sensored/Base.Iproj`:  
  Contains the default main screen that pops up when the app is opened and the launch screen. The main screen includes a reference screen, and I'll provide a screenshot if you're not running the code on your phone.

- `.../Sensored/SensorView`:  
  Correlated to the main code. This file adds labels, buttons, and image viewers to display certain data.

- `.../Sensored/Assets.x.cassets`:  
  Contains all the pictures used in the app.

- `.../Sensored/RootPageViewController`:  
  Allows swiping between the main page and the reference page.

- `.../Sensored/Sensor.xib`:  
  The selection screen for choosing which sensor data to display. A screenshot will be provided for this page as well.

Other files are system files generated when the app was first created.

---
