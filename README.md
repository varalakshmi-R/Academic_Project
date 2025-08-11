# Academic_Project
# Secure and Scalable EV Data Protection using RBAC and Identity-Based Cryptography

## Overview
This project implements a robust and efficient authorization management system for accessing electric vehicle (EV) data stored in a cloud server. It integrates Role-based Access Control (RBAC) with Identity-Based Cryptography (IBC) to enhance security and scalability.

## Features
- **RBAC + IBC Integration** for secure authentication and authorization.
- **Owner and Driver Modules** with private key-based authentication.
- **One-Time Password (OTP)** for sensitive operations.
- **Admin Module** for managing vehicles, owners, and drivers.
- **Spring Boot Backend** with REST API integration.
- **MySQL Database** for persistent storage.

## Technologies Used
- Java, Spring Boot, Thymeleaf
- HTML, CSS, JavaScript, jQuery
- MySQL 8
- Apache Tomcat
- Android (future enhancements)

## Modules
1. **Admin Module**
   - Add, update, and delete vehicle details.
   - Manage owners and drivers.
2. **Owner Module**
   - Add and manage vehicles.
   - View driver list.
   - Access vehicle data via OTP authentication.
3. **Driver Module**
   - Register and log in securely.
   - Access authorized vehicle data.

## System Requirements
### Hardware
- Hard Disk: 250GB+
- RAM: 6GB+
- Processor: i3 and above

### Software
- Windows 10 or above
- JDK 11.0
- J2EE
- MySQL 8

## Architecture
The system uses a cloud-based backend with secure key exchange and OTP verification. It employs MVC architecture with Spring Boot controllers and services.

## Installation & Setup
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Open the project in your IDE (IntelliJ/Eclipse).
3. Configure MySQL database settings in `application.properties`.
4. Run the Spring Boot application:
   ```bash
   mvn spring-boot:run
   ```
5. Access the application at:
   ```
   http://localhost:8080
   ```

## Future Enhancements
- Biometric authentication.
- Mobile app for real-time vehicle monitoring.
- Advanced analytics for EV data usage.

## License
This project is for academic purposes under Anna University curriculum.
