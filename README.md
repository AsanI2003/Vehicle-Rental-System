# 🚗 QuickCars Vehicle Rental System

This is an **academic project** developed for vehicle rentals.  
It allows customers to **inquire about available vehicles**, manage rentals, and includes features such as Google login and email notifications. 
JWT Secure Admin side for management

---

## 📌 Features
- Customers can inquire about available vehicles  
- Vehicle availability management  
- Authentication with Google OAuth2  
- Email notifications via Gmail SMTP  
- Secure API key-based access
- JWT Secure Admin Side

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/Vehicle-Rental-System.git
cd Vehicle-Rental-System



2️⃣ Configure Application Properties

src/main/resources/application.properties

# API Key
api.key=asan-quickcars-2025   # 👉 Change this to your own key

# Database Configuration
spring.datasource.username=root          # 👉 Replace with your DB username
spring.datasource.password=Ijse@1234     # 👉 Replace with your DB password

# Google OAuth2 Configuration
spring.security.oauth2.client.registration.google.client-id=763855479181-8hpsqmg3tsh7qrroga0001pu9jfff22b.apps.googleusercontent.com   # 👉 Replace with your Google client ID
spring.security.oauth2.client.registration.google.client-secret=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   # 👉 Replace with your Google client secret

# Email Configuration
spring.mail.username=asanindusara348@gmail.com   # 👉 Replace with your Gmail address
spring.mail.password=iphriuacmjlkdakd            # 👉 Replace with your Gmail app password

3️⃣ Run the Application

mvn spring-boot:run


The application will be available at:
👉 http://localhost:8080

▶️ Demo Video
https://youtu.be/xZOALoJVml4?si=M987Sg7vUgoaDQgV


📄 License

This project was built as an academic project and is not intended for production use.
You may modify and use it for learning purposes.


✨ Author
👤 Asan Indusara
asanindusara348@gmail.com



