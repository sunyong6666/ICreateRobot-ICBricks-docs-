# User Guide
## Required Permissions
The mobile app does not involve a registration process, nor does it upload any of your personal information to servers. During usage, you only need to grant the following device permissions to ensure the proper functioning of related features:  

**Storage**

Purpose: To save and read programming projects.

Special Note: Your programming projects are stored locally on your device and will not be accessed or uploaded.

**Bluetoot**

Purpose: To connect to hardware devices and enable interactive operations with hardware.

Special Note: During Bluetooth communication, data is transmitted only between your device and the hardware. Communication content is neither recorded nor disclosed.

**Location**

Purpose: To scan BLE (Bluetooth Low Energy) devices, as required by technical specifications.

Special Note: The app does not collect location information; this permission is solely for Bluetooth scanning purposes.

## Connecting Devices  
Using Bluetooth 4.0, you can easily connect your device to the main controller to unlock a variety of functions:  

+ **Beginner Version:** Supports running programs directly in online mode.
+ **Advanced Version:** Allows uploading programs to devices for offline operation.

### Connection Steps:  
1. **Power On the Device:** Press the device's power button to start.  
2. **Enable Bluetooth and Location Services:** Ensure Bluetooth and location services are active to support Bluetooth Low Energy mode.  

![](img/U01.png)

3. **Open the Programming Software:** Tap the Bluetooth button to initiate the device connection.  

![](img/U02.png)

4. **Select the Device:** If multiple devices are detected, choose the target device from the dropdown menu.  

![](img/U03.png)

5. **Complete the Connection:** Once connected, the target device will display a green background with a "Disconnect" button. The Bluetooth connection status will remain active within the app, eliminating the need for frequent reconnections.  

![](img/U04.png)

## Creating a Project  
1. **Choose Beginner Mode:** Select the basic programming mode for a quick start.  

![](img/U05.png)

2. **Click "New Project":** Create a brand-new project.  

![](img/U06.png)

3. **Edit the Program:** Drag and drop blocks to write your program.  

![](img/U07.png)

4. **Exit and Save:** Tap the back button to automatically save your program. You’ll return to the main interface to view your project list.  

![](img/U08.png)



## Online Mode (**Beginner Version)**
1. **Write a Program:** Enter the basic programming interface to create your program.  

![](img/U09.png)

2. **Click the Run Button:** The program will run on the device in real-time. Note that the program stops running if the Bluetooth connection is interrupted.  

![](img/U10.gif)

## Offline Mode (Advanced Version):  
1. **Write a Program:** Enter the advanced programming interface to design more complex logic.  

![](img/U11.png)

2. **Click the Run Button:** The program is downloaded to the device and starts immediately. It continues running even if the Bluetooth connection is lost.  

![](img/U12.gif)

3. **Click the Download Button:** The program is downloaded to the device but does not execute immediately. You can run it later, even without a Bluetooth connection.  

![](img/U13.gif)

4. **Start a Downloaded Program:** Press the device's power button three times in quick succession to run the downloaded program. Note that the Bluetooth connection will be interrupted, and the device cannot reconnect while the program is running.  

![](img/U14.gif)

5. **Quickly Stop a Running Program:** While the program is running, press the power button three times in quick succession to stop it.  

![](img/U15.gif)

## Renaming the Bluetooth Device  
| ![](img/U16.gif) | ![](img/U17.gif) |
| --- | --- |
| 1. **Connect the Device:** <br/>Tap the Bluetooth button, select the target <br/>device in the list, and connect. <br/>The hub's breathing light will flash white <br/>to indicate a successful connection.     | 2. **Access the Rename Option:** <br/>Tap "Select Device" 10 times in a row to <br/>bring up the rename input box.    |
| ![](img/U18.gif) | ![](img/U19.gif) |
| 3. **Enter a New Name:** <br/>Input the new name in the box. A confirmation <br/>window will appear upon a successful name change.   | 4. **Reconnect to View the New Name:** <br/>Disconnect the Bluetooth connection, refresh <br/>the device list, and reconnect to see <br/>the updated device name.   |

## AI
Machine Learning provides four types of training models: Image Recognition, Gesture Recognition, Pose Recognition, and Speech Recognition. By creating and training a model, the system automatically generates the corresponding programming blocks for the selected model category, allowing you to easily incorporate the trained model into your programs.

Example: Train an Image Recognition model. After the training is complete and the programming blocks are generated, use the corresponding blocks to develop your application.

| ![](img/U21.png) | ![](img/U22.png) |
| --- | --- |
| 1. Open ICBricks Advanced Programming Software, then select the AI category.   | 2. Click training model.   |
| ![](img/U23.png) | ![](img/U24.png) |
| 3. In the Machine Learning panel, select a training model. Click Image Recognition.<br/> _(Image Recognition is used as an example in this guide.)_ | 4. Click New Project.   |
| ![](img/U25.png) | ![](img/U26.png) |
| 5. Click Camera to capture image samples in the pop-up camera window.  <br/> **Note:** <br/> You can capture one or more samples for the same class. <br/>At least **two classes** are required for image model training.   | 6. Press and hold Capture for 1–2 seconds to capture an image sample. <br/>The captured samples are displayed in the yellow panel on the left. <br/>It is recommended to collect approximately 30 image samples for each class.   |
| ![](img/U27.png) | ![](img/U28.png) |
| 7. After all image samples have been collected, click Start Training.<br/> You can monitor the training progress using the progress bar.   | 8. When the training is complete, the software automatically enters Model Testing mode. <br/>Place a sample in front of the camera and verify that the software correctly identifies the sample's class <br/>and displays its confidence score. After confirming that <br/>the test results are correct, click Use Model.   |
| ![](img/U29.png) | ![](img/U30.png) |
| 9. The Machine Learning category will automatically generate the programming blocks for the trained model. <br/>Drag the corresponding blocks into your program to use the trained model.   | 10. During programming and program execution, observe the model recognition results in the Recognition Window.   |


**Demonstration：**

<!-- 这是一张图片，ocr 内容为： -->
![](img/U31.gif)





