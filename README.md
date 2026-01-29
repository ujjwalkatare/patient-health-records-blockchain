🏥 Patient Health Records Management System
🔐 Blockchain Secured | 📱 QR Code Based | ⚕️ Role-Based Access
📌 Project Overview

This project is a secure patient health records management system built using Django, Blockchain (Ethereum), and QR Codes.
It ensures data integrity, transparency, and tamper-proof medical records.
Each update to patient data is:

Cryptographically hashed
Stored on blockchain (Ganache / Ethereum)
Embedded inside a QR code for instant verification

🚀 Key Features
👤 User Roles
Admin
Doctor
Patient

🔐 Security & Blockchain

SHA-256 hashing of medical records
Ethereum Smart Contract integration
Immutable blockchain record storage
Transaction hash stored for verification

📱 QR Code System

QR contains:
Blockchain hash
Transaction hash
Latest medical record
Previous history
Doctors can scan & verify authenticity instantly

🧑‍⚕️ Doctor Module

Accept / reject patient requests
Add visit records, diagnosis & prescriptions
Auto-update blockchain hash
Send verified updates to patients

🧑‍🤝‍🧑 Patient Module

View dashboard with QR code
Track visit history
Receive doctor updates & notifications
Request doctors securely

🛠 Admin Module

Manage doctors & patients
Edit patient records (with blockchain versioning)
View appointments & analytics

🧠 Technologies Used

Backend: Django (Python)
Frontend: HTML, CSS, Bootstrap
Blockchain: Ethereum (Ganache)
Smart Contract: Solidity

QR Codes: Python qrcode

Hashing: SHA-256
Database: SQLite
Web3: Web3.py

🔗 How Blockchain is Used

![Uploading bt_health_record.png…]()

Every patient update generates a new hash
Hash is stored on Ethereum blockchain
Any data tampering changes the hash
QR scan verifies data authenticity

📸 Screens & Workflow

Admin Dashboard
Doctor Dashboard
Patient Dashboard
QR Scan & Hash Verification
Blockchain Transaction Logs

🎯 Use Cases

Hospitals
Clinics
Medical Record Security
Healthcare Auditing
Academic Blockchain Projects

👨‍💻 Developed By

Ujjwal
Aspiring Full Stack & Blockchain Developer
