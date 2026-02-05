# Python Text-to-PDF Automation Tool
This project is a Python-based script that converts a `.txt` file into a `.pdf` file.  
The script accepts both absolute and relative file paths, reads the content of the text file, and generates a formatted PDF file in the same directory using the **ReportLab** library.

## Features
- Converts `.txt` files to `.pdf`
- Validates file path and file extension before processing
- Supports absolute and relative file paths as input
- Automatically saves the PDF in the same directory as the text file
- Adds page numbers to the generated PDF

## Technologies Used
- Python  
- ReportLab(for PDF generation)  
- OS module(for path handling and validation)  
- File Handling(read/write operations)  

## 📌 How It Works
1. User provides the path of a `.txt` file.
2. The script checks:
   - Whether the path exists  
   - Whether the file extension is `.txt`
3. The text file is read line by line.
4. Paragraphs are detected and formatted properly.
5. The content is written into a PDF using ReportLab.
6. The PDF is saved in the same directory as the text file.

