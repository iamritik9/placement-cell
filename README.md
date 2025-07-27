# 🎓 Placement Cell - CUTM 🚀

<p align="center">
  <img width="2156" height="1290" alt="Placement Cell Banner" src="https://github.com/user-attachments/assets/ee095c2d-2649-4cd2-9e92-941d7baa37de" />
</p>

## ⭐ Introduction

The **Placement Cell Application** is a full-stack web platform developed using **MongoDB**, **MySQL**, **Spring Boot**, **Java**, **React**, and **REST APIs**. It is designed to help college placement teams efficiently manage student and company data, interview schedules, and results.

This platform is **employee-exclusive** and provides both **student** and **interview management** features through a responsive, user-friendly interface.

### 👨‍💼 Key Features

- Employee and Student registration/login
- CRUD operations for students and companies
- Assign students to interview slots and record results
- Download student data as CSV reports
- Add/remove/edit interview slots and assignments
- Validate image uploads (max 3MB)
- Dummy job listings linking to real job portals
- Profile update functionality
- Fully responsive UI across all devices

<p align="center">
  <img src="https://user-images.githubusercontent.com/76626529/192450122-842c2578-c742-4922-988b-4b141195cfed.png" alt="Dashboard Preview" />
</p>

---

## 🚀 Getting Started

Follow these steps to set up the project locally.

### 📦 Prerequisites

- Node.js & NPM
- Spring Boot
- MongoDB
- MySQL
- Postman (for API testing)

### 🔧 Installation Steps

1. **Fork** the repository
2. **Clone** the repo to your local machine
3. **Set up environment variables** in the `application.properties` file using the format from `ENV_FORMAT.json`
4. From frontend directory, install dependencies:
   ```bash
   npm install
   ```

### ⚙️ Run Locally

#### Development Mode
```properties
ENVIRONMENT=development
DEPLOYMENT=local
```
```bash
npm start         # For frontend
spring-boot:run   # For backend
```

#### Production Mode
```properties
ENVIRONMENT=production
DEPLOYMENT=heroku/aws/local
```
```bash
npm run build
```

---

## 🧰 Tech Stack & Tools

| Category        | Tools / Technologies                                                                 |
|----------------|----------------------------------------------------------------------------------------|
| 👨‍💻 Frontend     | React.js, SCSS, EJS, Bootstrap, JavaScript, HTML5, CSS3                              |
| ⚙️ Backend       | Java, Spring Boot, Spring Security, JPA, REST APIs                                   |
| 🗃️ Database      | MongoDB, MySQL                                                                        |
| 🔐 Auth & Security | JWT, Passport.js, bcryptjs                                                           |
| 📦 Libraries     | mongoose, cors, cookie-parser, json2csv, validator, etc.                              |
| 🧪 Testing       | Postman                                                                               |
| 📂 Others        | VSCode, Git, GitHub, Maven, CSV Export, Google OAuth, Flash Messages                 |

<p align="center">
  <img height="140" src="https://www.w3.org/html/logo/downloads/HTML5_Logo_256.png" />
  <img height="140" src="https://logodix.com/logo/470309.png" />
  <img height="140" src="https://upload.wikimedia.org/wikipedia/commons/6/6a/JavaScript-logo.png" />
  <img height="140" src="https://upload.wikimedia.org/wikipedia/commons/b/b2/Bootstrap_logo.svg" />
  <img height="140" src="https://github.com/user-attachments/assets/f93d7ed7-ee2f-4e7c-8fc8-9271c6181896" />
  <img height="140" src="https://github.com/user-attachments/assets/4a78b60a-5f10-4283-b324-28161ed508cb" />
  <img height="140" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRASBParCnQhsRkKZ8opkkRjtk9XJ-MHdy0jA&usqp=CAU" />
  <img height="140" src="https://code.visualstudio.com/assets/apple-touch-icon.png" />
</p>

---

## 💻 Screenshots

<p align="center">
  <img width="2159" height="1298" alt="Image" src="https://github.com/user-attachments/assets/a31db3e1-a3b9-4bae-9d92-1865d9f4f8ca" />
  <br/><br/>
  <img width="2159" height="1301" alt="Image" src="https://github.com/user-attachments/assets/ab6b1c98-9c5d-47ad-b45a-41d0ead3c0e0" />
  <br/><br/>
  <img width="2157" height="1297" alt="Image" src="https://github.com/user-attachments/assets/255b867e-a852-41d4-b63c-803230fa5232" />
</p>

---

---

## 🙋‍♂️ Developed By

**Ritik Chandra Mishra**  
📧 ritikchandramishra96@gmail.com  
🔗 [GitHub](https://github.com/iamritik9)

---

## ✅ License

This project is licensed under the MIT License. Feel free to use and modify.
