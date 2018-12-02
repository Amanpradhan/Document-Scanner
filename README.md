# Document-Scanner

It is a Document Scanner which scans documents from an image and then does OCR (Optical Character Recognition) on it. 


It involves 3 steps:

1. Segmenting the document (drawing bounding box around it)
2. Increasing image quality
3. Trying to convert image data to text format 


How to use it:

run python scan.py

The output will be saved in output/ directory and by default it will be 'test_s1.jpg'.
If you want to change the default file on which image segmentation will be done then simply give the path in line 330 in scan.py
 