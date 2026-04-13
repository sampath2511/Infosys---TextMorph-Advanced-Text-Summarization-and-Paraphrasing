## 🧠 Milestone 4 – Advanced Admin Dashboard & AI Platform Enhancements  
---

## 📖 Project Overview  
This project is an AI-powered text processing platform that combines advanced Natural Language Processing (NLP) models with a secure authentication system and interactive dashboards. It enables users to perform tasks such as text summarization, paraphrasing, readability analysis, and AI-driven chat interactions through a modern web interface. :contentReference[oaicite:0]{index=0}  

Milestone 4 builds upon previous implementations by introducing an advanced Admin Dashboard, enhanced user personalization, analytics visualization, and feedback analysis features. :contentReference[oaicite:1]{index=1}  

The system is designed to be secure, scalable, and user-friendly, providing an efficient environment for AI-based text processing. :contentReference[oaicite:2]{index=2}  

---

## 🚀 Key Features Implemented  
---

## 🔐 Secure Authentication System  
The platform includes a strong authentication mechanism to ensure user security and controlled access.  

**Features include:**  
- User registration and login system  
- Password hashing using bcrypt  
- JWT-based authentication  
- Email OTP verification for password recovery  
- Security question validation  
- Login rate limiting to prevent brute-force attacks  
- Password history tracking  

---

## 🛡 Admin Dashboard (Management & Analytics)  
The Admin Dashboard serves as a central control panel for managing users and monitoring system activity.  

---

### 👥 User Management  
Administrators can manage user accounts effectively.  

- Promote users to admin roles  
- Lock or unlock accounts  
- Delete users  
- View user details and registration data  

---

### 📊 Activity Monitoring  
The system provides real-time insights into platform usage.  

- Track active users  
- Monitor system activity  
- View historical logs of user actions  

---

### 📈 Data Visualization  
Interactive charts help analyze application usage.  

- Most frequently used AI models  
- User language preferences  
- Popular platform features  

Charts are generated using Plotly for better visualization.  

---

### 💬 Feedback Analysis  
User feedback is analyzed to improve the system.  

- Feedback trend analysis  
- WordCloud visualization for common keywords  
- Insights into user satisfaction  

---

### 📥 Data Export  
Admins can export system data for reporting purposes.  

- User data export  
- Activity logs export  
- Feedback dataset export  

---

## 👤 User Dashboard & Personalization  
The user dashboard provides a customized and interactive experience.  

---

### ⚙ Profile Management  
Users can manage their personal information.  

- Update email address  
- Change password  
- Upload or modify profile picture  

---

### 🎨 Personalized Experience  
Enhancements for better usability include:  

- Improved navigation  
- Personalized dashboard view  
- Clean and modern UI  
- Responsive design  

---

## 🤖 AI Modules Integrated  
The platform integrates multiple NLP functionalities.  

---

### 📑 Text Summarization  
Generates concise summaries from long text inputs.  

**Models used:**  
- BART  
- PEGASUS  
- FLAN-T5  

---

### ✏️ Paraphrasing Engine  
Rewrites text while preserving original meaning.  

**Model used:**  
- T5 Transformer  

---

### 📊 Readability Analyzer  
Evaluates text complexity using standard metrics.  

**Metrics include:**  
- Flesch Reading Ease  
- Flesch-Kincaid Grade Level  
- SMOG Index  
- Gunning Fog Index  
- Coleman-Liau Index  

---

## 🧪 Dataset Augmentation & Model Optimization  
To enhance model performance, dataset augmentation techniques were applied.  

**Techniques used:**  
- Synonym replacement  
- Random word deletion  
- Sentence shuffling  
- Paraphrase-based augmentation  

Models were further optimized using fine-tuning and quantization (4-bit / 8-bit) to improve efficiency and reduce memory usage.  

---

## 🛠 Technologies Used  
---

### Backend  
- Python  
- PostgreSQL  
- JWT Authentication  
- bcrypt Security  

### AI / NLP  
- Transformers  
- PyTorch  
- NLTK  

### Frontend  
- Streamlit  
- Plotly  
- Custom CSS  

### Additional Libraries  
- PyPDF2  
- WordCloud  
- pandas  
- numpy  

---

## 📁 Project Structure  
```
Milestone4
│
├── Milestone4_finaldemo.ipynb
├── requirements.txt
├── README.md
```

---

## ▶️ Setup & Installation  
---

### Step 1 – Install Dependencies  
```bash
pip install -r requirements.txt
```

### Step 2 – Configure Environment Variables  
Create a `.env` file and add:  

```
EMAIL_ADDRESS=your_email
EMAIL_PASSWORD=your_email_password
JWT_SECRET=your_secret_key

DB_NAME=database_name
DB_USER=postgres
DB_PASSWORD=postgres
DB_HOST=localhost
DB_PORT=5432
```

### Step 3 – Run the Application  
```bash
streamlit run app.py
```

The application will open in your browser.  

---

## 📸 Screenshots  
(Add your application screenshots here)  

---

## 📌 Conclusion  
Milestone 4 demonstrates a complete integration of secure authentication, AI-powered text processing, advanced analytics, and interactive dashboards into a unified platform.  

The system delivers powerful NLP tools with a user-friendly interface, while the admin dashboard enables efficient monitoring, management, and decision-making.  
