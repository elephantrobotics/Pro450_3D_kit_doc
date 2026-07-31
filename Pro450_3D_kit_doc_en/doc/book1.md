# 1 Software environment setup

## Computer configuration

|Requirements|Configuration|
|----|----|
|CPU|12th Gen Intel(R) Core(TM) i7-12700H 2.30 GHz|
|GPU|NVIDIA GeForce RTX 3050 and above|
|Memory|16.0 GB|
|Hard disk|128G available space|
|Network port|Gigabit network port|
|System|Windows 10 and above|

## 1.1 Python installation
It is recommended to install Python 3.8 or above. Official Python download address: https://www.python.org/downloads/

<img src="../img/pythondownload1.jpg" style="zoom: 26%;" />

<img src="../img/pythondownload2.jpg" style="zoom: 60%;" />

<img src="../img/pythondownload3.jpg" style="zoom: 50%;" />

## 1.2 Dependent library installation
Open a console terminal (shortcut Win+R, enter cmd to enter the terminal), enter the following command and press the Enter key on the keyboard
```bash
pip install pymycobot==4.0.6
```

## 1.3 Software package acquisition
Download address: https://github.com/elephantrobotics/Pro450_3D_Kit

Enter the download address in the browser, and after the software package is downloaded, unzip it.

<img src="../img/450_9.png" style="zoom: 20%;" />

<br/>

## 1.4 RVS installation
<!-- RVS official download address: http://res1.percipio.xyz/rvs/V1.8/RobotVisionSuite.zip -->

In the software package, find the RVS installer and double-click the program to install it.

<img src="../img/new101.png" style="zoom: 50%;" />

<br/>

<img src="../img/p1_2_3.png" style="zoom: 130%;" />

<br/>

<img src="../img/p1_2_4.png" style="zoom: 80%;" />

The path should not contain Chinese characters. It is recommended to install other disks other than C drive

<img src="../img/p1_2_5.png" style="zoom: 80%;" />

<br/>

<img src="../img/p1_2_7.png" style="zoom: 80%;" />

<br/>
<img src="../img/p1_2_8.png" style="zoom: 80%;" />

**Run and activate (application version license)**

Double-click the shortcut to start RVS for the first time. After the startup animation, the following prompt will appear.

<img src="../img/p1_3_3.png" style="zoom: 25%;" />

Click "OK", click "Copy" in the license dialog box, copy the machine code, and send the machine code to our after-sales colleagues

<img src="../img/p1_3_32.png" style="zoom: 150%;" />

After we receive the machine code, we will provide an activation file. The activation file is a license.txt, or a string, which is saved as license.txt. Please copy this txt file to the license directory under the RVS installation directory.

<img src="../img/image-20230713161953575.png" style="zoom: 60%;" />

## 1.5 Camera parameter adjustment software

<!-- Camera parameter adjustment software download address: https://en.percipio.xyz/downloadcenter/
<img src="../img/cam1.png" style="zoom: 50%;" /> -->
In the software package, find the percipio application and double-click to run the program without installation

<img src="../img/new102.png" style="zoom: 52%;" />

## 1.6 Project file configuration

<!-- Project file download address: https://github.com/elephantrobotics/Pro3D_Kit/tree/main

<img src="../img/git.png" style="zoom: 70%;" /> -->

In the software package, copy the entire location_demo folder to the RVS installation directory

<img src="../img/new103.png" style="zoom: 52%;" />

<img src="../img/450_10.png" style="zoom: 28%;" />

---

[← Previous Chapter](./readme.md) | [Next Chapter →](./book2.md)