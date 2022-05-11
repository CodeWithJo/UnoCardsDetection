# UnoCardsDetection
**MSc Robotic Intelligent Sensing for Robotics Module Assignment 2**

Note that This is a python Jupyter Notebook file.
In order to run the code succcesfully, you need to make sure you have 
install pillow python , tkinter, open cv and make sure you can import the libraries below: 

        from tkinter import * 
        import tkinter as tk
        import tkinter.messagebox
        from PIL import ImageTk, Image, ImageFont
        import numpy as np
        import cv2
        import os
        from tkinter import filedialog
        from tkinter.filedialog import askopenfile
    
Before you process any image, make sure you have the following folders and files 
**In the root folder** 

  unobg2.png (if not available it might cause GUI issues) 
  ImageReferences (Unzip) a subfolder with this name and with all the files for the feature extraction / feature matching function
 
**Once you are set:**
when you run file, a tkinter GUI opens up with two options/buttons

      Button 1 labled Video stream 
      Button 2 labled Upload Image 
  
 ** To detect the card features from the video stream click on the button 1**
    
        Note:
        Once the streaming starts show the card 
        For best results show the card upright and with the best natural light 
        I found that yellow and red cards work better in the evening with lighting in comparison to the blue and green cards.

        The results will be displayed on the screen as you continue to stream
    
  **To detect the cards features from an uploaded image click on the button 2**
  
        -click on upload 
        -on the pop up window locate your images 
        -and click open 
        The results with be displayed on a pop up window 
  
Find all project files at https://github.com/CodeWithJo/UnoCardsDetection.git
illustration video at https://www.canva.com/design/DAFAayn_XtY/IsnNAM2fvu1lPi1IfHA3Bg/watch?utm_content=DAFAayn_XtY&utm_campaign=designshare&utm_medium=link&utm_source=publishsharelink 


Project references:

        https://opencv24-python-tutorials.readthedocs.io/en/latest/py_tutorials/py_feature2d/py_matcher/py_matcher.html
        https://devdreamz.com/question/583210-error-invalid-number-of-channels-in-input-image-vscncontainsscn-using-o
        https://stackoverflow.com/questions/62324303/4-corners-of-a-playingcard-with-contours
        https://www.plus2net.com/python/tkinter-filedialog-upload-display.php
        https://pysource.com/2021/10/19/simple-color-recognition-with-opencv-and-python/
        https://github.com/EdjeElectronics/OpenCV-Playing-Card-Detector
        https://www.tutorialspoint.com/python/python_gui_programming.htm
