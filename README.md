# Document-Scanner

It is a Document Scanner which scans documents from an image and then does OCR (Optical Character Recognition) on it. 


It involves 3 steps:

1. Segmenting the document (drawing bounding box around it)
2. Increasing image quality
3. Trying to convert image data to text format 


How to use it:

run python scan.py

The output will be saved in output/ directory and by default it will be 'test_s1.jpg'.
Do pip install requirements.txt
If you want to change the default file on which image segmentation will be done then simply give the path in line 330 in scan.py


End Note - This project is heavily inspired by pyimagesearch course of computer vision to do document segmentation and OCR.

I will soon be building my own YOLO classifier which segments document using Neural Networks.

# OCR

To install tesseract, run :

sudo apt-get install tesseract-ocr

If you want to do Optical Character Recognition on the extracted image, then go to the output folder, open terminal and run:

tesseract image_name out
The output will be saved in a file named out.txt


