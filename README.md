# Trace an Object With Acceleration Data
This project which contains a Android application and a Java desktop application aims to estimate object position with using accelerometer data and camera.<br>

# Sensor Camera Application - Android
This Android application is designed to capture video and accelerometer data frame by frame.<br>
Sensor Camera app records video and accelerometer data simultaneously, accelerometer data will be saved in a .txt file.<br>
To record sensor data go settings and check "İvme Verisini Kaydet" radio button. <br>
Both sensor data and video will be saved DCIM/SensorKamera directory.<br>
[Releases](https://github.com/yusufhanoglu/SensorCamera/releases)

# Acceleration Estimation Application - Java Desktop
This Java desktop application is designed to estimate position of an object with using video file and accelerometer data file captured with Sensor Camera app in Android.<br>
Copy video file and accelerometer data file with same name to your computer, then in application, specify alpha value and video file path with extension.<br>
Acceleration Estimation application can use Tiny-Yolo to update bounding box coordinates. This option can be activated in application menu.<br>
Bounding boxes founded by accelerometer data will be shown red, founded by Yolo will be shown green if the bounding box coincide with estimation or cyan if the bounding box does not intersect with estimation.<br>
[Releases](https://github.com/yusufhanoglu/SensorCamera/releases)<br><br>
<i>Note: If Acceleration Estimation Application gives blank gray screen despite of true path of video file it might be indicating that your graphics card does not fully compatible with this version of OpenCV.</i>


# Samples
[Sample BB and GT Files for V1.61](https://drive.google.com/file/d/1zAT5l4xauxtDdpz8zE4eZS2AHU1Uuus-/view?usp=sharing)<br>
[Video Samples for V1.6](https://drive.google.com/file/d/1x0R58basjZ9K1ZpFCl-UxXY3-kb-m_K7/view?usp=sharing)<br>
[Video Samples for V1.5](https://drive.google.com/file/d/1k6Fp2bTy_7pMkYJggb7h1VEjG1-Z7VZy/view?usp=sharing)<br>
[Video Samples](https://drive.google.com/open?id=1PKtGLsmNJqkDpbaXovzigSYElGIMpiez)<br>
[Usage Samples](https://drive.google.com/open?id=15TVBRzGi_MRuwwZEocUp0MUSng2NXFtV)<br>
<br>

# Object Tracker - All in One Android App
This Android application is designed to both capture video and track objects. This application is a combination of the above two apps.<br>
[Examine](https://github.com/yusufhanoglu/ObjectDetector)<br>


