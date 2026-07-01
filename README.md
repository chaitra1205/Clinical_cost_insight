# 🏥 Clinical Cost Insight

Clinical Cost Insight is a full-stack web application designed to improve healthcare price transparency by allowing users to compare diagnostic test prices across multiple healthcare centers. The platform helps patients make informed decisions by providing an easy-to-use interface for searching and comparing medical test costs.

---

## 📌 Overview

The application collects and manages diagnostic test pricing information from different healthcare providers. It uses fuzzy string matching to identify similar test names, ensuring accurate search results even when different hospitals use different naming conventions.

---

## ✨ Features

- 🔍 Search diagnostic tests
- 💰 Compare prices across multiple hospitals
- 🤖 Fuzzy search using RapidFuzz
- 📊 MongoDB database integration
- 🌐 RESTful API architecture
- 📱 Responsive and user-friendly interface
- ⚡ Fast and efficient search functionality

---

## 🛠 Tech Stack

### Frontend
- HTML5
- CSS3
- JavaScript

### Backend
- Python
- Flask

### Database
- MongoDB Atlas

### Libraries
- RapidFuzz
- Flask-CORS
- PyMongo

---

## 📂 Project Structure

```
Clinical_Cost_Insight/
│
├── backend/
│   ├── app.py
│   ├── requirements.txt
│   └── database/
│
├── frontend/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
└── README.md
```

---

## 🚀 Installation

### Clone the Repository

```bash
git clone https://github.com/chaitra1205/Clinical_cost_insight.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Configure Environment Variables

Create a `.env` file and add your MongoDB connection string.

```
MONGO_URI=your_mongodb_connection_string
```

### Run the Backend

```bash
python app.py
```

The Flask server will start locally.

---

## 🎯 How It Works

1. Users search for a diagnostic test.
2. The application performs fuzzy matching using RapidFuzz.
3. Matching tests are retrieved from MongoDB.
4. Prices from different healthcare centers are displayed for comparison.
5. Users can choose the most affordable healthcare provider.

---

## 📈 Future Enhancements

- User Authentication
- Hospital Admin Portal
- AI-powered Cost Prediction
- Medical Report Upload
- OCR-based Test Extraction
- Location-based Hospital Recommendations
- Data Analytics Dashboard

---

## 👩‍💻 Author

**Bonagiri Chaitra**

- GitHub: https://github.com/chaitra1205
- LinkedIn: https://www.linkedin.com/in/chaitra-bonagiri-404b61290/

---

## 📄 License

This project was developed for educational and learning purposes.
