# AIM
The algorithm identifies an object of shape(triangle or rectangle) and colour (red, yellow or blue) and tracks it in real time. It further displays these features in a written format in the frame. Due to the purpose of this algorithm, it was restricted to detect and track only one object in the frame.

# Motivation
This algorithm was developed for MATE ROV International Competition 2017/18. The mission was to identify the type of an aircraft based on the shape and colour of the aircraft's tail. This mission was carried out using an underwater robot and hence this algorithm was tested underwater.


# Video Demonstration
[Shows the algorithm detecting and tracking objects above the water](http://tiny.cc/khoksz)


# Structure of Repository
1. 'FlowDiagram_ObjectDetection_Main.pdf': Flow Diagram showing the working of main algorithm
2. 'ObjectDetection_Main.py': Main Proposed Algorithm
3. 'ObjectDetection_Main_Alternative_1':Alternative Method 1
4. 'ObjectDetection_Main_Alternative_2':Alternative Method 2

# Setup/Installation
```
sudo apt-get install opencv-python
```
1. This algorithm runs on MacOS. Therefore, modify settings like opening web camera if using other operating system
2. Ensure that background is plain without any noise and appropriate lighting is available
3. Execute 'ObjectDetection_Main.py'
4. Once the webcam is up and running, bring a triangle/rectangle of blue, red or yellow colour in the frame
5. The algorithm will detect and track an object of the any of the above combination. Only a single object will be tracked in the frame


# Potential Failures
If results obtained are inconsistent it is likely due to poor lighting in the room. Modify the HSV values, brightness, contrast and sharpness in the code to improve accuract.

# Future Work
1. Detecting and tracking multiple objects in a single frame
2. Detecting and tracking other types of objects (i.e. other shapes and colours)
3. Automatically adjusting the contrast and brightness of an image to deal with varying lighting conditions


