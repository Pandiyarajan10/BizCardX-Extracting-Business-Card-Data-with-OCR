# BizCardX-Extracting-Business-Card-Data-with-OCR

## What is EasyOCR?

   EasyOCR, as the name suggests, is a Python package that allows computer vision developers to effortlessly perform Optical Character Recognition.It is a Python library for Optical Character Recognition (OCR) that allows you to easily extract text from images and scanned documents. In my project I am using easyOCR to extract text from **business cards.**
   
   When it comes to OCR, EasyOCR is by far the most straightforward way to apply Optical Character Recognition:

   - The EasyOCR package can be installed with a single pip command.
   - The dependencies on the EasyOCR package are minimal, making it easy to configure your OCR development environment.
   - Once EasyOCR is installed, only one import statement is required to import the package into your project.
   - From there, all you need is two lines of code to perform OCR — one to initialize the Reader class and then another to OCR the image via the readtext function.

## Project Overview
 
   In this Streamlit web app, you can upload an image of a business card and extract relevant information from it using EasyOCR. You can view, modify, or delete the extracted data in this app. This app also allows users to save the extracted information into a database along with the uploaded business card image. The database can store multiple entries, each with its business card image and extracted information.

   ## Libraries/Modules used for the project!

   - Pandas - (To Create a DataFrame with the scraped data)
   - sqlite - (To store and retrieve the data)
   - Streamlit - (To Create Graphical user Interface)
   - EasyOCR - (To extract text from images)
