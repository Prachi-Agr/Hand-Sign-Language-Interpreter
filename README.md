# Hand-Sign-Language-Interpreter
An app that interprets hand sign language and converts to audio. 
This project was presented at a 24hr hackathon at IISC Bangalore in January 2020 and awarded 2nd position.

An android app has been developed which takes hand gesture images from the camera, uploads it to a Flask backend where a CNN Classifier model with a VGG16 base model classifies the image. It currently supports two formats :the American and Indian Sign Language. The classified label is returned to the android app which is then converted to speech.
