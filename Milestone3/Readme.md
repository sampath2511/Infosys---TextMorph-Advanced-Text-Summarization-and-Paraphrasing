## 🧠 Milestone 3 – AI-Based Text Summarization and Paraphrasing  
---

## 📌 Project Title  
TextMorph – Advanced Text Summarization and Paraphrasing  

---

## 📖 Project Overview  
In Milestone 3, the core functionality of the TextMorph project was implemented by integrating Artificial Intelligence-based Natural Language Processing (NLP) models for text summarization and paraphrasing.  

This milestone builds upon the secure authentication system developed in Milestone 1 and Milestone 2. After successful login, users can access advanced text processing tools that allow them to summarize long text and generate paraphrased versions of the content.  

The objective of this milestone is to help users quickly understand large textual information and rewrite content in a different structure while preserving its original meaning.  

---

## 🎯 Objective of Milestone 3  
The main objectives of this milestone were to:  

- Implement an AI-based text summarization module  
- Develop a text paraphrasing system  
- Integrate NLP features into the authenticated dashboard  
- Provide a simple and interactive user interface  
- Enable efficient processing of large text  

---

## 🛠 Technologies Used  
The following technologies were used in this milestone:  

- **Python** – Core programming language  
- **Streamlit** – Web-based user interface  
- **Transformers (HuggingFace)** – Pretrained NLP models  
- **NLTK / SpaCy** – Text preprocessing  
- **SQLite Database** – User data storage  
- **JWT (JSON Web Token)** – Secure authentication  
- **bcrypt** – Password hashing  
- **Ngrok** – Public deployment  

---

## 🚀 Features Implemented  
---

### 📑 Text Summarization Module  
The system generates a concise and meaningful summary from long text inputs.  

**Process**  
- User enters a long text paragraph  
- NLP summarization model processes the input  
- Key information is extracted  
- A short summary is generated and displayed  

**Benefits**  
- Saves time and effort  
- Highlights important points  
- Improves content understanding  

---

### ✏️ Text Paraphrasing Module  
This feature rewrites text while preserving its original meaning.  

**Process**  
- User inputs a sentence or paragraph  
- NLP model analyzes sentence structure  
- Alternative phrasing is generated  
- Paraphrased output is displayed  

**Advantages**  
- Enables content rewriting  
- Useful for academic writing  
- Reduces plagiarism  

---

## 🔐 Integration with Authentication System  
The NLP modules are integrated with the secure authentication system built in earlier milestones.  

**Workflow**  
- Only authenticated users can access features  
- JWT ensures secure session handling  
- Dashboard provides access to all AI tools  

---

## ⚙️ Application Workflow  
The system works as follows:  

1. User registers via Signup page  
2. Email validation and security checks are performed  
3. User logs in with valid credentials  
4. JWT authentication grants dashboard access  
5. User inputs text for summarization or paraphrasing  
6. NLP model processes the text  
7. Output is displayed to the user  

---

## ▶️ How to Run the Application  
---

### Step 1 – Install Dependencies  
```bash
pip install streamlit transformers torch nltk spacy bcrypt pyjwt pyngrok
```

### Step 2 – Run Application  
```bash
streamlit run app.py
```

### Step 3 – Access  
Open the Streamlit local URL in your browser or use Ngrok for public access.  

---

## 🔮 Future Scope  
The project can be enhanced by adding:  

- Grammar correction module  
- Multi-language summarization  
- AI chatbot integration  
- Cloud deployment (AWS / Azure)  
- Advanced NLP optimization  

---

## 📌 Conclusion  
Milestone 3 successfully integrates AI-based text summarization and paraphrasing into the TextMorph system. These features allow users to efficiently analyze and rewrite large text while maintaining context and meaning.  

Combined with the secure authentication system from previous milestones, this completes the core functionality of the project and demonstrates a real-world application of AI and NLP.  
## ScreenShots

----
OTP Verification
<img width="1600" height="720" alt="image" src="https://github.com/user-attachments/assets/05350eb4-c8b3-4d71-a2b5-4a9e82e5d69a" />
Readability Dashboard
<img width="1600" height="760" alt="image" src="https://github.com/user-attachments/assets/ee2bf3d1-9c2e-4101-afd0-85dadca34902" />
<img width="1600" height="752" alt="image" src="https://github.com/user-attachments/assets/9ae8cd68-923f-4d4b-ba45-e2262bdb8497" />
Text Summarization Module
<img width="1600" height="764" alt="image" src="https://github.com/user-attachments/assets/254300ba-8cd5-4345-a651-570454240e44" />
Paraphrasing Module
<img width="1600" height="764" alt="image" src="https://github.com/user-attachments/assets/813392cd-6b74-4d40-b6f6-200ffe03fb9c" />
Dataset Augmentation Module
<img width="1600" height="764" alt="image" src="https://github.com/user-attachments/assets/986fd8bd-cfb6-4d0b-b1d0-204ee591d9fc" />
<img width="1600" height="764" alt="image" src="https://github.com/user-attachments/assets/63925c86-3466-42ea-813c-1f1cc1a20593" />






