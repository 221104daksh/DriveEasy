# 🚗 DriveEasy – Car Rental Management System

<p align="center">
  <img src="assets/logo.png" alt="DriveEasy Logo" width="180"/>
</p>

<p align="center">
  <b>A modern Car Rental Management System built with Streamlit, Python, and SQLite.</b><br>
  Manage vehicles, customers, rentals, returns, and business analytics through an intuitive dashboard.
</p>

---

## ✨ Overview

**DriveEasy** is a full-stack Car Rental Management System designed to streamline vehicle rental operations. The application provides an intuitive interface for managing fleet inventory, rental transactions, customer records, and business analytics, making it suitable for small to medium-sized rental businesses.

---

## 🚀 Key Features

### 🚘 Fleet Management

* Add, edit, and delete vehicles
* Track vehicle availability
* Search and filter cars
* Store vehicle details including:

  * Brand
  * Model
  * Year
  * Fuel Type
  * Daily Rental Price
  * Availability Status

### 👥 Customer Management

* Register new customers
* Update customer information
* Delete customer records
* Maintain customer database

### 📄 Rental Management

* Create new rental bookings
* Automatically calculate rental cost
* Prevent double booking
* Update vehicle availability
* Maintain rental history

### 🔄 Return Management

* Process vehicle returns
* Update rental status
* Restore vehicle availability
* Calculate total rental charges

### 📊 Analytics Dashboard

Interactive visualizations powered by Matplotlib:

* Monthly Rental Trends
* Most Rented Car Brands
* Revenue Insights
* Fleet Utilization

### 🗄 Database

* SQLite Database
* Relational Tables
* Persistent Data Storage
* Automatic CRUD Operations

---

## 🛠 Tech Stack

| Category        | Technology   |
| --------------- | ------------ |
| Language        | Python       |
| Frontend        | Streamlit    |
| Database        | SQLite       |
| Data Analysis   | Pandas       |
| Visualization   | Matplotlib   |
| Version Control | Git & GitHub |

---

## 📁 Project Structure

```text
DriveEasy/
│
├── app.py
├── database.py
├── dashboard.py
├── fleet.py
├── customers.py
├── rentals.py
├── returns.py
├── analytics.py
├── reports.py
├── utils.py
├── style.css
├── requirements.txt
├── README.md
│
├── assets/
│   ├── logo.png
│   └── images/
│
└── car_rental.db
```

---

## ⚙ Installation

### Clone the Repository

```bash
git clone https://github.com/221104daksh/DriveEasy.git
cd DriveEasy
```

### Create a Virtual Environment

**Windows**

```bash
python -m venv venv
venv\Scripts\activate
```

**Linux / macOS**

```bash
python3 -m venv venv
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
streamlit run app.py
```

The application will open automatically in your default browser.

---

## 📊 Dashboard Preview

The dashboard includes:

* Fleet Summary
* Vehicle Availability
* Rental Statistics
* Revenue Overview
* Interactive Charts
* Business Insights

> Add screenshots here after deployment.

```
assets/screenshots/dashboard.png
assets/screenshots/fleet.png
assets/screenshots/analytics.png
```

---

## 📈 Future Enhancements

* Admin Authentication
* Customer Login Portal
* Email Notifications
* PDF Invoice Generation
* Vehicle Image Upload
* Online Payment Integration
* Advanced Analytics Dashboard
* Cloud Database Support
* Multi-user Role Management

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push to GitHub

```bash
git push origin feature-name
```

5. Open a Pull Request

---

## 👨‍💻 Author

**Daksh Sharma**

* GitHub: https://github.com/221104daksh


---

## ⭐ Support

If you found this project useful, consider giving it a **⭐ Star** on GitHub.

It helps others discover the project and motivates future improvements.

---

## 📄 License

This project is licensed under the **MIT License**.

Feel free to use and modify it for educational and personal purposes.
