Live webcam is streamed from a mobile app; the stream can be view in the python app frontend; faces and names are identified and displayed real time.

Android App is IP Webcam (https://play.google.com/store/apps/details?id=com.pas.webcam&hl=en_IN&gl=US). face recognition is performed using https://pypi.org/project/face-recognition (which is a python library built on top of dlib)

There are also two files serversocket.py and socket-client.py that send server initiated messages (implements web socket). the idea is to extend the application and have server push messages or actions to android based on the faces detected.
