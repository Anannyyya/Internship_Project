# 🍽️ Food Expiry Tracker & Recipe Suggester

## 📌 Overview
This **Streamlit-based web application** helps users track food expiry dates, categorize items using clustering, and suggest recipes based on items expiring soon. It leverages **machine learning (KMeans clustering)** to group foods based on expiry and provides insightful visualizations.

## 🚀 Features
- **Upload a CSV File** containing food items and their expiry dates.
- **Track Expiry** and calculate remaining days for each item.
- **Clustering using K-Means** to group items based on expiry duration.
- **Visualizations** (Elbow method, scatter plots) for better insights.
- **Smart Recipe Suggestions** for items nearing expiry.
- **User-friendly Interface** powered by **Streamlit**.

## 🛠️ Technologies Used
- **Python** 🐍
- **Streamlit** (for web UI)
- **Pandas** (data handling)
- **NumPy** (numerical operations)
- **Matplotlib & Seaborn** (visualization)
- **Scikit-Learn** (clustering and scaling)

## 📂 Installation & Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/food-expiry-tracker.git
   cd food-expiry-tracker
   ```

2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

3. Run the Streamlit app:
   ```sh
   streamlit run app.py
   ```

## 📊 Data Format (CSV)
Your CSV file should have the following structure:
```csv
Food Item,Expiry Date
Milk,2025-03-10
Bread,2025-03-07
Eggs,2025-03-15
```

## 📷 Screenshots
### 🔹 Home Page
![App Home](https://imgur.com/a/Gxo0ktg)
### 🔹 Clustering Visualization
![Cluster Plot](https://imgur.com/a/tUeNafb)
### 🔹 Recipe Suggestions
![Recipes](https://imgur.com/a/eFBuZOI)

## 🎯 Future Enhancements
- **Inventory Management**
- **User Authentication**
- **Push Notifications for Expiry Alerts**
- **Mobile-Friendly UI**

## 🤝 Contributing
Feel free to contribute! Open an issue or submit a pull request.

## 📜 License
This project is licensed under the MIT License.

---

🔗 **Live Demo**: [Streamlit App](https://your-streamlit-app-link.streamlit.app)  
📧 **Contact**: [your-email@example.com](mailto:your-email@example.com)

