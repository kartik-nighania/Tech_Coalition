## TO install:

pip install -r requirements.txt

## to login to environment 
source face_recognition_app/bin/activate

## TO train and run:

python encode_faces.py --dataset dataset --encodings encodings.pickle

python face_detection_and_recognition.py --shape-predictor shape_predictor_68_face_landmarks.dat --encodings encodings.pickle --dataset dataset --camera 0

## BUTTONS
q on the image to close the app

a on the image to stop the app

d on the image to start it again

## To change the camera

in the --camera option while calling face_detection.py 
the integer value decides the camera.
change to 1 to use external webcam 
change to 2 to use 2nd external webcam
