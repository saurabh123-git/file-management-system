# File Organizer GUI with Tkinter

## Project Description

This is a simple Python application with a graphical user interface (GUI) built using `tkinter`. The program organizes files in a selected directory by sorting them into subfolders based on their file types such as PDFs, text files, images, media files, and miscellaneous others. It also keeps a log of moved files.

## Features

- GUI-based input for directory path using `tkinter`
- Automatically categorizes files into:
  - `pdf_files`
  - `text_files` (`.txt`, `.html`, `.c`, `.py`, `.docx`)
  - `images` (`.jpg`, `.png`)
  - `miscs` (`.mp4`, `.mkv`, `.mp3`)
  - `others` (everything else)
- Creates subdirectories as needed
- Moves files into appropriate folders
- Logs all moved files in `output.txt`
- Stores the input directory path in `path.txt`
- Displays output log in the GUI

## How to Use

1. Run the script using a Python interpreter:
   ```bash
   python file_organizer.py
