# Medical-Diagnosis-Extraction
**Team : Kartavya**

**Pitch Desk** - https://www.canva.com/design/DAGROIYa62w/GA4Q-5vdEh4UoTTLqqz14g/edit?utm_content=DAGROIYa62w&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

## 1. Introduction :
- This project is to implement medical data extraction, and this project will auto classify and extract useful information from medical forms and documents.
- Implemented this project by using libraries - Pytesseract(Runs On Google Optical Character Recognition-OCR), Computer Vision, Regex, PDF2Image, Pytest.
- At first we use PDF2Image library to convert PDF into image, clean the image with Computer Vision by Adaptive Thresholding Techinique and extract useful data by using Pytesseract(OCR) and regex.
- This project works well on medicalcare documents(like extracting name, patient details, medicine, diagonosis) and this saves time as it reduces human work and saves time from 10 min to less than a second.

## System Design
![system design](https://github.com/user-attachments/assets/bef32bb2-a86a-4df9-981c-24e2155403d0)

## Workflow
![data flow](https://github.com/user-attachments/assets/b3771cd0-de0a-4660-b7db-1668dfad7fb3)

## Technologies used
- Python
- Pdf2image module
- Opencv
- pytesseract
- Regular expression
- RAG Model
- LLM
- Postman
- FastApi


