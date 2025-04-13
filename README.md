# 🍽️ CaloriChef - Restaurant Menu Management System

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![Flask](https://img.shields.io/badge/Flask-Web%20Framework-lightgrey?logo=flask)
![MongoDB](https://img.shields.io/badge/Database-MongoDB-brightgreen?logo=mongodb)
![Responsive](https://img.shields.io/badge/Responsive-Design-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

**CaloriChef** is a web-based Restaurant Menu Management System that allows restaurant admins to manage and display menu items dynamically. Users can filter meals based on nutritional information, availability, and category. Built using **Flask**, **MongoDB**, and basic **HTML/CSS/JavaScript**, CaloriChef offers a modern solution for digital menu control.


## 📌 Features

- ✅ Admin dashboard to add/edit/delete food items  
- 🍱 Categorize meals (e.g., Breakfast, Lunch, Dinner)  
- 💪 Nutrition-based filters (Protein, Carbs, Calories)  
- 🔍 Search functionality  
- 📱 Fully responsive design  
- 🔄 Real-time data updates with Flask and MongoDB  


## 🛠️ Tech Stack

| Layer       | Technology             |
|-------------|------------------------|
| Frontend    | HTML, CSS, JavaScript  |
| Backend     | Python (Flask)         |
| Database    | MongoDB (NoSQL)        |


## 🚀 Getting Started

### 🔧 Prerequisites

- Python 3.10+
- MongoDB (Local or Atlas)
- pip / virtualenv

### 📦 Installation

```bash
# Clone the repository
git clone https://github.com/niharikaaa1209/calorichef.git
cd calorichef

# Create and activate virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Configure your MongoDB connection in config.py or app.py

# Run the app
flask run
