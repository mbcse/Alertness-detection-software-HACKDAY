                                          # Alertness-detection-software-HACKDAY



# Project Description :
In the current scenario working is so tiring that we often fall asleep , but feeling sleeping  during driving can be very dangerous or might lead you  to major accident. So to avoid such hazardous accidents we thought that savilian cameras or IOT  device should be their in cars with our software inbuilt which will help drivers to stay awake or reach home safely
This concept can be extended like in corporate meeting , cctv cameras .
Last but not the least it could also be used in schools to check it a student is sleeping or not. 

# About our software
Our software detects if the driver is yawning or his/her eyes are closing 
If driver is detected to yawn/close eyes more than a threshold times then an alarm is activated 



# To test our software :

NOTE: Download shape predictor dat file

Step 1:
Run the Python script using command line 
	Type python   sleep_detection.py --shape-predictor (path to shape_predictor_68_face_landmarks.dat file) 

Step 2:
Model will run and it will start the webcam of the pc or laptop 

Step3:
Come closer to the Webcam so that it can detect your eyes and lips 

Step 4:
 When you either close your eyes or yawn warning audio will be generated and after 4 warning a loud alarm will be generated to stop the car immediately 
