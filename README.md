# Smart Attendance System

This project is a smart attendance system that uses computer vision technology to capture the photos of students and automatically mark their attendance without the need for any manual intervention. The system is designed to detect multiple faces and identify them using a trained machine learning model.

**Features**  
Automatic attendance marking without the need for manual intervention  
Detection of multiple faces in a single photo  
Ability to recognize faces using a trained machine learning model  
Integration with Firebase for real-time attendance tracking and reporting  

**How it Works**  
The smart attendance system uses a camera to capture the photos of students. The photos are then processed using a computer vision algorithm that detects faces and identifies them using a trained machine learning model. The detected faces are then marked as present in the attendance database, which is hosted on Firebase.

The system uses YOLO (You Only Look Once) pre-trained weights for face detection, which is a popular algorithm for object detection in real-time scenarios. The machine learning model used for face recognition is trained on a dataset of labeled faces using a deep learning framework like TensorFlow or PyTorch.

The attendance database is hosted on Firebase, which provides real-time updates and easy access to attendance records. The attendance records can be accessed by authorized personnel through a web-based dashboard or mobile application.


The capture script take 50 images of the face and stores it.  
The training script trains the model with the dataset created and makes a .yml file which is used to recognize the face.  
The automation of facedatabase creates a link with firebase, recognizes the face and updates the attendance.

**Structure**  
![Smart Attendance System](images/structure.png "Structure")

**Process**  
![Smart Attendance System](images/process.png "Process")
