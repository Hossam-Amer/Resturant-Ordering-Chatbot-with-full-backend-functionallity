
Demo
================================
<div style="display: flex; gap: 20px;">
    <video width="auto" height="auto" src="https://github.com/user-attachments/assets/568fdf1e-7365-4bab-9768-8ae18534f434" style="border: none;"></video>|<img src="https://github.com/user-attachments/assets/a690f1bb-c288-4abd-be75-bc1c7f312eda" alt="Image" style="width: auto; height: auto;">
</div>


Directory structure
================================
backend: Python FastAPI backend code
db: Contains the dump of the database. you need to import this into your MySQL db by using MySQL workbench tool

================================
run pip install -r backend/requirements.txt to install both in one shot

To start fastapi backend server
================================
1. Go to backend directory in your command prompt
2. Run this command: uvicorn main:app --reload

ngrok for https tunneling
================================
1. To install ngrok, go to https://ngrok.com/download and install ngrok version that is suitable for your OS
2. Extract the zip file and place ngrok.exe in a folder.
3. Open windows command prompt, go to that folder and run this command: ngrok http 8080

