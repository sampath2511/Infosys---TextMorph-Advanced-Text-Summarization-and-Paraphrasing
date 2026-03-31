# 🚀 TextMorph – Advanced Text Summarization & Paraphrasing Platform

>TextMorph is an AI-powered platform designed to simplify text through summarization, paraphrasing, and multilingual analysis with intelligent insights.

---

## 📌 Overview
TextMorph is a secure, scalable, and intelligent Natural Language Processing (NLP)-based web application developed to simplify complex textual information through advanced AI techniques. The system provides functionalities such as text summarization, paraphrasing, readability analysis, and multilingual support, all integrated into a single interactive platform.

The application is designed to assist students, researchers, and professionals in improving reading comprehension, reducing time spent on lengthy documents, and enhancing writing quality. It combines transformer-based deep learning models with secure backend systems to deliver accurate and efficient results.

The platform also incorporates user authentication, feedback systems, activity tracking, and an admin dashboard to ensure a complete end-to-end solution.



---

## 🎯 Objectives
To develop an AI-powered system capable of generating accurate summaries and paraphrased content
To provide readability analysis for evaluating text complexity
To design a secure authentication system for user data protection
To maintain user interaction history for future reference
To implement an admin dashboard for monitoring and analytics
To ensure scalability, usability, and deployment readiness

---

## ✨ System Features

### 🔐 Authentication & Security System
The system includes a robust authentication and security mechanism to ensure safe user interaction and data protection.

Users can register and log in using email and password
Passwords are securely stored using bcrypt hashing algorithm, preventing plaintext storage
Email-based OTP (One-Time Password) verification is implemented for secure password recovery
JWT-based session management ensures secure communication between frontend and backend
Password strength is enforced using regex validation (minimum length, special characters, etc.)
Login attempts are tracked, and rate limiting is applied to prevent brute-force attacks
Password reuse prevention is implemented using password history tracking
User accounts can be locked or unlocked by the admin

### 👤 User Dashboard
The user dashboard provides an interactive interface for accessing all NLP functionalities.

Users can input text manually or upload files in .txt and .pdf formats
The system processes input and displays results instantly
Users can access summarization, paraphrasing, and readability tools from a single interface
Generated outputs are displayed clearly with proper formatting
Users can view their past activity history
Users can submit feedback and ratings for generated results

### 📊 Readability Analysis Module
This module evaluates the complexity and readability of the given text using standard linguistic metrics.

Calculates multiple readability scores including:
Flesch Reading Ease Score
Flesch-Kincaid Grade Level
Gunning Fog Index
SMOG Index
Provides insights into:
Sentence length
Word complexity
Syllable count
Helps users understand how easy or difficult the text is to read
Visualizes results using charts and indicators for better interpretation

### 🤖 Text Summarization Engine
The summarization module uses transformer-based deep learning models to generate concise summaries.

Models used:
Pegasus (optimized for abstractive summarization)
BART (bidirectional transformer for sequence generation)
FLAN-T5 (instruction-tuned model for flexible summarization)
Supports different summary lengths:
Short
Medium
Long
Designed to handle long articles, academic content, and reports
Maintains contextual meaning while reducing content length


### ✍️ Paraphrasing Engine
The paraphrasing module rewrites text while preserving its original meaning.

Supports both sentence-level and paragraph-level paraphrasing
Enhances vocabulary and sentence structure
Displays original and generated text side-by-side for comparison
Ensures semantic consistency
Allows users to rate the output using a feedback system

### 🌐 Multilingual Support
The application supports multilingual text processing through integrated translation capabilities.

Uses NLLB (No Language Left Behind) translation support
Enables processing of text in multiple languages
Supports languages such as English, Hindi, Tamil, and others
Enhances accessibility for a wider range of users


### 🗂 Dataset Integration & Processing
The system leverages publicly available NLP datasets to improve model performance.

CNN/DailyMail dataset for summarization tasks
XSum dataset for abstractive summarization
PAWS dataset for paraphrasing and sentence similarity
These datasets help improve model understanding and output quality
Supports dataset-based preprocessing and evaluation

### 💬 Feedback System
A structured feedback system is implemented to evaluate model performance.

Users can provide ratings and comments on generated outputs
Feedback is stored along with:
Task type (summarization/paraphrasing)
Rating
Comments
Timestamp
Helps in analyzing system performance and user satisfaction


### 📜 Activity History Management
The system maintains a detailed record of user activities.

Tracks actions such as:
Text summarization
Paraphrasing
File uploads
Stores metadata including:
Model used
Timestamp
Activity details
Enables users to revisit and reuse previous results


## 👨‍💼 Admin Dashboard

👥 User Management
View all registered users
Promote users to admin role
Lock or unlock user accounts
Delete users from the system
📊 Analytics & Insights
Monitor system usage statistics
Analyze:
      Feature usage
      Model usage
      Language usage
Data is displayed using interactive charts
📡 Activity Monitoring
View all user activities across the platform
Search and filter activity logs
Inspect system-wide operations
📈 Feedback Analysis
Analyze collected feedback data
Generate WordCloud visualization for user comments
📤 Data Export
Export data including:
              User information
              Usage logs
              Feedback records
### 👥 User Management
- 
The system follows a layered architecture:

User → Frontend (Streamlit) → Backend (API Layer) → AI Model Layer → Database

Frontend handles user interaction and display
Backend manages API requests, authentication, and logic
AI layer processes NLP tasks
Database stores all persistent data

### 📈 Analytics & Insights
- Usage statistics

### 📡 Activity Monitoring
- Real-time tracking

### 📊 Feedback Analysis
- Sentiment analysis

### 📤 Data Export
- Export reports

---

## 🎨 UI/UX Design
Clean and modern user interface
Structured layout for better navigation
Interactive components for improved user experience
Designed to be responsive and user-friendly


---

## 🏗 System Architecture

The system follows a layered architecture:

User → Frontend (Streamlit) → Backend (API Layer) → AI Model Layer → Database

Frontend handles user interaction and display
Backend manages API requests, authentication, and logic
AI layer processes NLP tasks
Database stores all persistent data
---

## 🗄 Database Design
The application uses SQLite for data storage.

Tables:
Users
Password History
Login Attempts
Feedback
Activity History
Active Users
System Logs
Feature Usage
Usage Analytics
Key Functionalities:
Secure password storage
Tracking user activities
Managing feedback
Logging system events
Monitoring usage patterns




## 🛠 Tech Stack
Layer	Technologies
Frontend	Streamlit
Backend	Python
Security	JWT, bcrypt, OTP
NLP Models	Pegasus, BART, FLAN-T5
Libraries	Transformers, NLTK, Datasets
Database	SQLite
Visualization	Plotly, WordCloud
Deployment	ngrok


---

## Deployment

Deployed as a Streamlit web application
Public access enabled using ngrok
Google Drive integration for database persistence (optional)

##🔑 Environment Variables
EMAIL_USER
EMAIL_PASSWORD
NGROK_AUTHTOKEN
HF_TOKEN (optional)

## 🔒 Security Features

### Clone Repository
Password hashing (bcrypt)
JWT authentication
OTP verification
Input validation
Rate limiting
Secure session handling

## 📈 Logging & Monitoring

Tracks feature usage
Monitors active users
Logs system events
Maintains usage analytics

## 🔮 Future Scope
Docker containerization
Cloud deployment
Advanced role-based access
Real-time dashboards
Integration with advanced LLM APIs

## Conclusion
TextMorph is a comprehensive NLP-based platform that integrates AI-driven text processing with secure system design. The application successfully combines summarization, paraphrasing, readability analysis, and multilingual support into a unified system. With the inclusion of admin analytics, user tracking, and feedback mechanisms, the system demonstrates practical implementation of full-stack development and modern NLP techniques, making it suitable for real-world applications and future scalability.
## 📸 Screenshots
Login Page
<img width="1919" height="914" alt="image" src="https://github.com/user-attachments/assets/0b4eb83f-9011-4535-9d03-572229992eea" />

Summarizer
<img width="1912" height="912" alt="image" src="https://github.com/user-attachments/assets/b64aff57-99ea-452b-abd2-7195d0335c33" />

Paraphraser
<img width="1919" height="909" alt="image" src="https://github.com/user-attachments/assets/c6224f3a-08f7-4b4e-9256-0db64c855f18" />

Readability Analyzer
<img width="1915" height="914" alt="image" src="https://github.com/user-attachments/assets/68c1a2e5-a51f-477c-be18-ccf74e984125" />

Fine Tuning
<img width="1911" height="912" alt="image" src="https://github.com/user-attachments/assets/13565885-4464-4f50-af36-e82278a65d44" />

History
<img width="1919" height="915" alt="image" src="https://github.com/user-attachments/assets/4888a928-620d-45b2-8062-29bdb2e254bb" />

User Dashboard
<img width="1914" height="912" alt="image" src="https://github.com/user-attachments/assets/fa0e1c33-96a5-4519-bade-d5a0e6fa583b" />

f7
Admin Dashboard
<img width="1914" height="912" alt="image" src="https://github.com/user-attachments/assets/3c62dcb4-956d-43b3-aa14-923c9bf732b4" 
