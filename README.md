# CSD TEAM-10 - Human Pose Estimation

## Team Members

- **Gadi Surya Prakash (Team Lead)**
- **Kotha Neeraj Madhav**
- **Valavala Naga Sai Sandeep**
- **Adhikari Venkatesh**
- **Adari Chandini**
- **Kontham Lakshmi Hemanjali**
- 

**Introduction**

Human Pose Estimation is a computer vision task that involves identifying key                                                             points on the human body to understand movement and posture. It has become                                                          important in many fields—ranging from sports analysis to healthcare—because                                                                   it helps interpret human activity. In this project, we use the MediaPipe pipeline, which                                                         offers a simple and efficient way to implement pose estimation without building a
complex model from scratch. MediaPipe’s modular design and pre-trained models
make it ideal for real-time applications and rapid development.


**Abstract**

This project focuses on
Human Pose Estimation using MediaPipe—a robust, open-source framework developed
by Google. MediaPipe simplifies the process of detecting and tracking key body
points (like shoulders, elbows, and knees) in images and videos. By utilizing
MediaPipe’s ready-to-use modules, this project demonstrates an efficient and
real-time solution for applications such as fitness tracking, gesture control,
and healthcare monitoring. The following sections outline the key aspects of
the project, including its introduction, the underlying technology, practical
uses, and a step-by-step approach to build the system.


**Technology**

**Python:** Python
is the main programming language used in this project.

**OpenCV:**
It is used for image and video processing tasks, such as capturing video from a
camera, preprocessing images, and displaying results.

**MediaPipe Framework:** It is an open-source framework developed by Google.                                                                                                                 It provides ready-to-use solutions for computer vision tasks, including human pose estimation.

**Deep Learning Models:** The
project utilizes pre-trained deep learning models available within MediaPipe,
which are designed to detect and track human body keypoints.


**Uses and Applications**

Human Pose Estimation has
a wide range of practical applications. Using MediaPipe makes these
applications more accessible and easier to develop:

* **Fitness and Sports:**
  Monitor exercise form, track performance, and provide feedback on posture
  during workouts.
* **Healthcare:**
  Assist in physical therapy by tracking patient movements and ensuring
  exercises are performed correctly.
* **Entertainment and Gaming:**
  Enable gesture-based controls and improve motion capture for realistic
  animations.
* **Human-Computer Interaction (HCI):**
  Enhance interaction with devices by allowing control through body
  gestures, improving accessibility.

**Steps to Build**

Building a Human Pose
Estimation system using MediaPipe involves the following steps:

1. **Data Collection:**
   * Use publicly available datasets or
     create your own to ensure diversity in poses, lighting, and backgrounds.
2. **Integration of MediaPipe:**
   * Install and set up MediaPipe in your
     development environment.
3. **Preprocessing:**
   * Use MediaPipe’s built-in functions
     to handle video or image input.
   * Preprocess the data as needed (e.g.,
     resizing or normalization) to match MediaPipe’s requirements.
4. **Pose Detection:**
   * MediaPipe’s pipeline automatically
     processes the input data, applies the pre-trained model, and outputs the
     detected key points.
5. **Visualization and Postprocessing:**
   * Overlay the detected key points onto
     the original images or videos to visualize the pose.
6. **Testing and Optimization:**
   * Test the system on new data to
     verify accuracy and performance.
   * Adjust parameters or settings within
     the MediaPipe pipeline to optimize detection speed and precision.

**Conclusion**

By leveraging MediaPipe, this project
demonstrates a simple yet powerful method for human pose estimation. The
MediaPipe pipeline streamlines the development process by providing pre-trained
models and efficient processing modules, making it easier to build applications
that require real-time analysis of human movement. Whether used for fitness,
healthcare, gaming, or security, MediaPipe offers a practical and accessible
solution for integrating pose estimation into a variety of applications.

**Summary**

**1. Input:**
The project takes images or videos as input, usually captured via webcams, smartphone cameras, or video files. These inputs contain people performing various movements or poses, which the system will analyze.

---

**2. Processing:**
The input is processed using  **MediaPipe Pose** , which detects 33 key landmarks on the human body (like shoulders, elbows, knees, and ankles). The system calculates joint angles, tracks movements across frames, and analyzes body posture to recognize activities such as walking, running, or exercising.

---

**3. Output:**
The system outputs a skeleton overlay on the image or video, highlighting key joints and body posture. It also provides useful insights like joint angles, detected activities, and feedback (e.g., "Incorrect squat posture—knees are misaligned"). 
