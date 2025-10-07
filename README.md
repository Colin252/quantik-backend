# Quantik - Personal Finance App

Quantik is a **full-stack personal finance management application**.  
It helps individuals and businesses manage their **incomes, expenses, invoices, clients, products, and reports** with an intuitive dashboard and PDF export support.

---

## 🚀 Features
- User registration & login (JWT authentication)
- Manage clients, providers, products, and invoices
- Record income, expenses, and transactions
- Dashboard with balance and statistics
- PDF export for invoices
- REST API + React frontend integration
- Modern responsive UI

---

## 🛠️ Tech Stack

### Backend
- Java 17
- Spring Boot 3
- Spring Security + JWT
- MySQL
- Maven

### Frontend
- React 18
- React Router DOM
- Axios
- jsPDF + jspdf-autotable
- CSS3

---

## ⚙️ Installation

### Backend
```bash
# Clone backend
git clone https://github.com/Colin252/quantik-backend.git
cd quantik-backend

# Configure DB in src/main/resources/application.properties
spring.datasource.url=jdbc:mysql://localhost:3306/quantik_db
spring.datasource.username=root
spring.datasource.password=your_password

# Run backend
./mvnw spring-boot:run
# Clone frontend
git clone https://github.com/Colin252/quantik-frontend.git
cd quantik-frontend

# Install dependencies
npm install

# Start development server
npm start

🌍 Access

Backend: http://localhost:8080

Frontend: http://localhost:3000

📌 Author

Developed by Helton Emerson Quiroz Lopez
Full Stack Developer | Java + Spring Boot + React.js



