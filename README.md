## OCRecognizer
##
### OCRecognizer is a desktop program for Windows that lets you extract text from images and PDF files
##
### Download OCRecognizer
[Windows](https://drive.google.com/file/d/1YPHSKaxGdxXXoxLuVRZSmreSB07CXkJD/view?usp=sharing)
   64 bits installer
##
### Install Tesseract-OCR on Windows


https://github.com/UB-Mannheim/tesseract/wiki


Go to the official Tesseract-OCR website at https://github.com/UB-Mannheim/tesseract/wiki and download the latest version for the
Windows. It is recommended that you choose the latest version available with the "-win64-setup.exe" suffix if your operating system
is 64-bit, or "-win32-setup.exe" if 32-bit.

Once downloaded, run the installer by double-clicking the ".exe" file and follow the on-screen instructions to complete the installation.
It is recommended that you leave all settings at default during installation.

After completing the installation, add the Tesseract-OCR installation path to the "PATH" environment variable. To do this, follow
the following steps:

     Click the Start button and type "Environment Variables" in the search box.
     Select the "Edit the environment variables for this account" option.
     Click the "Environment Variables" button.
     In the "System variables" section, select the "PATH" variable and click "Edit".
     Click "New" and add the Tesseract-OCR installation path to the end of the list.
For example, if Tesseract-OCR is installed in "C:\Program Files\Tesseract-OCR",
add ";C:\Program Files\Tesseract-OCR" to the end of the list.
     Click "OK" to save the changes.


Download languages from:

https://github.com/tesseract-ocr/tessdata

Save to C:\Program Files\Tesseract-OCR\tessdata

