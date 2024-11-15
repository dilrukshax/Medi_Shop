# 🛒 Medi Shop - Pharmacy Management System

**Medi Shop** is a robust pharmacy management system designed to optimize and automate pharmacy operations. It offers efficient solutions for managing inventory, processing sales, and handling customer information through an intuitive interface.

---

## 🌟 Features

- **Inventory Management**: Add, update, and track medicines and products.
- **Sales Processing**: Efficiently process transactions and generate receipts.
- **Customer Management**: Maintain customer records and purchase histories.
- **User-Friendly Interface**: Simplified design for easy navigation and usability.

---

## 🛠️ Technologies Used

<p align="center">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java Badge" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL Badge" />
  <img src="https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS Badge" />
  <img src="https://img.shields.io/badge/SCSS-CC6699?style=for-the-badge&logo=sass&logoColor=white" alt="SCSS Badge" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript Badge" />
</p>

---

## ⚙️ Setup and Installation

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/dilrukshax/Medi_Shop.git
```

### 2️⃣ Navigate to the Project Directory
```bash
cd Medi_Shop
```

### 3️⃣ Import the Database
- Use the provided `medishop.sql` file to set up the database schema and data.
- Import the file using a tool like **phpMyAdmin** or the MySQL command line:
  ```bash
  mysql -u username -p database_name < medishop.sql
  ```

### 4️⃣ Configure the Database Connection
- Open the application’s configuration files and update the database credentials:
  ```java
  db.host = "localhost";
  db.user = "username";
  db.password = "password";
  db.database = "medishop";
  ```

### 5️⃣ Deploy the Application
- Run the application in your Java-supported environment.
- Ensure your server is configured for the application stack.

---

## 🚀 Usage

1. **Launch the Application**: Start the application on your local server or supported environment.
2. **Inventory Management**: Add and update product details like name, quantity, and price.
3. **Sales Processing**: Process customer transactions and generate receipts.
4. **Customer Management**: Maintain customer information and purchase histories.

---

## 🤝 Contribution

Contributions are welcome and appreciated! Follow these steps to contribute:

1. **Fork this repository**.
2. **Create a new branch**:
   ```bash
   git checkout -b feature-name
   ```
3. **Make changes** and commit:
   ```bash
   git commit -m "Added new feature"
   ```
4. **Push your changes**:
   ```bash
   git push origin feature-name
   ```
5. **Submit a pull request** for review.

---


## 🎉 Acknowledgments

A special thanks to all contributors and open-source projects that helped make this project a reality. Together, we’re transforming pharmacy management!
