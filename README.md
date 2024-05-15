# Python File Format Converter
The Python File Format Converter is a versatile script that allows users to convert files between different formats, including PDF, DOCX, MP3, PPTX, and HTML. Whether you need to convert a PDF document to a DOCX file, extract audio from an MP4 video, or create a PDF from an HTML file, this script has got you covered.

## Features:
Multiple Conversion Options: Users can choose from a variety of conversion options, including:

-PDF to DOCX
-DOCX to PDF
-MP4 to MP3
-PDF to PPTX
-PPTX to PDF
-HTML to PDF
-PDF to HTML

Simple User Interface: The script provides a simple command-line interface where users can select their desired conversion option and provide input file names.

## How to Use:
Installation: Ensure you have Python installed on your system. If not, download and install it from python.org.

Download the Script: Clone or download the Python file format converter script to your local machine.

Run the Script: Open a terminal or command prompt, navigate to the directory containing the script, and execute it using Python:
```
python main.py
```
Follow Prompts: The script will display a menu with available conversion options. Choose the desired option and provide input file names when prompted.

Conversion Complete: Once the conversion is complete, the script will display a success message indicating the output file name.

## Requirements:
PyPDF2: Library for working with PDF files in Python.
python-docx: Library for working with DOCX files in Python.
moviepy: Library for working with video files in Python.
pdf2pptx: Library for converting PDF files to PPTX presentations.

Install dependencies using pip:
```
pip install -r requirements.txt
```

## Security Considerations:
Be cautious when converting files from untrusted sources, as they may contain malicious content.
