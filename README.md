# 🎓 EduChain – Blockchain-Based Certificate Verification System

EduChain is a blockchain-powered certificate issuance and verification system designed for educational institutions. This decentralized web application ensures that once a certificate is issued, it is tamper-proof, publicly verifiable, and stored securely on a custom blockchain built using JavaScript.

This project was developed as part of the IBM Blockchain Certification Course and serves as a practical implementation of decentralized trust in academic record management.

## 🚀 Features

- Web UI for institutions to issue academic certificates
- Public interface for verifying certificate authenticity
- Tamper-proof data using cryptographic SHA256 hashing
- Blockchain chaining logic with block validation
- REST API integration for frontend-backend communication
- Optional Docker support for standardized deployment

## 🛠️ Technologies Used

Node.js        – Backend server and logic  
Express.js     – API routing and middleware  
JavaScript     – Custom blockchain, frontend interactivity  
HTML & CSS     – Basic UI layout  
Tailwind CSS   – Responsive modern styling  
Crypto-js      – SHA256 hashing for blockchain security  
Docker         – (Optional) Containerization

## 🔧 How to Run This Project

### Local Development Setup

1. Clone the repository  
   `git clone https://github.com/techynAR/EduChain.git`  
   `cd educhain`

2. Install dependencies  
   `npm install`

3. Run the development server  
   `npm run dev`

4. Access the frontend  
   Add Certificate: http://localhost:3000/frontend/addCertificate.html  
   Verify Certificate: http://localhost:3000/frontend/verifyCertificate.html  
   Blockchain JSON Output: http://localhost:3000/api/getBlockchain

### Docker Deployment (Optional)

1. Build Docker image  
   `docker build -t educhain .`

2. Run Docker container  
   `docker run -p 3000:3000 educhain`

## 🔗 Connect

Developed by Aryan Sharma  
LinkedIn: https://www.linkedin.com/in/aryan-sharma-techynar/
