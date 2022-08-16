# Optical Character Recognition.
Implementing optical character recognition using PaddleOCR.

## Introduction
The PaddleOCR repository is from baidu servers. The model has been extensively trained on different types of images and can therefore extract text from different types of images e.g., prescription bottles, number plates, memes etc. For this project I was trying to implement an ocr model that could properly detect text from images in hopes of creating an extension that will help me copy code directly from the video tutorials. It is a bit cheeky but I have to try. The learning curve on this project is honestly quite interesting. Anyone who would like to copy this code and maybe compile it on their localhost is very welcome to do so. 

## Getting Started
Install the PaddleOCR using the following code:

`!python3 -m pip install paddlepaddle-gpu -i https://mirror.baidu.com/pypi/simple`

The PaddleOCR framework has a custom font in the final display hence, one also has to clone the github repo in order to use the fonts in the final display.

`!git clone https://github.com/PaddlePaddle/PaddleOCR`


The necessary imports to be able to run this python code includes:
>
- cv2
- matplotlib
- PaddleOCR
- os

### Prerequisites
The only prerequisite is a **Jupyter notebook** or a google collab. 

## Credit
 I used code from the repo https://github.com/PaddlePaddle/PaddleOCR and a tutorial from Nicholas Renotte (https://www.youtube.com/watch?v=t5xwQguk9XU&t=780s). It’s always important to give credit where credit is due. 

## Future Updates 
Some of the future tasks will include:
>
- Creating a GUI that lets one define the binding boxes.
- Converting the python code to an exe file.
- Compiling to **.crs** which is required for the chrome extension. 
## License
MIT

## Contact
John Ruoro and SnowTec
ruorojohn@gmail.com
