# 🎓 College Information Chatbot

A simple and smart chatbot that provides instant answers to common college-related questions like admissions, courses, fees, hostels, placements, contact details, and more.

This project uses datasets (`intents.csv` and `college_data.json`) along with your Python chatbot script to respond to student queries.

---

## 🚀 Features

* Provides information about:

  * Admissions
  * Fees
  * Courses offered
  * Faculty & departments
  * Hostels & facilities
  * Placements
  * Events & calendars
  * Contact details
* Easy to train and modify
* Dataset included for customization
* Works with ML/NLP-based chatbot logic

---

## 📂 Project Structure

```
📁 college-information-chatbot
│
├── college_bot.ipynb           # Main chatbot code (from Google Colab)
├── intents.csv                 # User utterances + responses dataset
├── college_data.json           # Knowledge base of college information
├── requirements.txt            # Python dependencies
└── README.md                   # Project documentation
```

---

## 🛠️ Tech Stack

* **Python**
* **NLTK / sklearn / simple NLP logic** (based on your code)
* **JSON Data Handling**
* **Google Colab / Jupyter Notebook**

---

## 📥 Installation & Setup

### 1️⃣ Clone the repository

```
git clone https://github.com/your-username/your-repo-name.git
```

### 2️⃣ Install dependencies

```
pip install -r requirements.txt
```

### 3️⃣ Run the chatbot

If using the notebook:

```
Open college_bot.ipynb → Run all
```

If you convert `.ipynb` to `.py`:

```
python chatbot.py
```

---

## 📊 Dataset Description

### **intents.csv**

This file contains:

* user utterances
* chatbot responses
* tags and context

Used for training the chatbot.

### **college_data.json**

This file works as:

* a knowledge base
* structure for courses, fees, departments, events

Your chatbot can fetch answers using this file.

---

## 🌟 Example Queries

You can ask:

* "When do admissions open?"
* "What is the B.Tech fee?"
* "Is hostel available?"
* "Who is the HOD of Mechanical?"
* "What are library timings?"
* "How to apply online?"

---

## 🧩 How to Customize

* Update `intents.csv` → to add more Q&A
* Update `college_data.json` → to add college-specific information
* Update responses in the code if needed

---

## 🏫 About

This chatbot helps students quickly access college information without navigating through websites or brochures.

---

## 🤝 Contributing

Feel free to fork the repo, open issues, or submit pull requests.

---





