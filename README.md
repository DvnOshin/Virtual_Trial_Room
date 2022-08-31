Project Description: 

Virtual Trial Room project is based on the concept of Image Processing using Open CV Python. In this project, the user has to provide his own image with certain requirements and he/she can have a virtual experience of trial rooms while sitting at home.
The available outfits are pre-uploaded in the dataset and taken into account as required by the user, same can be used on a large scale by feeding the available data set into the system and the user can try them virtually.


Pre-Requisites:

- In the image provided by the user, the person must be wearing a blue colour t-shirt with a still body posture.
- The background in the image must not contain any blue coloured object. It is better to have a plain background without any extra element.


Working:

This project is made using Open CV and NumPy modules. Open CV module reads the image and detects the blue colour with the help of the NumPy array and makes the black and white masks of the blue colour in the original image. The T-shirts provided in the dataset are re-sized according to the original image and masked to black or white. Then using cv2.bitwise_or and cv2.bitwise_and both the masked image and the original image is superimposed. A Tkinter python Library is also imported which opens a window having t-shirt options to choose from. 

When the code runs a window with buttons appears on the screen. The user can then select any button of their choice. Then the image provided by the user, the image of the t-shirt along with the masked image appears on the screen which is the final output.


Output Screen:

![Output Screen](https://user-images.githubusercontent.com/61008588/187613332-c4d398c3-64e9-44bf-a0ee-368e24c3ea38.png)

![Tkinter Window](https://user-images.githubusercontent.com/61008588/187613337-54652f2d-aee1-4a86-987c-db014a43e818.png)
