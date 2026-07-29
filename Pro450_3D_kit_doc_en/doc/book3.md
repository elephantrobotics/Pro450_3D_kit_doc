# 3 Unit Testing

## 3.1 Robotic Arm & Suction Pump Test

Run the `test.py` file in the `demo_code` folder within the `location_demo` folder. The robotic arm will return to its joint zero position, then move to the camera position, turn on the suction pump for 2 seconds, and then turn it off.

<img src="../img/450_18.png" style="zoom: 50%;" />

<!-- Select the Wi-Fi hotspot you want to connect to, enter the password, and then check the robot's wireless IP. The customer's computer must be connected to the same Wi-Fi hotspot as the robot. Open VNC, and enter the robotic arm's wireless IP, username, and password.

<img src="../img/wifi1.png" style="zoom: 50%;" />

Simply move the mouse over the Wi-Fi icon to display the wireless IP.

<img src="../img/wifi2.png" style="zoom: 50%;" /> <img src="../img/test.png" style="zoom: 50%;" />

**Note:** Replace `robot_ip` with the robot's actual wireless IP address.

## 3.2 Camera Testing

<!-- Refer to the camera debugging section in the video tutorial: https://www.bilibili.com/video/BV1xxTNzxEL2/?spm_id_from=333.337.search-card.all.click&vd_source=672e3f7240eaaca210b45e7c033dc45f>
**Video section time points: 1 minute 44 seconds to 2 minutes 46 seconds> -->

Change the IP address of the wired network card connected to the camera to automatic assignment. The connection between the camera and the computer must be direct; it cannot be connected via a USB-to-Ethernet adapter.

<img src="../img/new1.png" style="zoom: 50%;" />

Open the camera's parameter adjustment software and connect the camera.

<img src="../img/new3.png" style="zoom: 50%;" />

First, click the camera's color image and depth image acquisition buttons, then click the color point cloud mode. Adjust the camera's gain parameters as needed. The parameters in Left IR Stream and Right IR Stream should be consistent. The point cloud adjustment should match the effect shown in the image. After adjusting, be sure to close the camera parameter adjustment software.

<img src="../img/new2.png" style="zoom: 50%;" />

**Important Notes**: The camera parameters need to be readjusted every time the camera is powered on to ensure the image quality of the point cloud.

<!-- For detailed instructions, please refer to the video, which can be downloaded to your local computer for viewing. Video address: https://github.com/elephantrobotics/Pro3D_Kit/blob/mv/rvs_cam.mp4

Point cloud after parameter adjustment

<img src="../img/cam_p.png" style="zoom: 50%;" /> -->

<!-- Double-click the RVS icon on your desktop. After RVS opens, click Load.

<img src="../img/rvs1.png" style="zoom: 50%;" />

Then select the demo.rvs file in the location_demo folder.

<img <img src="../img/rvs2.png" style="zoom: 50%;" />

Then click Run

<img src="../img/rvs3.png" style="zoom: 50%;" />

Wait for the camera to initialize

<img src="../img/rvs4.png" style="zoom: 50%;" />

<br/>

<img src="../img/rvs5.png" style="zoom: 50%;" />

After the camera initializes successfully, click the interactive panel, then click Manual Trigger

<img src="../img/rvs6.png" style="zoom: 50%;" />

Showing video output is sufficient.

<img src="../img/rvs7.png" style="zoom: 50%;" /> -->