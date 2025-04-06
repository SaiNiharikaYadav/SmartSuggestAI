
# Smart Suggest AI

Smart Suggest AI is an intelligent, AI-powered product recommendation platform that provides real-time personalized suggestions based on user preferences. It is built using Flask (Python) for the backend and HTML/CSS/JavaScript for the frontend, with SQLite for session and data storage.

---

##  Features

- 🔐 User login and preference input
- 📦 Real-time product filtering and recommendation
- 📊 Filters based on:
  - Category
  - Subcategory
  - Brand
  - Price Range
  - Rating
  - Season
  - Location
- ⚡ Fast, dynamic frontend with no page reloads
- 🗃️ Data-driven recommendations using CSV dataset (10,000+ products)
- 💾 SQLite integration for session management and logging
- 📉 Filtered display based on multiple criteria
- 🛠️ Built with Flask, JavaScript, Pandas, and Bootstrap

---

## 📂 Project Structure
SmartSuggestAI/ │ ├── app.py # Flask backend ├── static/ │ └── script.js # Frontend JS (AJAX logic) │ ├── templates/ │ └── index.html # Combined login + recommendation page │ ├── data/ │ └── product_recommendation_data.csv # Dataset (Product info) │ ├── database/ │ └── smart_suggest.db # SQLite database (optional)


---

## 🧪 Sample Dataset Columns

- `Product_ID`
- `Category`
- `Subcategory`
- `Price`
- `Brand`
- `Average_Rating_of_Similar_Products`
- `Product_Rating`
- `Customer_Review_Sentiment_Score`
- `Holiday`
- `Season`
- `Geographical_Location`
- `Similar_Product_List`
- `Probability_of_Recommendation`

---

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript (vanilla)
- **Backend**: Python, Flask
- **Database**: SQLite
- **Data Processing**: Pandas
- **Data Storage**: CSV file (`product_recommendation_data.csv`)

---

## 🧰 Installation & Setup

1. **Clone the repository**
git clone https://github.com/SaiNiharikaYadav/SmartSuggestAI.git
cd SmartSuggestAI
2.Install Python dependencies
pip install flask pandas
3.Run the application
python app.py
4.Open your browser
http://localhost:5000/

✨ Future Enhancements

1.User profile management
2.Machine learning for smarter suggestions
3.Admin dashboard to upload product data
4.Exporting recommendations as PDF
5.Responsive mobile-first design


