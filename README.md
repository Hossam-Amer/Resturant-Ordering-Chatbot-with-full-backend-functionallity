# 🍽️ Restaurant Ordering Application

## Overview
This is a smart restaurant ordering system powered by **Dialogflow**, **FastAPI**, and **MySQL**. The system allows users to place, edit, and track their orders through a conversational interface while managing real-time order updates in the database.

## Features
- 🗣️ **Conversational Ordering**: Users can order meals using natural language processing (NLP) powered by Dialogflow.
- 📝 **Edit Orders**: Modify orders before they are confirmed.
- 📦 **Order Tracking**: Check the status of an order in real-time.
- 🗄️ **Database Integration**: Orders are stored and managed in a MySQL database.
- 🚀 **Fast & Scalable API**: Uses FastAPI for quick and efficient backend operations.

## Technologies Used
- **Dialogflow** - Conversational AI for handling user interactions
- **FastAPI** - High-performance API framework
- **MySQL** - Relational database for storing order details

- **ngrok** - Expose local API for Dialogflow integration (optional)

Demo
================================
<div style="display: flex; gap: 20px;">
    <video width="auto" height="auto" src="https://github.com/user-attachments/assets/e83af307-995b-4c6c-8207-7bf4ca13c653" style="border: none;"></video>|<img src="https://github.com/user-attachments/assets/e8c754d9-4dc6-4f4e-a0a5-4651363c9fd2" alt="Image" style="width: auto; height: auto;">
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

