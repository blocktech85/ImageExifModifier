# ExifTool GPS & Metadata Setter

A user-friendly PyQt6 desktop application for batch editing image metadata and GPS geotags using the powerful [ExifTool](https://exiftool.org/) command-line utility by Phil Harvey, and upgraded as well as UI friendly GUI created by Jordan Smith of Growthkey.tech

---

## Overview

This application provides an intuitive graphical interface to select images or entire folders, specify GPS coordinates, orientation, timestamps, copyright, and additional metadata fields. Using ExifTool in the background, it applies changes efficiently across multiple files.

### Key features:
- Select individual images or complete folders (optionally recursive)
- Enter GPS latitude, longitude, and altitude metadata
- Edit EXIF orientation codes, date/time original, create, and modify fields
- Add copyright, artist, keywords, titles, and subjects metadata
- Preview selected images with enlarged icons (160x160 pixels)
- Real-time console logging of ExifTool command and output
- Progress bar indicating batch processing status
- Stylized **Apply Metadata** button (neon green, bold, 50% larger font, unique font)
- Tooltips on main sections for ease of use

---

## Installation & Requirements

- Python 3.8 or newer
- [PyQt6](https://pypi.org/project/PyQt6/)
- ExifTool executable (`exiftool.exe`) by Phil Harvey

### ExifTool Download and Credit

ExifTool, developed and maintained by Phil Harvey, is a widely respected and robust metadata manipulation tool.  
The original ExifTool executable used by this app can be downloaded freely from the official website:  
[https://exiftool.org/](https://exiftool.org/)

Please ensure `exiftool.exe` is downloaded from the official source and placed in the configured application folder.

---

## Usage

1. Download and place `exiftool.exe` in the specified `Change Image EXIF+Geotag` folder or adjust the path in the script accordingly.
2. Install PyQt6 via pip if not installed:
3. Run the PyQt6 application script:
4. Use the **Select Images or Folder** button to choose files.
5. Fill in desired GPS, date/time, orientation, copyright, and descriptive metadata.
6. Click the **Apply Metadata** button to process all selected files.
7. Monitor the progress bar and console log output for success or error messages.
8. Optionally save the log output to a text file.

