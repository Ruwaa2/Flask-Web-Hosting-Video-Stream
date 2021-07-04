# Flask-opencv webcam streaming server #
This is a simple python3 script that serves a tiny Flask video webserver that allows to take photos or see real time video streaming of a connected camera/webcam controlled with opencv.

## Requirements ##
In order to execute the script you need to install opencv3 -> `import cv2` and some python modules.

Move to the project folder using `cd` and try:

### Try #1: ###
```
pip install -r requirements.txt
```

### Try #2: ###
```
pip install flask opencv-python
```
If it gets any error, probably with `opencv-python` try to install them manually.

## Running ##
To start the service, Move to the project folder using `cd` and type `python server.py` or `python3 server.py`

*It only runs on python3*

Once done navigate to the ip of the server and access the port `5000`.

http://localhost:5000
