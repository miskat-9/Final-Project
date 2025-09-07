# AI News Summarizer 📰🤖

An end-to-end **AI-powered news summarization system** built with **FastAPI**, **Streamlit**, and **Web Scraping**.  
The project allows scraping news articles, storing them in a database, summarizing them in **English & Bangla**, and providing a user-friendly interface for interaction.  

---

## 📂 Project Structure

```
Final Project( AI news summarizer )/
│── requirements.txt
│── Database/
│   ├── database_connection.py
│   ├── news_db_manager.py
│   ├── news_insert.py
│   └── (ER diagrams & table schema images)
│
│── FastAPI-news/
│   ├── main.py
│   ├── models.py
│   ├── english_summarizer.py
│   └── requirements.txt
│
│── Streamlit-App/
│   ├── app.py
│   ├── database.py
│   └── Streamlit.py
│
│── Web Scrapping/
│   └── Web Scrapping and Insertion to DB.ipynb
│
│── SS of Streamlit UI/
│   └── (Screenshots of API & Streamlit interface)
```

---

## 🚀 Features

- 🔎 **Web Scraping**: Automatically fetch news articles from sources.  
- 🗄 **Database Management**: Store news, publishers, reporters, categories, and summaries.  
- ⚡ **FastAPI Backend**:
  - REST APIs for fetching and summarizing news.  
  - English & Bangla summarization support.  
- 🎨 **Streamlit Frontend**:
  - Clean UI to view, search, and summarize news.  
  - Interactive dashboards.  
- 📸 **Screenshots Included**: Demonstrates working APIs and Streamlit pages.  

---

## 🛠️ Tech Stack

- **Backend**: FastAPI  
- **Frontend**: Streamlit  
- **Database**: MySQL
- **AI Models**: Custom summarizers (`english_summarizer.py`, `bangla_summarizer`)  
- **Web Scraping**: Jupyter Notebook (BeautifulSoup / Requests expected)  
- **Others**: Python 3.10+, PyTorch/Transformers (if used for NLP)  

---

## ⚙️ Installation & Setup

1. **Clone the repository**  
   ```bash
   git clone <repo-link>
   cd Final Project( AI news summarizer )
   ```

2. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

3. **Setup Database**  
   Run the scripts inside the `Database/` folder to create tables and insert sample data.  

4. **Run FastAPI Backend**  
   ```bash
   cd FastAPI-news
   uvicorn main:app --reload
   ```

5. **Run Streamlit App**  
   ```bash
   cd Streamlit-App
   streamlit run app.py
   ```

---

## 📊 Database Schema

The database contains the following tables:  

- **Categories**  
- **News**  
- **Publisher**  
- **Reporter**  
- **Images**  
- **Summary**  


---

## 📷 Screenshots

Screenshots of the project are available inside **`SS of Streamlit UI/`**.  
They include:  
- FastAPI endpoints (categories, news, reporter APIs, etc.)  
- Streamlit UI pages (news list, categories, summaries, etc.)  

---

## 🔮 Future Improvements

- Integration with live news APIs (e.g., NewsAPI, Google News).  
- More advanced summarization using **transformer-based models** (BART, Pegasus, mBART for Bangla).  
- Multilingual support beyond English & Bangla.  
- Deploying on cloud platforms (Heroku, AWS, Hugging Face Spaces).  

---

