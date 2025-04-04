# ScoreMe
Detecting and Extracting Tables from PDFs
Overview

This is a GUI-based Python application that extracts tables from PDF files and converts them into Excel spreadsheets. The program is built using pdfplumber and pandas for table extraction and data manipulation, and it provides a user-friendly interface using PyQt5 and Tkinter.

Features

Extracts tables from PDF documents and ignores plain text.
Uses pdfplumber to extract tabular data.
Converts extracted tables into structured Excel files.
Supports different table extraction strategies.
Enables users to select a directory of PDFs for batch processing.
And successful conversion is there.

Prerequisites

Ensure you have Python installed. You also need to install the following dependencies:
-> pip install pdfplumber pandas PyQt5 xlsxwriter

How to Use

Run the script by executing the following command:
python script.py
A GUI window will appear with instructions.
Click the button to select a directory containing PDF files.
Choose extraction strategies for vertical and horizontal table parsing.
The program will process the PDFs and save extracted tables as Excel files in the same directory.
After completion, you will be prompted to open the output directory.
