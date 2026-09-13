# 🎟️ FestTracker

A full-stack event and fest management platform designed to help users discover, explore, and manage college fests and events in one place.

FestTracker provides an organized platform for viewing upcoming events, exploring fest details, and managing event-related information through a user-friendly interface.

---

## 🚀 Features

- 🎉 Browse and explore college fests and events
- 📅 View upcoming events and fest schedules
- 🔎 Search and explore event information
- 📝 View detailed information about fests and events
- 👤 User authentication and account management
- 🔐 Secure login and registration
- 📌 Manage fest and event details
- 📱 Responsive and user-friendly interface
- ⚡ Fast and organized full-stack architecture
- 🌐 Backend APIs for managing application data

---

## 🛠️ Tech Stack

### Frontend

- HTML
- CSS
- JavaScript
- React.js *(if used in the project)*

### Backend

- Java
- Spring Boot
- Spring MVC
- Spring Data JPA
- REST APIs

### Database

- MySQL / PostgreSQL *(as configured in the project)*

### Tools and Technologies

- Maven
- Git
- GitHub
- IntelliJ IDEA / VS Code
- Postman

---

## 📂 Project Structure

```text
FestTrackerSystem
│
├── Backend
│   ├── src
│   │   ├── main
│   │   │   ├── java
│   │   │   └── resources
│   │   └── test
│   ├── pom.xml
│   └── README.md
│
├── Frontend
│   ├── public
│   ├── src
│   ├── package.json
│   └── README.md
│
├── .gitignore
└── README.md
```

> The exact folder names may vary depending on the project configuration.

---

## ⚙️ Getting Started

Follow the steps below to run FestTracker locally.

### 1. Clone the Repository

```bash
git clone https://github.com/Roushni1211/FestTrackerSystem.git
```

Move into the project directory:

```bash
cd FestTrackerSystem
```

---

## 🔧 Backend Setup

### 1. Open the Backend Folder

```bash
cd Backend
```

### 2. Configure the Database

Create a database according to the database configuration used in the project.

Update the database properties in:

```text
src/main/resources/application.properties
```

Example configuration:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/festtracker
spring.datasource.username=your_username
spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

> Use your own database credentials and never upload passwords or secret keys to GitHub.

### 3. Install Dependencies

Make sure Java and Maven are installed.

Run:

```bash
mvn clean install
```

### 4. Start the Backend

Run:

```bash
mvn spring-boot:run
```

The backend will start on the configured port.

Usually:

```text
http://localhost:8080
```

---

## 💻 Frontend Setup

### 1. Open the Frontend Folder

From the project root:

```bash
cd Frontend
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Start the Frontend

```bash
npm start
```

The frontend will usually be available at:

```text
http://localhost:3000
```

---

## 🔑 Environment Variables

If the project uses environment variables, create a `.env` file locally and add the required values.

Example:

```env
DATABASE_URL=your_database_url
DATABASE_USERNAME=your_database_username
DATABASE_PASSWORD=your_database_password
JWT_SECRET=your_jwt_secret
```

Do not commit the `.env` file to GitHub.

Use `.env.example` to show the required variable names without exposing real credentials.

---

## 🔐 Authentication

FestTracker includes user authentication functionality to help secure user accounts and application access.

Authentication may include:

- User registration
- User login
- Password validation
- Secure API access
- Session or token-based authentication

---

## 🔄 Application Flow

```text
User
 │
 ▼
Frontend Interface
 │
 ▼
Backend REST APIs
 │
 ▼
Business Logic
 │
 ▼
Database
```

---

## 🧪 Testing the APIs

You can test the backend APIs using tools such as:

- Postman
- Swagger UI
- Browser Developer Tools

If Swagger is configured, open:

```text
http://localhost:8080/swagger-ui/index.html
```

---

## 📌 Future Enhancements

- Event registration and ticket booking
- Admin dashboard
- Event reminders and notifications
- Personalized event recommendations
- Fest organizer profiles
- Event reviews and ratings
- Online payment integration
- Email notifications
- Advanced search and filtering
- Deployment with cloud hosting

---

## 🤝 Contribution

Contributions are welcome!

To contribute:

1. Fork the repository.
2. Create a new branch.

```bash
git checkout -b feature/your-feature
```

3. Make your changes.
4. Commit your changes.

```bash
git commit -m "Add new feature"
```

5. Push the branch.

```bash
git push origin feature/your-feature
```

6. Open a Pull Request.

---

## 📄 License

This project is created for educational and development purposes.

---

## ⭐ Support

If you find this project useful, consider giving it a ⭐ on GitHub.
