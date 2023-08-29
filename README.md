# **DS-BizCardX**
A Streamlit application that allows users to upload an image of a business card and extract relevant information from it using easyOCR.

## What is EasyOCR?
EasyOCR, as the name suggests, is a Python package that allows computer vision developers to effortlessly perform Optical Character Recognition.It is a Python library for Optical Character Recognition (OCR) that allows you to easily extract text from images and scanned documents. In my project I am using easyOCR to extract text from business cards.

When it comes to OCR, EasyOCR is by far the most straightforward way to apply Optical Character Recognition:

The EasyOCR package can be installed with a single pip command. The dependencies on the EasyOCR package are minimal, making it easy to configure our OCR development environment. Once EasyOCR is installed, only one import statement is required to import the package into our project. From there, all we need is two lines of code to perform OCR — one to initialize the Reader class and then another to OCR the image via the readtext function.

### Project Overview*

BizCardX is a user-friendly tool for extracting information from business cards. The tool uses OCR technology to recognize text on business cards and extracts the data into a SQL database after classification using regular expressions. Users can access the extracted information using a GUI built using streamlit. The BizCardX application is a simple and intuitive user interface that guides users through the process of uploading the business card image and extracting its information. The extracted information would be displayed in a clean and organized manner, and users would be able to easily add it to the database with the click of a button. Further the data stored in database can be easily Read, updated and deleted by user as per the requirement.

### Approach:*

1. Installation of the required packages: First we will need to install Python, Streamlit, easyOCR, and a database management system like SQLite or MySQL. 
2. Design of the user interface: Creating a simple and intuitive user interface using Streamlit that guides users through the process of uploading the business
card image and extracting its information. We have used widgets like fileuploader, buttons, and text boxes to make the interface more interactive.
3. Implement the image processing and OCR: Using easyOCR to extract the relevant information from the uploaded business card image we have used
image processing techniques like resizing, cropping, and thresholding to enhance the image quality before passing it to the OCR engine.
4. Displaying the extracted information: Once the information has been extracted, we have displayed it in a clean and organized manner in the Streamlit GUI. We also have used widgets like tables, text boxes, and labels to present the information.
5. Implementation of database integration: Using a database management system like MySQL to store the extracted information along with the uploaded
business card image, we have used SQL queries to create tables, insert data, and retrieve data from the database, Update the data and Allow the user to
delete the data through the streamlit UI
