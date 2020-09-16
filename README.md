# Face-Recognition-using-OpenCV
This is Face Recognition Model which is an implementation of Haar Casscade classifier, which used detectMultiScale() feature to detect all the features from an image, and store them in XML file.

The Process goes like this:-
1. First we created a function that take input from our webcam, detect the face and crop it and save them in a defined pixel value
2. Then we combine all the RGB feature, convert the image into black and white.
3. Another feature which extracts the features from the images and stores all of them in XML file
4. Next we train our model using those XML files
5. We extraxt test image from our webcam, and predict the confidence value.
