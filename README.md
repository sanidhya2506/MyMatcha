# 💖 MyMatcha — Your Personalized BL Drama Recommender

_A web app where you can find your related BL drama recommendations with just one click!_

Welcome to **MyMatcha**, the first-ever **BL (Boys' Love) drama recommendation engine** built using Machine Learning. Unlike general movie or anime recommenders, **MyMatcha is exclusively focused on BL dramas**, helping fans discover what to watch next based on their personal taste.

🌐 **Live App**: [MyMatcha BL Recommender](https://mymatcha-jrjsdk8mm5bobfwdnu88ph.streamlit.app/)

---

## 🖼 Preview

![MyMatcha App Screenshot](Screenshot%202025-07-23%20153549.png)


---

## 🗂 Custom Dataset for BL Dramas

Since there was **no existing dataset** for BL dramas available online, I **curated and compiled my own dataset manually** from various trusted sources, drama archives, and fan communities.

📄 **Dataset (Google Sheet)**:  
🔗 [BL Drama Dataset Sheet](https://docs.google.com/spreadsheets/d/1TcMXr_EwMpA99Lz20EaVqHQmPvJ2M6g8zFfwtZeoHeE/edit?usp=sharing)

Feel free to use it for academic, project, or fan work purposes — just give credits!

---

## 🧠 What MyMatcha Does

✨ When a user types the name of a BL drama they liked, **MyMatcha predicts and recommends the top 5 most relevant BL dramas** using a trained machine learning model based on content similarity.

📌 The app also features:
- 🔝 Top 5 BL drama recommendations from:
  - 🇰🇷 **South Korea**
  - 🇹🇭 **Thailand**
  - 🇯🇵 **Japan**
- 💘 A **personal favorite drama pick** to check out

All this, beautifully packed into an easy-to-use and minimalist web app.

---

## 🛠 Tech Stack

- **Python**
- **Streamlit**
- **Scikit-learn** (ML model)
- **Pandas / Numpy**
- **Pickle** (for saving similarity matrix)
- **Google Sheets Dataset**

---

## 🧪 How It Works

1. User enters a drama title in the input box
2. The app compares it with others using text vector similarity
3. Displays the **top 5 most similar BL dramas**
4. Also shows **country-wise top BL picks** + 1 personal choice

---

## 📚 Installation 

```bash
git clone https://github.com/your-username/mymatcha.git
cd mymatcha
pip install -r requirements.txt
streamlit run main.py
