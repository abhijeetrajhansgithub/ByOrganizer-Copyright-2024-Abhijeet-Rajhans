# ByOrganizer-Copyright-2024-Abhijeet-Rajhans
This application is meticulously crafted to deliver a contemporary and user-friendly interface, catering to a diverse range of tasks. Developed with Python and PyQt5, it boasts a sophisticated architecture that ensures seamless performance and intuitive user interaction.

This README file will guide you through the installation process on Windows.

# Prerequisites
Before you begin, ensure you have the following installed on your system:

* Python 3.x: Download Python
* PyQt5: Install using pip: `pip install pyqt5`
* WinRAR: Download and install WinRAR from the official website: https://www.rarlab.com/download.htm

# Installation Steps
Follow these steps to install and run the app:

1. Clone the Repository:
`git clone https://github.com/abhijeetrajhansgithub/ByOrganizer-Copyright-2024-Abhijeet-Rajhans.git`

2. Navigate to the Project Directory:
`cd ByOrganizer-Copyright-2024-Abhijeet-Rajhans`

3. Run the Installer:
Locate the installer file (ByOrganizer.exe) in the dist directory.

4. Double-click the installer to run it.
Once the installation is complete, you can run the app from the Start Menu or Desktop shortcut.
Alternatively, you can run the app from the command line:
`python ByOrganizer.py`

# Handling Split Archive Volumes
If your app's installer is split into multiple volumes, follow these steps to extract the installer:

1. Ensure All Volumes Are in the Same Directory:
      * Make sure all split archive volumes (installer.part1.rar, installer.part2.rar, etc.) are located in the same directory.
  
2. Select all split archive volumes
3. Right-click and open WinRAR
4. Choose **"Extract Here"** or **"Extract to [folder name]"** from the context menu.
5. WinRAR will begin extracting the files from the split archive volumes.
6. Once the extraction is complete, the installer file (**ByOrganizer.exe**) is in the extraction directory.


## More Documentation
1. **Python**: Ensure you have Python installed on your system. You can download it from [python.org](https://www.python.org/).
2. **Tkinter**: Tkinter is included with most Python installations. If it's not installed, you can install it using the following command:
    ```sh
    pip install tk
    ```
3. **WinRAR**: Ensure WinRAR is installed on your system. You can download it from [rarlab.com](https://www.rarlab.com/download.htm). WinRAR must be in your system PATH. If it's not, follow the instructions below to add it.

## Adding WinRAR to System PATH
If WinRAR is not recognized as an internal or external command, you need to add it to your system PATH.

1. **Check if WinRAR is installed**:
   - Default installation directory: `C:\Program Files\WinRAR`
   - If it's installed in this directory, follow the next steps to add it to the PATH.

2. **Add to PATH**:
    - Open the Start Search, type in "env", and select "Edit the system environment variables".
    - Click the "Environment Variables" button.
    - In the System variables section, find the `Path` variable and click "Edit".
    - Click "New" and add the path to the WinRAR installation directory (e.g., `C:\Program Files\WinRAR`).
    - Click "OK" to save and close all windows.

3. **Install WinRAR using winget** (if WinRAR is not installed):
    - Open Command Prompt as an administrator and run:
      ```sh
      winget install winrar
      ```

## Installation Instructions
1. **Download the Project**: Clone the repository or download the ZIP file and extract it to a directory on your computer.

2. **Download the Split RAR Files**: Ensure you have all the split RAR files required for the application. These files should be named starting with "ByOrganizer" and you should have exactly 8 files.

3. **Run the Merge and Extract Script**:
    - You can either use the provided Tkinter app or do it manually.

### Using the Tkinter App
1. **Run MergeWinRAR.exe**: This executable will automatically merge and extract the split RAR files.
    - Ensure all split RAR files are in the same directory as `MergeWinRAR.exe`.
    - Run `MergeWinRAR.exe`.
    - The merged and extracted files will be placed in a new directory called `extracted_files`.

### Manual Extraction Using WinRAR
1. **Open WinRAR**:
    - Navigate to the directory containing the split RAR files.
    - Select the first file (e.g., `ByOrganizer.part1.rar`).
    - Right-click and choose "Extract here" or "Extract to <folder name>".
    - WinRAR will automatically merge the parts and extract the files.

## Running the Application
Once the extraction process is complete, navigate to the `extracted_files` directory and run the main executable of your PyQt5 application.

===================================================================================================
===================================================================================================

### License
    This application is proprietary software and is protected by copyright law. Your use of this software is subject to the terms of the proprietary license agreement provided with the software.
    
    1. You are granted a non-exclusive, non-transferable license to use this application for personal or commercial purposes, subject to the terms of the proprietary license agreement.
    2. Redistribution or modification of the application is strictly prohibited without prior written consent from the author.
    3. Agree not to distribute the application illegally or without this complete section of the about clause.
    4. The author must approve any modifications or enhancements made to the application.
    5. The author shall not be liable for any damages or losses arising from the use or inability to use the application.

### Contact
    * Author: Abhijeet Rajhans
    * Developed By: Abhijeet Rajhans
    * Github: https://github.com/abhijeetrajhansgithub
    * Linkedin: https://www.linkedin.com/in/abhijeetrajhans/

# **Copyright © 2024 Abhijeet Rajhans**

