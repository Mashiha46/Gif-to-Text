# Gif-to-Text
### GIF
A GIF or Graphical Interchange Format is a type of highly Compressed Image. It is considered the most famous image format in the web world because of its portability and wide support with another image format; JPEG. 
### OCR
The method of extracting text from images is called Optical Character Recognition (OCR). **Tesseract** is an optical character recognition engine for various operating systems. It is free software, released under the Apache License.
## Installing Tesseract
### Linus
We Should Install Binary
- sudo apt-get update
- sudo apt-get install libleptonica-dev 
- sudo apt-get install tesseract-ocr tesseract-ocr-dev
- sudo apt-get install libtesseract-dev
### Mac
For Mac Users
- brew install tesseract
### Windows
- To Install tesseract using windows installer [Click here](https://github.com/UB-Mannheim/tesseract/wiki) and Download suitable Version.
- Add tesseract path to your System Environment i.e Edit system variable.
- Run ```pip install pytesseract``` and ```pip install tesseract```
- Run the Code.
#### Note: 
If We get an Error like this ```pytesseract.pytesseract.TesseractError: (1, 'Error opening data file \\Program Files (x86)\\Tesseract-OCR\\tessdata/eng.traineddata')``` then try to worked around by changing directory to the drive containing tesseract.
