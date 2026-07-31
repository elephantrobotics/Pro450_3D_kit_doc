# 4 Hand-Eye Calibration

<!-- Refer to the hand-eye calibration section in the video tutorial: https://www.bilibili.com/video/BV1xxTNzxEL2/?spm_id_from=333.337.search-card.all.click&vd_source=672e3f7240eaaca210b45e7c033dc45f
**Video section time point**: 2 minutes 47 seconds to 4 minutes 10 seconds -->

<!-- Calibration board generation website: https://calib.io/pages/camera-calibration-pattern-generator
Set the parameters according to the image and print it out -->

**Friendly Reminder**: If the user strictly follows the hardware installation section to install the camera, the user can directly jump to the function reproduction section to reproduce the function. If the workpiece cannot be captured, then perform hand-eye calibration.

In the camera project, find the calibration board file and print it out.

<img src="../img/450_14.png" style="zoom: 60%;" />

<!-- <img src="../img/b2.png" style="zoom: 50%;" /> -->

Double-click the RVS icon on your desktop. After RVS opens, click the Hand-Eye Calibration Tool in the menu bar to open the Hand-Eye Calibration Tool window.

<img src="../img/image-20241118151846708.png" style="zoom: 23%;" />

Select "Eye on Hand" and click Next.

<img src="../img/image-20241118151646002.png" style="zoom: 48%;" />

Select "Multi-pose Calibration" and click Next.

<img src="../img/image-20241118151709062.png" style="zoom: 48%;" />

Select a six-axis robot and click Next.

<img src="../img/image-20241118151658056.png" style="zoom: 48%;" />

Follow the installation image guide, click the buttons in sequence. After clicking each button and the log is output, proceed to the next step. Place the calibration plate in the center of the field of view to ensure the robotic arm can completely capture the calibration plate after each movement.

<img src="../img/b1.png" style="zoom: 27%;" />

Enter the calibration plate spacing according to the side length of one grid on the calibration plate. Click "Recognize Calibration Plate," and after the score is output, click Next.

<img src="../img/b3.png" style="zoom: 27%;" /> 

<img src="../img/b4.png" style="zoom: 27%;" />

Following the image annotations, click the buttons in sequence.

<img src="../img/b5.png" style="zoom: 27%;" />

Run the HandInEyeCailb.py file in the demo_code folder within the location_demo folder. Do not move the calibration board after running the program.

<img src="../img/450_17.png" style="zoom: 58%;" />

After the program finishes, click Next, then click Calculate Calibration Results. After the results are output, click Save Calibration Results and save them to the InitFile folder within the location_demo folder.

<img src="../img/b7.png" style="zoom: 27%;" />

<br/>

<img src="../img/b8.png" style="zoom: 29%;" />

<br/>

<img src="../img/b9.png" style="zoom: 47%;" />

Finally, close the RVS software

---

[← Previous Chapter](./book3.md) | [Next Chapter →](./book4.md)