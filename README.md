# Smart Procurement & Vendor Management System

A web-based application designed to streamline procurement operations, vendor management, purchase requisitions, purchase orders, and approval workflows through a centralized platform.

## 🌟 Key Features

- **Vendor Management:** Maintain vendor details, contact information, ratings, and vendor status.
- **Requisition Management:** Create and track purchase requisitions with item specifications, quantities, and pricing details.
- **Purchase Order Management:** Manage purchase orders and their associated items and supplier information.
- **Approval Workflow:** Support the review and approval process for requisitions and purchase orders.
- **Dashboard:** View procurement-related information through a centralized interface.
- **Report Generation:** Support PDF and Excel reports using JasperReports.
- **Role-Based Access Control (RBAC):** Organize application access according to assigned user roles.
- **Responsive User Interface:** Web interface developed using Thymeleaf, HTML, and CSS.

## 🛠️ Technology Stack

| Component | Technology |
|---|---|
| Backend | Java, Spring Boot |
| Security | Spring Security |
| Frontend | Thymeleaf, HTML, CSS |
| Database | MySQL |
| ORM and Data Access | Spring Data JPA |
| Reporting | JasperReports |
| Build Tool | Apache Maven |

## 📁 Project Structure

```text
Smart-Procurement-Vendor-Management-System/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/procurement/procurement/
│   │   │       ├── config/
│   │   │       ├── controller/
│   │   │       ├── dto/
│   │   │       ├── entity/
│   │   │       ├── exception/
│   │   │       ├── mapper/
│   │   │       ├── repository/
│   │   │       ├── security/
│   │   │       ├── service/
│   │   │       └── util/
│   │   ├── resources/
│   │   │   ├── jasper/
│   │   │   ├── static/css/
│   │   │   ├── templates/
│   │   │   └── application.properties
│   │   └── test/
├── .gitignore
├── FRONTEND_GUIDE.txt
├── MIT_License
├── mvnw
├── mvnw.cmd
├── pom.xml
└── README.md
```

## 🚀 Getting Started

### Prerequisites

- Java Development Kit (JDK) compatible with the project configuration
- MySQL Server
- Apache Maven or the included Maven Wrapper

### 1. Clone the Repository

```bash
git clone https://github.com/rohinivaddikar/Smart-Procurement-Vendor-Management-System.git
```

### 2. Navigate to the Project Directory

```bash
cd Smart-Procurement-Vendor-Management-System
```

### 3. Create the Database

Create the database configured for your application in MySQL. For example:

```sql
CREATE DATABASE procurement_db;
```

### 4. Configure Database Credentials

Open `src/main/resources/application.properties` and configure the database connection for your local environment.

Keep your database username and password private. Use environment variables or a secure local configuration for sensitive credentials. Do not commit real passwords or secrets to this public repository.

### 5. Run the Application

On Windows, open PowerShell in the project directory and run:

```powershell
.\mvnw.cmd spring-boot:run
```

Alternatively, if Maven is installed and configured:

```bash
mvn spring-boot:run
```

### 6. Open the Application

After the application starts successfully, open the configured local application URL in your browser. Check `application.properties` for the actual server port and application configuration.

## 🔐 Security

- Protect database credentials and other sensitive configuration.
- Avoid committing passwords, API keys, tokens, or production secrets.
- Use appropriate authentication and authorization controls.
- Change any credentials that may have been exposed publicly.

## 🧪 Testing

The project includes test source files under `src/test`. To run the available tests, use:

```powershell
.\mvnw.cmd test
```

You can also use `mvn test` if Maven is installed.

## 📸 Screenshots

Application screenshots can be added here to demonstrate the dashboard, vendor management, requisitions, purchase orders, and approval workflows.

## 🤝 Contributing

Suggestions and improvements are welcome.

1. Fork the repository.
2. Create a branch for your changes.
3. Implement and test your updates.
4. Submit a pull request describing your contribution.

## 👩‍💻 Author

**Rohini Vaddikar**

GitHub: [@rohinivaddikar](https://github.com/rohinivaddikar)

## 📄 License

This project is distributed under the MIT License. See the [MIT_License](MIT_License) file for details.
