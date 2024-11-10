# Style Sync
## Salon Appointment Management System

A modern web application built with Angular and Spring Boot that allows customers to manage their salon appointments online.

## Features

- **Appointment Booking**
  - Schedule appointments with preferred stylists
  - Select services and time slots
  - Receive confirmation emails
  
- **Appointment Management**
  - View upcoming and past appointments
  - Cancel or reschedule existing appointments
  - Check appointment status
  
- **User Authentication**
  - Secure login/registration system
  - User profile management
  - Role-based access (customers, stylists, admin)

## Technology Stack

### Frontend
- Angular (Latest Version)
- TypeScript
- Angular Material UI
- RxJS
- NgRx (State Management)

### Backend
- Java Spring Boot
- Spring Security
- Spring Data JPA
- MySQL/PostgreSQL
- Maven/Gradle

## Prerequisites

- Node.js (v18 or higher)
- Java JDK 17 or higher
- Maven/Gradle
- MySQL/PostgreSQL
- IDE (recommended: VS Code, IntelliJ IDEA)

## Installation

### Backend Setup

1. Clone the repository
```bash
git clone https://github.com/yourusername/salon-appointment-system.git
cd salon-appointment-system/backend
```

2. Configure database
```properties
# src/main/resources/application.properties
spring.datasource.url=jdbc:mysql://localhost:3306/salon_db
spring.datasource.username=your_username
spring.datasource.password=your_password
```

3. Run the Spring Boot application
```bash
./mvnw spring-boot:run
```

### Frontend Setup

1. Navigate to the frontend directory
```bash
cd ../frontend
```

2. Install dependencies
```bash
npm install
```

3. Start the development server
```bash
ng serve
```

The application will be available at `http://localhost:4200`

## Project Structure

```
salon-appointment-system/
├── frontend/
│   ├── src/
│   │   ├── app/
│   │   ├── assets/
│   │   └── environments/
│   └── package.json
└── backend/
    ├── src/
    │   ├── main/
    │   └── test/
    └── pom.xml
```

## API Endpoints

### Appointments
- `POST /api/appointments` - Create new appointment
- `GET /api/appointments` - Get all appointments
- `GET /api/appointments/{id}` - Get appointment by ID
- `PUT /api/appointments/{id}` - Update appointment
- `DELETE /api/appointments/{id}` - Cancel appointment

### Users
- `POST /api/auth/register` - Register new user
- `POST /api/auth/login` - User login
- `GET /api/users/profile` - Get user profile

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Contact

Your Name - [your.email@example.com]
Project Link: [https://github.com/yourusername/salon-appointment-system](https://github.com/yourusername/salon-appointment-system)

## Acknowledgments

- Angular Documentation
- Spring Boot Documentation
- [Other libraries and resources used]
