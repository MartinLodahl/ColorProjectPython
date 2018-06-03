#Project info

Colour blindness is a spectrum and there is never a complete absence of colour. So colour-blind people can take care of most of the regular day to day activities without a problem. The colour blindness test is the first time they realize they are colour blind.

As to real world problems a colour blind person judges colour based on intensity and luminance so he/she would have very little difficulty doing the regular day to day activities including using traffic lights. People with severe degrees of colour blindness make appropriate adjustments subconciously to veer themselves through daily life.

But some professions require the correct recognition of colours like scientists, pilots, certain doctors, certain type of engineers, electricians, technicians in various fields. Their job may require them to recognize colour and their own life or life of others may depend on it.

With this is mind we conducted some research and realised that at this very moment the amount of python attempt to approach this market with specifically targeting colour blindness is very poor.

Our first release consists of 3 steps:

First step is the data collecting part. Because we are so lucky to have our very own comrade (Sean) in our group, we are able to collect realistic data. As mentioned above, there is a variety 
of different kinds of colour blindness, one of them being "Red-Green color blind". A big misconception when talking colour blindness is the fact that even though you are E.G. Red-Green colour blind, you can still see shades of red and green colors. Sean falls into this category and will be functioning as our test person thoughout the process.
The team collected 10 pictures, all with an isolated red value E.G (255,0,0). This number is then dropping by a consistent value of 30 for every interaction the user has. The interactions consists of the user being presented with an image and a question whether or not the colour red is present in the image. By doing this we can define the threshold (RGB wise) of where Sean is able to see the colour red. With this data we can continue to our next step, which involves context.

Second step is the context part. Now that we have collected some valuable information on Sean's threshold and tested his "base", we need to test his abilities in context aswell. Sean is now presented to another 10 pictures, this time everyday images with furnitures, equipment, you name it - All in common, they have the color red in it, with all kinds of different shades. The reason for doing this conduct of research is to collect more data and set in stone the challenges Sean faces when analysing such images.

Third and last step is the fun part. Our expectation when going through second step is that Sean will experience hard times trying to segment the colours in these images. However, what we will do in this step, is what we consider the "product" of our project. This time around we will present Sean with the exact same images as presented in step two, BUT now we will have forced down the conducted RGB values from step one onto every picture. This should greatly improve Sean's accepted response rates of the colour red being present in the images.

##Disclaimer
We are very well aware that research behind this subject is factor ten larger then our little four man army and of course there is alot of factors that is no taking into considerations in this project, an example being age. However, the thing that really intrigued us and got us motivated on this project was the fact that even though we are this small group of four guys from a university, with the right resources this could be a potential business model. Picture if you'd be able to further develope on this, to a point where it becomes a layer on operating systems. A programme, designed to gather enough information through a small process to calculate and state your individual RGB values, automatically processing everything from ads to images and forcing upon them your predetermined RGB values. This would expectant enhance the perfomance of the colour-blind and more important the comfortability of performing in higher stake jobs. 

#How to run the program 

This requires you to have jupyter notebook and related imports set up on your computer, but once you have got these set up. 
You'll need to run the 'Untitled.ipynb' interactive python code in Jupyter Notebook. When the program is running in Jupyter Notebook, you shall run the first cell, and the program will be going on by itself below the cell, where you'll have an output off a picture, and you'll need to answer in the input field, if you see the color red or not. 

##Imports needed. 

random 
matplotlib.pyplot 
numpy 
nbformat
nbconvert.preprocessors 
numpy 
cv2
