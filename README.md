# 🍔 FoodHub - Food Delivery Chatbot
## 📌 Project Description
FoodHub is an intelligent food delivery chatbot that allows users to browse menus, place orders, and interact using natural language. The system integrates a database to manage food items and orders efficiently.

---

## ✨ Features
- Conversational food ordering system  
- Menu browsing through chatbot  
- Order placement and tracking  
- Database integration for storing orders  
- User-friendly interaction

---

## 📸 Screenshots

### 💬 Chat Input
![Chat Input](images/foodhub_chat_input.png)

### 🤖 Chatbot Response
![Chat Response](images/foodhub_chat_response.png)

### 🧾 Order Confirmation
![Order Confirmation](images/foodhub_order_confirmation.png)

### 🗄️ Database Query
![Database Query](images/foodhub_database_query.png)
![Database Response](images/foodhub_database_response.png)

---

## 🛠️ Tech Stack
- Python  
- Pandas, NumPy  
- SQLite (via sqlite3 with SQL queries)  
- LangChain (for chatbot workflow)  
- ChatGroq (LLM) integrated using LangChain 

---

## 📊 Project Workflow
1. Import and initialize required libraries  
2. Configure Large Language Model (LLM)  
3. Connect chatbot with SQL database  
4. Build conversational flow using LangChain  
5. Process user queries and return responses  

---

## 📈 Output
The chatbot successfully interprets user queries and provides relevant responses such as menu suggestions, order confirmation, and tracking details.

---

## ⚙️ Installation & Setup
```bash
git clone https://github.com/nayanasharma7124/FoodHub
cd FoodHub
pip install -r requirements.txt
python app.py
