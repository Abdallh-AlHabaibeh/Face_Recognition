# Face_Recognition
Note: Please ensure that you have the necessary libraries before running the project. This includes: dlib, face_recognition, os, scikit-learn, OpenCV, and Python. 

My face recognition system is a real-time application designed to detect and recognize faces within live video streams. Developed using Python and leveraging powerful libraries such as OpenCV and face_recognition, this project was undertaken independently as part of a larger endeavor. The system employs the Haar Cascade classifier, a popular method for object detection, to accurately locate faces in the video feed. To enable recognition, I created a dataset comprising known faces, each associated with their unique encodings derived using the face_recognition library. These encodings serve as the basis for comparison during recognition.

Powered by the K-nearest neighbors (KNN) algorithm, my model is trained with the known face encodings and corresponding names. During runtime, the system dynamically compares detected faces with those in the dataset. When a known face is identified, it is visually indicated by a green rectangle surrounding the face, accompanied by the person's name. For unidentified faces, a red rectangle is displayed, accompanied by the label 'Unknown face'.

To ensure accurate recognition, I implemented a threshold distance mechanism, allowing the system to distinguish between known and unknown faces effectively. This threshold helps mitigate false positives and enhances the system's reliability across different environmental conditions.

In addition to its recognition capabilities, my system is designed for seamless integration between front-end and back-end components, offering users a smooth and intuitive face recognition experience. With its robust functionality and user-friendly interface, my face recognition system is poised to provide valuable insights and applications in various domains.
