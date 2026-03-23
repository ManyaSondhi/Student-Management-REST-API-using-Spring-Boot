# 🎓 STUDENT MANAGEMENT REST API  
### 🚀 Built with Spring Boot & MySQL  

<p align="center">
  <b>A RESTful API for managing student data using a clean layered architecture</b>
</p>

---

## 📌 Overview  

This project is a **Spring Boot-based REST API** designed to perform operations on student data.  
It follows a **layered architecture (Controller → Service → Repository → Model)** ensuring scalability and maintainability.  

---

## 🛠️ Tech Stack  

- 💻 **Spring Boot**  
- ☕ **Java (JDK 21)**  
- 🗄️ **MySQL Database**  
- 🔧 **Maven**  
- 🧪 **Postman (API Testing)**  

---

## ⚙️ Features  

✔ Add new student  
✔ Retrieve all students  
✔ Retrieve student by ID  
✔ Clean architecture  
✔ Database integration using JPA  

---

## 🔗 API Endpoints  

### 📍 Base URL  
http://localhost:8080/api/students


---

| Method | Endpoint | Description |
|--------|--------|------------|
| GET | `/api/students` | Get all students |
| GET | `/api/students/{id}` | Get student by ID |
| POST | `/api/students` | Add new student |

---

## 🧪 Example Request  

```json
{
  "name": "Manya",
  "course": "AIML"
}
```
## 📸 Screenshots  

### 🔹 Postman Output  

![Postman Output](images/postman.png)

---

### 🔹 Localhost Output  

![Localhost Output](images/localhost.png)


##⚙️ How to Run
git clone https://github.com/your-username/rest-api.git
cd rest-api
mvn spring-boot:run

##🧠 Architecture

Controller → Handles HTTP requests
Service → Business logic
Repository → Database operations
Model → Entity representation
⭐ Support

If you like this project, give it a ⭐ on GitHub!

👩‍💻 Author
Manya Sondhi
