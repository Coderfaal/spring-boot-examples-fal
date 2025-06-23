# 🎓 Spring Boot Student REST API

A simple and beginner-friendly Spring Boot REST API that manages student records using H2 in-memory database.

---

## 🚀 Features

- 🧾 Create new students (`POST /students`)
- 📄 Get all students (`GET /students`)
- 🔍 Get student by ID (`GET /students/{id}`)
- ❌ Delete student (`DELETE /students/{id}`)
- 🔄 Update student (`PUT /students/{id}`) *(optional to add)*
- ✅ Input validation using `@Valid` annotations
- 🗃 In-memory H2 database with schema & sample data

---

## ⚙️ Tech Stack

| Tool            | Description                        |
|-----------------|------------------------------------|
| 💻 Java         | Programming Language               |
| ☕ Spring Boot   | Backend Framework                  |
| 🛠 Maven         | Build Tool                         |
| 💾 H2 Database  | In-memory DB for dev/test          |
| 🧪 JUnit        | Unit Testing *(optional)*          |

---

## 📁 Project Structure

src/
└─ main/
└─ java/
└─ com.in28minutes.springboot.rest.example.student/
├─ Student.java
├─ StudentRepository.java
└─ StudentResource.java
└─ resources/
├─ application.properties
├─ schema.sql
└─ data.sql



---

## 💡 How to Run

1. Clone the Repository:
git clone https://github.com/Coderfaal/spring-boot-examples.git

2.Open in IntelliJ or VS Code

3.Run the App
mvn spring-boot:run

4.Access Endpoints

| Method | Endpoint         | Description          |
| ------ | ---------------- | -------------------- |
| GET    | `/students`      | Get all students     |
| GET    | `/students/{id}` | Get student by ID    |
| POST   | `/students`      | Add new student      |
| DELETE | `/students/{id}` | Delete student by ID |

---

📬 Sample Request Body (POST)

{
  "name": "name",
  "passportNumber": "IND1234567"
}

---

📚 Learning Highlights
✅ Spring Boot REST API development

✅ @RestController, @GetMapping, @PostMapping, etc.

✅ Handling JSON request/response with Jackson

✅ Using @Autowired with Repository layer

✅ Auto schema/data loading with H2 and schema.sql + data.sql

---

🎯 Enhancements (TODOs)
 ➕ Add PUT /students/{id} for updates

 🧪 Add JUnit tests for controller & service

 🌐 Add Swagger UI documentation

 🎨 Connect with a frontend (React/Vue)

 ☁️ Deploy to Render or Railway

 ---

 🧠 Bonus Tips
You can view H2 Console at:
http://localhost:8080/h2-console
(Make sure to enable it in application.properties)

Use Postman or Thunder Client to test POST/DELETE endpoints easily.


 ---

 🧑‍💻 Author
Made with ❤️ by Falguni Nargund
🔗 LinkedIn


 ---

 🙏 Acknowledgement
Thanks to in28minutes for the project base & tutorials.

