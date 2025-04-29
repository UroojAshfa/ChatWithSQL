# 🧠 ChatWithSQL — AI-Powered Natural Language Interface for Databases

ChatWithSQL is a **production-grade** Streamlit application that empowers users to interact with relational databases using **natural language**. It leverages **LangChain agents**, **Groq LLMs**, and **SQL parsing** to abstract away SQL syntax, enabling seamless database access for both technical and non-technical users.

> 💡 Ideal for data analysts, engineers, educators, and decision-makers seeking fast, conversational insights from their data.

---

## 🚀 Key Features

- ⚡ **LLM-Powered SQL Agent**: Uses Groq's `Gemma2-9b-It` to interpret natural language queries and generate corresponding SQL statements in real-time.
- 🧩 **Multi-DB Support**: Connects to both local **SQLite3** (`student.db`) and **remote MySQL** databases with a simple toggle interface.
- 🧠 **LangChain Toolkit**: Built using LangChain's `SQLDatabaseToolkit` for robust reasoning and schema-aware interactions.
- 📊 **No-Code Analytics**: Democratize data access for business teams by removing the SQL barrier.
- 📡 **Secure API Key Input**: API and DB credentials are securely handled through Streamlit's sidebar UI.

---

## 🛠️ Tech Stack

| Layer        | Technology                      |
|--------------|----------------------------------|
| Frontend     | Streamlit                        |
| Backend      | LangChain Agents, Groq LLM       |
| Database     | SQLite3 / MySQL                  |
| ORM Layer    | SQLAlchemy                       |
| LLM Provider | [Groq](https://groq.com/)        |
| Language     | Python 3.9+                      |

---

## 🧰 Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/chatwithsql.git
cd chatwithsql

### 2. Create & Populate the Sample DB
```bash
python sqlite.py  # creates student.db with sample data

### 3. Install Required Packages
```bash
pip install -r requirements.txt

### 4.  Launch the Application
```bash
streamlit run app.py

### 5. Connect & Interact
Choose between SQLite3 or MySQL from the sidebar.

Input your Groq API Key and (if using MySQL) database credentials.

Start chatting with your data in natural language.


## 🧠 Example Use Cases
Data Analyst: "Show me the average marks of students in class A."

Marketing Lead: "List all students with marks above 90 in Marketing."

Instructor: "How many students failed in each section?"

