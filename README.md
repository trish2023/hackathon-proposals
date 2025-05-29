# hackathon-proposals
# 1. Multilingual AI Loan Assistant

A hackathon project proposal for an AI-powered chatbot that assists users in **loan eligibility checks**, **financial guidance**, and **loan applications** via **WhatsApp**.

## Key Features
- **Multilingual AI**: Uses **Sarvam.ai** for translation.
- **Loan Eligibility**: NLP-powered intent detection (DistilBERT) with rule-based/API assessment.
- **Alternative Credit Scoring**: Analyzes transaction patterns for users without credit scores.
- **Secure & Scalable**: End-to-end encryption (E2EE), WebSockets for real-time updates, and Kafka for async processing.
- **Loan Matching & Assistance**: Personalized loan suggestions and guidance on documentation.

## Workflow Overview
1️⃣ User starts chat & selects language.
2️⃣ NLP extracts intent (eligibility, guidance, financial insights).
3️⃣ Data fetched via input, APIs, or Account Aggregator (AA).
4️⃣ Computes credit score & loan eligibility.
5️⃣ Suggests loan options & next steps.

# 2. SmartAttendanceSystem 

### Coded in Python, includes seamless integration with Amazon Rekognition, Amazon S3, and AWS Lambda. Utilises a Raspberry Pi to capture real-time attendance. 

The Smart Attendance System for Classroom is a solution designed to streamline attendance tracking and enhance identification processes using facial recognition technology. This system offers seamless integration with Amazon Rekognition, Amazon S3, and AWS Lambda, ensuring efficient and secure image processing and storage



## Why is this even a need? 

Assuming there are 260 working days in a year, 4 classes per day, and 5 minutes required for attendance in each class it takes us a whopping 5200 minutes per year for just attendance. That is **86.7 hours wasted on just roll call**

## How does it work? A tech dive 
![image](https://github.com/trish2023/SmartAttendanceSystem/assets/136291896/0fc202bc-6d3a-44b4-b517-81ce942a529b) 

## Tools 
# S3 Bucket 
Amazon S3 (Simple Storage Ser  vice) is a scalable object storage service provided by Amazon Web Services (AWS). An S3 bucket is essentially a container for storing objects, which can include anything from text files to images to application binaries. Here are the key points about S3 buckets:

 <u> Event driven Architecture - Lambda </u>
 
Lambda, in the context of computing and cloud services, often refers to AWS Lambda, which is a serverless computing service provided by Amazon Web Services (AWS). Here's a brief explanation:
# AWS Lambda:
* Definition: AWS Lambda is a serverless computing service that allows you to run code without provisioning or managing servers. It automatically scales and 
              manages the compute resources needed to run your code in response to events, such as changes to data in an Amazon S3 bucket or an update to a 
              DynamoDB table.



## 🛠️ Proposed Tech Stack
- **Frontend**: React.js + Next.js, WhatsApp UI (via Twilio API).
- **Backend**: Express.js, WebSockets, Kafka, DistilBERT, Sarvam.ai.
- **Security**: Firebase (encrypted storage), E2EE chat security.

📌 *This is a hackathon project proposal and has not been implemented yet.*
