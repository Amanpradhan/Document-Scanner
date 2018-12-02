# Document-Scanner

It is a Document Scanner which scans documents from an image and then does OCR (Optical Character Recognition) on it. 


It involves 3 steps:

1. Segmenting the document (drawing bounding box around it)
2. Increasing image quality
3. Trying to convert image data to text format 


How to use it:

1. pip install -r requirements.txt 
2. run python scan.py
3. after that, paste the path of the image you want to do image segmentation on.


End Note - This project is heavily inspired by pyimagesearch course of computer vision to do document segmentation and OCR.

I will soon be building my own YOLO classifier which segments document using Neural Networks.

# OCR

To install tesseract, run :

sudo apt-get install tesseract-ocr

If you want to do Optical Character Recognition on the extracted image, then go to the output folder, open terminal and run:

tesseract image_name out
The output will be saved in a file named out.txt


