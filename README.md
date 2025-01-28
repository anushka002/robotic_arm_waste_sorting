# Final Year Project: 
University: Dr. Vishwanath Karad MIT World Peace University, Pune, India.
CGPA: 9.7/10
Course: B.Tech Robotics and Automation

## Title: Design and Prototyping of a Robotic Arm for Waste Sorting

### Aim: 
The project aims to automate the segregation of waste into four categories: plastic, glass, paper, and metal using a 4-DOF robotic arm equipped with a vacuum gripper and computer vision-based object detection.

### Waste Detection using YoloV7
![waste detection](https://github.com/user-attachments/assets/2b52a4da-27b6-46ca-9016-917e481c17ff)

### Circuit Diagram
![circuitdiagram](https://github.com/user-attachments/assets/641eaf04-a080-4195-a1a1-61c949978303)

### Final Prototype
![Robot Arm](https://github.com/user-attachments/assets/b0069ecb-1a67-47d3-8b49-feaf13fb6041)

### Conclusion:
- Successfully designed and prototyped a 4 degree of freedom Robot arm for sorting waste into 4 categories: plastic, paper, metal and glass.
- The sorting of waste is conducted using YOLOv7, a computer vision technique.
- Design and static structural analysis of the robot arm is performed on Ansys 2022 R1 which confirms that the design is safe to operate.
- Servo motors are selected based on the torque calculations and the vacuum pump is selected based on its flow rate.
- Maximum payload that the robot arm can pick is found to be 300g for the 1cm suction cup and 500g for the 3cm suction cup.
- A trash dataset was imported from RoboFlow containing 4878 images and YOLOv7 model was trained for this dataset with 50 epochs using Google Colab.
- Out of 10 images, 7 number of images were correctly classified. The accuracy of the model is **70%**. 
