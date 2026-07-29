# 4 Hand-eye calibration

<!-- Please refer to the hand-eye calibration chapter in the video tutorial: https://www.bilibili.com/video/BV1xxTNzxEL2/?spm_id_from=333.337.search-card.all.click&vd_source=672e3f7240eaaca210b45e7c033dc45f
**Video chapter time node**: 2 minutes 47 seconds to 4 minutes 10 seconds -->

<!-- Calibration board generation website: https://calib.io/pages/camera-calibration-pattern-generator
You can set it according to the image parameters and print it out with a printer -->

In the camera project, find the calibration board file and print it out with a printer

<img src="../img/450_14.png" style="zoom: 50%;" />

<!-- <img src="../img/b2.png" style="zoom: 50%;" /> -->

Click the hand-eye calibration tool in the menu bar to open the hand-eye calibration tool window

<img src="../img/image-20241118151846708.png" style="zoom: 100%;" />

Select Eye on Hand and click Next

<img src="../img/image-20241118151646002.png" style="zoom: 100%;" />

Select Multi-pose Calibration and click Next

<img src="../img/image-20241118151709062.png" style="zoom: 100%;" />

Select Six-axis Robot and click Next

<img src="../img/image-20241118151658056.png" style="zoom: 100%;" />

Install the instructions in the picture, click the buttons in order, and after clicking the button and the log is output, proceed to the next step. Try to place the calibration plate in the center of the field of view to ensure that the robotic arm can completely capture the calibration plate after each movement

<img src="../img/b1.png" style="zoom: 50%;" />

Fill in the calibration plate spacing according to the side length of a grid of the calibration plate, click to identify the calibration plate, and click next after the score is output

<img src="../img/b3.png" style="zoom: 50%;" />

Click on the communication service configuration

<img src="../img/b4.png" style="zoom: 50%;" />

According to the image annotation, click the buttons in sequence

<img src="../img/b5.png" style="zoom: 50%;" />

Run the HandInEyeCailb.py file in the demo_code folder in the location_demo folder. After running the program, do not move the calibration board.

<img src="../img/450_17.png" style="zoom: 50%;" />

After the program ends, click Next, click Calculate Calibration Results, and after the results are output, click Save Calibration Results and save them to the InitFile folder in the location_demo file.

<img src="../img/b7.png" style="zoom: 50%;" />

<br/>

<img src="../img/b8.png" style="zoom: 50%;" />

<br/>

<img src="../img/b9.png" style="zoom: 50%;" />