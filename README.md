# 🎯 Smart Event Management System with AI Assistant

## 📌 Overview

The **Smart Event Management System with AI Assistant** is an intelligent platform designed to streamline event planning and management. It integrates an **AI-powered assistant** to automate tasks such as event scheduling, attendee queries, and personalized recommendations.

This system enhances user experience by combining **automation, real-time interaction, and data-driven insights**.

---

## 🚀 Features

* 📅 Event creation and management
* 🤖 AI Assistant for user queries and guidance
* 🔍 Smart search and filtering of events
* 🧾 Attendee registration and tracking
* 📊 Real-time event insights and updates
* 💬 Interactive chatbot for event-related questions

---

## 🛠️ Tech Stack

* **Frontend:** Streamlit 
* **Backend:** FastAPI
* **Database:** SQLite / PostgreSQL
* **AI/ML:** NLP, LLM (for assistant)
* **Libraries:** LangChain 

---


## 📂 Project Structure

```bash
Smart_Event_Management_System/
│
├── backend/                      # FastAPI backend services
│   ├── __pycache__/              # Python cache files
│   ├── database/                 # Database configuration & connections
│   ├── models/                   # Data models and schemas
│   ├── routes/                   # API endpoints
│   ├── services/                 # Business logic and processing
│   ├── credentials.json          # API credentials/config (keep secure)
│   ├── events.db                 # SQLite database
│   ├── main.py                   # FastAPI entry point
│   ├── sheets.py                 # Integration with Google Sheets
│   ├── requirements.txt          # Backend dependencies
│   └── Dockerfile                # Backend container setup
│
├── frontend/                     # User interface (Streamlit apps)
│   ├── __pycache__/              # Python cache files
│   ├── admin_dashboard.py        # Admin panel for event management
│   ├── student_app.py            # User interface for participants
│   ├── requirements.txt          # Frontend dependencies
│   └── Dockerfile                # Frontend container setup
│
├── .env                          # Environment variables
├── .env.example                  # Sample environment config
├── .gitignore                    # Git ignore rules
├── docker-compose.yml            # Multi-container orchestration
└── README.md                     # Project documentation
```

```

---

## ⚙️ Installation


git clone https://github.com/your-username/smart-event-management.git
cd smart-event-management
pip install -r requirements.txt
```

---

## ▶️ How to Run

### 1️⃣ Start Backend

```bash id="z2g9mx"
uvicorn main:app --reload
```

### 2️⃣ Start Frontend

```bash id="l0k3sd"
streamlit run app.py
```

---

## 🤖 AI Assistant Capabilities

* Answers event-related queries
* Provides schedule recommendations
* Assists with event navigation
* Handles FAQs automatically
* Supports conversational interaction

---

## 🧪 Example Use Case

1. User registers for an event
2. AI assistant suggests sessions based on interest
3. User asks questions → chatbot responds instantly
4. System tracks participation and engagement

---

## 📸 Screenshots

### 🏠 Home Page
<img width="1365" height="637" alt="Screenshot 2026-04-14 223354" src="https://github.com/user-attachments/assets/240f9e24-417c-480f-9774-fe4c4c148711" />
<img width="1365" height="631" alt="Screenshot 2026-04-14 225822" src="https://github.com/user-attachments/assets/c12f59a2-b9c1-4aa7-bb0a-7aef65d0f71e" />
<img width="1365" height="636" alt="Screenshot 2026-04-14 230039" src="https://github.com/user-attachments/assets/e814e6e6-842c-49da-8a73-6ec899649068" />
<img width="1365" height="635" alt="Screenshot 2026-04-14 230111" src="https://github.com/user-attachments/assets/b7f91ce3-f30e-4f10-bd2a-5d96f3963486" />
<img width="1365" height="632" alt="Screenshot 2026-04-14 230216" src="https://github.com/user-attachments/assets/f3e27181-b30e-4321-ac25-1ef2094bb276" />

### 🤖 AI Assistant Chat
<img width="1365" height="626" alt="Screenshot 2026-04-14 230259" src="https://github.com/user-attachments/assets/b52f7907-7cfd-447b-8ebf-6867c183bf97" />


### 📊 Dashboard
<img width="1365" height="640" alt="Screenshot 2026-04-14 230410" src="https://github.com/user-attachments/assets/9fb2d47b-56cd-41a1-9ac1-04371efe75f0" />


---

## 💡 Use Cases

* 🎓 College event management
* 🏢 Corporate event planning
* 🎤 Conferences and seminars
* 🎉 Community events

---


## 👩‍💻 Author

**Maha Vigneshwari**
Generative AI Developer

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
