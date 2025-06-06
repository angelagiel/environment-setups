# Python Installation

## Step 1: Download Python Installer
- Open your browser and go to the official Python website:
👉 https://www.python.org/downloads/
- Click Download Python (version number) (e.g., "Download Python 3.12.3").
- Save the .exe installer file.

## Step 2: Install Python Using the GUI (App Interface)
- Go to the folder where the installer was downloaded (usually Downloads).
- Double-click the installer to run it.
- On the first screen:
    - Check the box that says "Add Python X.X to PATH" (this is very important!).
    - Then click "Install Now".
- Wait for the installation to complete.
- Once installed, you should see a screen that says "Setup was successful".
    - Click "Close".

## Step 3: Verify Python and pip Installation via Command Prompt
- Press Win + R, type cmd, and hit Enter to open the Command Prompt.
- Check Python installation:
  
      python --version 
- You should see something like:
      
      Python 3.12.3 
- Check pip installation:    

      pip --version 
- You should see something like:  

      pip 24.0 from C:\Users\YourName\AppData\Local\Programs\Python\Python312\lib\site-packages\pip (python 3.12) 

  
## Step 4: Upgrade pip (Recommended)
- To get the latest features and security patches:  

      python -m pip install --upgrade pip 

## ❗For Troubleshooting: “Python is not recognized”
- If you get:  

      'python' is not recognized as an internal or external command 
- Then you need to add Python to your PATH manually
- How to Add Python to System PATH:
  - Press Win + S, search for "Environment Variables", and open it.
  - Under System Variables, find and select Path, then click Edit.
  - Click New, and add these (adjust the version as needed):
  
        C:\Users\YourName\AppData\Local\Programs\Python\Python312\ 
        C:\Users\YourName\AppData\Local\Programs\Python\Python312\Scripts\ 
- Click OK on all dialogs and restart Command Prompt.
