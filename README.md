# Facial-recognition
A facial recognition system is a technology potentially capable of matching a human face from a digital image or a video frame against a database of faces. Such a system is typically employed to authenticate users through ID verification services, and works by pinpointing and measuring facial features from a given image.
Installation and Running
Before running this script, ensure you have the necessary libraries installed. Here’s a step-by-step guide:
![image](https://github.com/pixel-06/Facial-recognition/assets/104183935/291390d5-f27e-4f45-859b-0cf884d56bfd)

Install OpenCV:
pip install opencv-python opencv-python-headless

Install Flask:
pip install Flask

Install other dependencies:
pip install numpy pandas scikit-learn joblib

Install OpenCV with Contrib modules:
The opencv-contrib-python package includes additional modules, including the highgui module which provides GUI functionalities.

Install it with pip:
pip install opencv-contrib-python
pip install opencv-python-headless
pip install numpy matplotlib

Run the Flask App:
Save the script to a file, e.g., app.py, and run it with:
python app.py
![image](https://github.com/pixel-06/Facial-recognition/assets/104183935/65cfe2e3-33ef-4121-9bbe-efb5bc27025c)

Notes:

Camera Access: The script captures images from the default camera (usually the webcam). Ensure that your webcam is functional.

Error Handling: The script lacks extensive error handling. It’s advisable to add error handling, especially around file operations and camera access.

Model Saving: The trained KNN model is saved as face_recognition_model.pkl in the static directory. Ensure this directory is writable.

Scalability: For a larger number of users or higher accuracy, consider using more sophisticated face recognition models like those provided by deep learning frameworks.
![image](https://github.com/pixel-06/Facial-recognition/assets/104183935/d1955332-ffa3-4610-ba46-335e734b70dc)

