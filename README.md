ExifTool GPS & Metadata Setter
A user-friendly PyQt6 desktop application for batch editing image metadata and GPS geotags using the powerful ExifTool command-line utility.

Overview
This app provides an intuitive graphical interface to select images or entire folders, specify GPS coordinates, orientation, timestamps, copyright info, and other metadata fields. The program leverages ExifTool in the background to apply the changes efficiently and reliably across multiple files.

Key features:

Select individual images or folders (with optional recursive folder scanning)

Set GPS latitude, longitude, and altitude metadata

Edit EXIF orientation codes, date/time original and modified fields

Add copyright, artist, keywords, titles, and subjects

Preview selected images at twice normal icon size

Real-time console logging of ExifTool command and output

Progress bar updates during batch processing

Styled "Apply Metadata" button with larger font and neon green highlight

Tooltips on key sections for user guidance

Installation & Requirements
Python 3.8 or above

PyQt6

ExifTool executable (exiftool.exe) must be downloaded and placed in the specified folder:

Download from ExifTool official site. ExifTool by Phil Harvey is the recognized and widely trusted metadata editing toolkit used in this app.

Recommended to install PyQt6 via pip:

bash
pip install pyqt6
Usage
Run the Python script:

bash
python exiftool_gps_app.py
Use Select Images or Folder button to load image files.

Enter GPS data, orientation, date/time, and other metadata fields as needed.

Click the Apply Metadata button to process files.

Monitor the logging area for detailed ExifTool output.

Optionally save the log to a file.

Credits
ExifTool - Metadata editing backend by Phil Harvey. Learn more and download at https://exiftool.org/

GUI and application logic developed with PyQt6.
