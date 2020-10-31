# FaceMask_Detection

Face Mask Detection using Python, Keras, OpenCV and MobileNet | Detect masks real-time video streams

The face mask detector didn't use any morphed masked images dataset. The model is accurate, and since the MobileNetV2 architecture is used, it’s also computationally efficient and thus making it easier to deploy the model to embedded systems (Raspberry Pi, Google Coral, etc.).

This system can therefore be used in real-time applications which require face-mask detection for safety purposes due to the outbreak of Covid-19. This project can be integrated with embedded systems for application in airports, railway stations, offices, schools, and public places to ensure that public safety guidelines are followed.

## Requirements 

1. tensorflow>=1.15.2
2. keras==2.3.1
3. imutils==0.5.3
4. numpy==1.18.2
5. opencv-python==4.2.0.*
6. matplotlib==3.2.1
7. scipy==1.4.1
