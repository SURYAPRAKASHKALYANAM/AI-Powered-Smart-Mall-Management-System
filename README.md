# AI-Powered Smart Mall Management System 🏬🤖📊🛍️

Welcome to the AI-Powered Smart Mall Management System project repository! 🌟

## Project Overview

In today's highly competitive retail landscape, understanding customer behavior and preferences is essential for businesses to stay ahead. 

This project relates to an artificial intelligence system and method for smart mall management, focusing on business forecasting and security. The recommended system identifies and quantifies the types of customers, providing details of actual customer footprints for each outlet. 
By analyzing customer data, the system provides insights into foot traffic and customer behavior for each outlet or store within the mall. This data enables traders and store owners to plan their inventory effectively, ensuring appropriate stock levels.

With this information, businesses can make more accurate predictions about customer demand, optimize their supply chain, and avoid stockouts or overstocking situations.

## Methodology

Our methodology consists of four modules:

### 1. Parallel Camera Input Reading Using Multi-Processing
   - Description: This module handles the parallel input reading from cameras using multi-processing for efficient data collection.

### 2. Yolov-8 For Face Detection In Input Frames
   - Description: Yolov-8 is employed for face detection in the input frames to track customer movements.

### 3. Face Encoding Generation and Comparison
   - Description: This module generates and compares face encodings to identify and quantify customer types.

### 4. Customer Analytics
   - Description: The final module performs customer analytics and provides insights into foot traffic and behavior for each outlet or store.

# DEMO 

## UI  
###  1. Login & REGISTER
   - ![register](https://github.com/user-attachments/assets/505c49d1-cab1-4851-a8de-dd10f9239e9c)
   - ![login](https://github.com/user-attachments/assets/4e6f9072-a58f-460d-90d5-9fbb270c236e)

### 2. USER DASHBOARDS 
   - ![dash-1](https://github.com/user-attachments/assets/95652984-fc21-4247-9b72-96f548132f5b)
   - ![dash-2](https://github.com/user-attachments/assets/acfd0563-2f75-4d31-860a-00eb390e1a89)
### 3. ADMIN DASHBOARD 
   - ![admin dash](https://github.com/user-attachments/assets/ec7d10b1-fbfe-47f4-bcf1-c24e8f7fd363)
### UI WALKTHROUGH 
   https://github.com/user-attachments/assets/fbdbf083-3984-42ff-8ac6-015d2c00ef48

## BACKEND
### 1. APIS 
   - ![fast-apis](https://github.com/user-attachments/assets/8b33db5a-5c33-4818-93dd-a6283dcd6e1d)

### 2. DATABASE SCHEMA 
   - Mall_DATA Stores Details of persons and has 6 attributes
       - UNIQUE ID - An ID assigned to each person
       - FACE_ENCODINGS - Facial Encodings of each person
       - CAMERA_ID - List of camera Id's which shows the path that person followed or stalls visited by user.
       - TIMESTAMP - Timestamp for each camera entry for the id in camera id's which shows , at what time the user came to specific stall.
       - CURRENT_CAMERA - At which stall the user is currently present.
       - EXIT_STATUS - Tells whether the user exits from the mall or not.
         
         ![mall_data db](https://github.com/user-attachments/assets/dc84025a-ead6-4767-87e8-9a376a38b128)

   - Users store details of application users.
        - user email and password were stored
          
          ![user db](https://github.com/user-attachments/assets/3fdcae0a-ec0f-4540-a26d-7679b3a229db)

### Usage

To use this smart mall management system, follow these steps:



1. Commands to run:
   ```bash
   FAST-API - python -m uvicorn main:app --reload
   Python - python app.py
   React - 
   npm install
   npm run dev
   
## Demo
https://github.com/user-attachments/assets/1b78bd31-ffc9-4491-9b97-4a6ff5cab941

-It has two camera inputs and reads two inputs parallelly using multi-processing.
- the predicted faces in both cameras are saved in the yolo-outputs folder
     - ![yolo output](https://github.com/user-attachments/assets/db7da8ed-9213-43e6-afd1-bea1d7a837b1)
- unique faces will be stored in predicted output
     - ![predicted output](https://github.com/user-attachments/assets/df803f2a-73b5-4fc4-9cbd-00a0309c0eb2)





   
