/*AIM*/
The algorithm identifies an object of shape(triangle or rectangle) and colour (red, yellow or blue) and tracks it in real time. 
Due to the nature of this task, the algorithm was restricted to detect and track only one object in a frame.

Motivation
This algorithm was developed for MATE ROV International Competition 2017/18. The mission was to identify the aircraft type based on the shape and colour of the aircraft's tail. This mission was carried out underwater using a ROV and hence this algorithm has been tested underwater.


Video Demonstration
http://tiny.cc/i9a1dz


Setup/Installation
1. sudo apt-get install opencv-python
2. Execute 'ObjectDetection_Main.py'
3. Algorithm runs on MacOS. Modify settings like opening web camera if using other operating systems
4. Ensure that background is plain without any noise and appropriate lighting is available
5. Once the webcam is up and running, bring a triangle/rectangle of blue, red or yellow colour in the frame
6. The algorithm will detect and track the object


Structure of Folder
1. I/O Flow Diagram for 'ObjectDetection_Main.py'
2. Main Proposed Algorithm: 'ObjectDetection_Main.py'
3. Alternative Method 1:'ObjectDetection_Main_Alternative_1'
4. Alternative Method 2: 'ObjectDetection_Main_Alternative_2'

Error
If inconsistent is because of lighting in the room. Modify the HSV values, brightness, contrast and sharpness

Future Extension
1. Can be extended to detect and track multiple objects in a single frame
2. Can be extended to detect and track more shapes
3. Can be extended to detect and and track more colours


