# Samples for ORB-SLAM2 in Web

HOW to run?.<br>
1-you have to install apache server.<br>
2-but the code in the HTDOC Folder.<br>
3-start the Server.<br>
4-but this link in the browser "http://127.0.0.1/slamjs_samples-master/".<br>


To run the samples, your browser need support: "Web Worker" and "SharedArrayBuffer".<br>
The monocular sample will obtain images from WebRTC and your camera.<br>
The RGB-D sample will obtain images from rgb video file and depth video file. <br>The videos are from [TUM CVG dataset](https://vision.in.tum.de/data/datasets/rgbd-dataset/download).<br>
Console will print the tracking state, camera pose and the numbers of key points and map points.
