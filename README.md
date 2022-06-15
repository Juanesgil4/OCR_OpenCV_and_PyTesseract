# **Newspaper OCR and Facial Recognition using Pillow, OpenCV and PyTesseract**

In this project, we use some powerful python libraries such as Pillow, OpenCV and PyTesseract (Tesseract) to perform character recognition, as well as face recognition within some newspaper images that we provide.

The **Python Imaging Library known as PIL or [Pillow](https://pillow.readthedocs.io/en/stable/)** adds image processing capabilities to your Python interpreter. This library provides extensive file format support, an efficient internal representation, and fairly powerful image processing capabilities. The core image library is designed for fast access to data stored in a few basic pixel formats. It should provide a solid foundation for a general image processing tool.

This library will be used to deal with images, load, apply filters, display to the output among some other functionalities.

The **[PyTesseract](https://pypi.org/project/pytesseract/)** Library is a wrapper for [Google’s Tesseract-OCR Engine](https://github.com/tesseract-ocr/tesseract). It is also useful as a stand-alone invocation script to tesseract, as it can read all image types supported by the Pillow and Leptonica imaging libraries, including jpeg, png, gif, bmp, tiff, and others. Additionally, if used as a script, Python-tesseract will print the recognized text instead of writing it to a file.

This library will help us perform OCR and character recognition from the files we pass in.

**[OpenCV-Python](https://docs.opencv.org/4.x/d0/de3/tutorial_py_intro.html)** is a huge open-source library for computer vision, machine learning, and image processing. 
OpenCV supports reading of images in most file formats, such as JPEG, PNG, and TIFF. Most image and video analysis requires converting images into grayscale first. This simplifies the image and reduces noise allowing for improved analysis.

The contents of this repository are a result of the final project of the  <img src="https://images.ctfassets.net/00atxywtfxvd/2MlqAOzmHjSPtssv6HlNox/1cb35b40775835a5f574ebc5509907a1/coursera-wordmark-blue.svg" alt="Coursera" style="width:100px;"/> 
  **[Python3 Programming Specialization](https://www.coursera.org/specializations/python-3-programming)** in colaboration with the  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c1/University_of_Michigan_logo.svg/2560px-University_of_Michigan_logo.svg.png" alt="University of Michigan" style="width:100px;"/>.

By combining the use of these libraries, we are going to access some newspaper files using python code which allows us to search through the images, looking for the occurrences of keywords and faces. 
E.g. if you search for "Mark" it will return a contact sheet of all of the faces which were located on the newspaper page which mentions "Christopher".

# Results
## IPYNB Visualization
To visualize the notebook and the source code, we rendered it on `https://nbviewer.jupyter.org/`.

Access to the file here https://nbviewer.org/github/Juanesgil4/OCR_OpenCV_and_PyTesseract/blob/main/project.ipynb.

## Source Image File
<img src="https://github.com/Juanesgil4/OCR_OpenCV_and_PyTesseract/blob/main/Resources/a-0.PNG.png?raw=true" alt="Test Results" style="width:800px;"/>

## Example Results
<img src="https://github.com/Juanesgil4/OCR_OpenCV_and_PyTesseract/blob/main/Resources/test_results.PNG?raw=true" alt="Test Results" style="width:800px;"/>
