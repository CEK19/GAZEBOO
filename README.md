
<br><b> What is the function of each file ? <b></br>

1. talker.py: Using to create terminal. From terminal you can follow the guideline of syntax command in https://www.overleaf.com/read/drnsdvyjpttm
2. talker_excel.py: You can create terminal command base on modify excel file.
3. cmd.xlsx: Containing command lists
4. listener.py: Just a subcrisber node used to test receiving message from talker.py (receive from the topic that talker.py node send to)
5. detection.py: Using to detect traffic signal. It will send the msg is redefined at https://www.overleaf.com/read/drnsdvyjpttm. You need to change the path of
model "370.h5" download at the link below.

<br> <b> PREQUESITE FOR detection.py <b> </br>
- ROS Noetic: Install on Unbutu 20.04 at http://wiki.ros.org/noetic
- Tensorflow: https://www.tensorflow.org/install/pip
- Gazebo Simulation is turned on.
- Model Detection: https://drive.google.com/drive/folders/1-PSXko-rbEp4iNnfnL8Q4yf9ht7IIlh9?usp=sharing

<br> <b> With talker_excel.py <b> </br>
- Change path of code by: Right click on cmd.xlsx on VSC, choose "Copy path" and paste it in "path" variable in code
- Install openpyxl (PyPi): https://pypi.org/project/openpyxl/
