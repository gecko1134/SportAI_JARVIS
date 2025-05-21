# SportAI Ultra Complete Suite

This is the complete deployment bundle for the **SportAI Ultra Platform**, including:
- ✅ `main_app.py`: Streamlit-powered dashboard launcher
- ✅ `modules/`: All AI, analytics, and operations tools
- ✅ `users.json`: Preloaded with sample logins for testing
- ✅ Compatible with Streamlit Cloud and local deployment

---

## 🚀 Getting Started

### 1. Install Dependencies
```bash
pip install -r requirements.txt
```

### 2. Launch the App
```bash
streamlit run main_app.py
```

---

## 🔐 Sample Logins

| Email              | Password   | Role        |
|-------------------|------------|-------------|
| admin@example.com | admin123   | admin       |
| coach@example.com | coach123   | coach       |
| sponsor@example.com | sponsor123 | sponsor     |
| board@example.com | board123   | board       |
| member@example.com | member123 | member      |

You can modify or add users in `users.json`.

---

## 📂 Folder Structure

```
SportAI_Ultra_Complete/
├── main_app.py
├── users.json
├── modules/
│   ├── ai/
│   ├── ops/
│   └── ...
```

---

## 🧪 Demo Testing

Try uploading sample `.csv` files for:
- Demand forecasting
- Scheduling optimization
- Churn prediction
- Contract generation
- Sponsorship matching

Example files can be added manually or requested for generation.

---

## 📤 Deployment

For deployment to Streamlit Cloud or GitHub:
- Ensure `main_app.py`, `users.json`, and `modules/` are in root directory
- Push to a repo or upload to Streamlit Cloud


---

## ☁️ Streamlit Cloud Deployment

[![Deploy to Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://streamlit.io/)

### ➤ Setup Instructions:

1. Go to [streamlit.io/cloud](https://streamlit.io/cloud)
2. Connect your GitHub account
3. Click "New App" → select your repo
4. Set `main_app.py` as the target file
5. Make sure `requirements.txt` and `users.json` are present
6. Deploy and log in using the sample accounts

