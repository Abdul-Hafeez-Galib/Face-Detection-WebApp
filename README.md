# Face-Detection-WebApp

This is a simple web app made using Flask for Face-Detection developed using Haar Cascade in OpenCV.

### **Steps to try the project locally:**

1.  Download the project folder from my GitHub locally by directly downloading zip folder or 

    ```
      git clone https://github.com/Abdul-Hafeez-Galib/Face-Detection-WebApp.git
    ```
    
2. Open your Terminal and go to the directory of the folder.
3. Create a Virtual Environment for running Flask.

    ```
      py -3 -m venv venv
    ```
    
4. Activate the virtual environment.

    ```
      venv\scripts\activate
    ```
    
5. Install Flask in virtual environment.

    ```
      pip install flask
    ```
    
6. Install OpenCV in virtual environment.

    ```
      pip install opencv-contrib-python
    ```
    
7. Run the flask app.

    ```
      set FLASK_APP=app.py
    ```
    
    ```
      flask run
    ```
    
8. Go to  http://127.0.0.1:5000 in a you browser to see the app working locally.

### **Images of WebApp: (Detecting faces in webcam)**

<img width="563" alt="face-detection" src="https://user-images.githubusercontent.com/77202232/164677587-f030cbe4-a012-428f-b0bf-0f62db3530f6.png">
