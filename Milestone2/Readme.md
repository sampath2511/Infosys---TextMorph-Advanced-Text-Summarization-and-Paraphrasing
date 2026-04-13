## 📌 Milestone 2 – Advanced Authentication & Readability Analytics Integration  
---

### 🔗 Continuation from Milestone 1  
After completing **Milestone 1**, which established the foundational authentication interface and basic navigation flow, Milestone 2 focused on strengthening system functionality, security mechanisms, and analytical capabilities.  

This phase transformed the application from a UI prototype into a **fully functional, secure, database-driven AI platform.**  

---

## 🔐 Authentication System Enhancements  
---

### ⭐ Database-Driven User Management  
- Integrated SQLite database for persistent user storage  
- Created structured table for user credentials and security metadata  
- Enabled automatic database initialization during app startup  

---

### ⭐ Secure Registration Workflow  
- Implemented username uniqueness validation  
- Added email format validation using regex  
- Enforced password strength constraints  
- Stored security question and answer for recovery use  
- Introduced password hashing for secure storage  
- Enabled automatic login after successful registration  

---

### ⭐ Login System Improvements  
- Database-backed credential verification  
- Secure password hash comparison  
- Token-based session handling  
- Automatic redirection to dashboard upon authentication  
- Error messaging for invalid login attempts  

---

### ⭐ OTP-Based Password Recovery  
A complete recovery pipeline was implemented:  

- Registered email verification  
- OTP generation and email delivery  
- OTP time-based expiry control  
- New password validation  
- Prevention of reuse of old password  
- Password update in database  
- Post-reset navigation back to login  

---

## 📊 Readability Intelligence Module  
---

### ⭐ Feature Introduction  
Milestone 2 introduced a dedicated **Readability Intelligence Dashboard** enabling text complexity analysis for NLP experimentation.  

---

### ⭐ Multi-Source Text Input  
Users can analyze text through:  
- Manual text entry  
- Plain text file upload (.txt)  
- Word document upload (.docx)  

---

### ⭐ Readability Metrics Implemented  
- Flesch Reading Ease  
- Flesch-Kincaid Grade Level  
- Gunning Fog Index  
- SMOG Index  
- Automated Readability Index  

---

### ⭐ Visualization & Interpretation  
- Gauge visualizations for intuitive understanding  
- Comparative bar chart for metric overview  
- Semantic interpretation of readability levels  
- Responsive layout with metric containers  

---

## 🎨 UI & Interaction Improvements  
---

- Updated application color scheme for professional appearance  
- Improved button behavior and hover interaction  
- Added navigation controls for password reset flow  
- Enhanced form spacing and layout consistency  
- Fixed overlapping UI elements and visual artifacts  

---

## 🧠 Skills & Concepts Applied  
---

- Secure authentication architecture  
- Token-based session management  
- Database integration in Streamlit applications  
- Email automation for OTP workflows  
- NLP readability metric computation  
- Interactive visualization design  
- UI refinement and usability optimization  

---
## ScreenShots
---
OTP Email verification
<img width="1911" height="907" alt="image" src="https://github.com/user-attachments/assets/75431a8c-3859-4c65-bfc7-6b4786dfb685" />
Readability metrics visualization
<img width="1910" height="910" alt="image" src="https://github.com/user-attachments/assets/7726c6f1-5172-4420-b3b5-5df22fc9942f" />
<img width="1918" height="910" alt="image" src="https://github.com/user-attachments/assets/8056c7a1-81ff-456f-9a0f-17839ea0a6d5" />


