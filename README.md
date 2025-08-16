# 📊 Customer Sentiment Analyzer

Gain instant insights from customer feedback with the power of **GenAI**.  
This Streamlit app analyzes customer reviews, classifies them as **Positive, Negative, or Neutral**, and visualizes trends for quick decision-making.

---

## 🚀 Features
- 🧠 **Sentiment Classification** using OpenAI (LLM-based analysis)  
- ✅ **Score-based Sentiment** from existing dataset metrics  
- 📊 Interactive **visualizations** with Plotly (hover, zoom, drill-down)  
- 🎯 **Filters** by product for focused insights  
- ⚡ Built with **Streamlit** for fast, user-friendly dashboards  

---

## 🛠 Setup Instructions  
### 1. Clone the Repository

a) git clone https://github.com/<your-username>/customer-sentiment-analyzer.git

b) cd customer-sentiment-analyzer

---

### 2. Create Virtual Environment
a) python -m venv .venv

b) source .venv/bin/activate   # Mac/Linux

c) .venv\Scripts\activate      # Windows

---

### 3. Install Dependencies
pip install -r requirements.txt

---

### 4. Set Up Environment Variables
Create a .env file in the root directory and add your OpenAI API key:

OPENAI_API_KEY=your_api_key_here

---

### 5. Run the App
streamlit run app.py

---

### 6. 📂 Project Structure
customer-sentiment-analyzer/
│── data/

│   └── customer_reviews.csv     # Sample dataset

│── app.py                       # Main Streamlit app

│── requirements.txt             # Python dependencies

│── .gitignore                   # Ignore files

│── .env                         # Environment variables

│── README.md                    # Project documentation

---

### 7. 📌 Tech Stack

a) Python 3.9+

b) OpenAI GPT – for sentiment classification

c) Streamlit – app framework

d) Pandas – data processing

e) Plotly – interactive visualizations

---

### 8. 📷 Demo Screenshot

<img width="563" height="1000" alt="CSA" src="https://github.com/user-attachments/assets/4906865d-a527-43c8-af50-d029c04a370b" />

---

### 9. 🤝 Contributing

Contributions are welcome! 🚀 If you'd like to improve this project:

a) Fork the repository

b) Create a new branch (feature/your-feature)

c) Commit your changes

d) Push to your branch

e) Open a Pull Request

---

### 10. 📜 License

This project is licensed under the MIT License. You’re free to use, modify, and distribute it.

---

### 11. 🙌 Acknowledgements

a) OpenAI for the GPT API

b) Streamlit for the interactive app framework

c) Plotly for visualization support
