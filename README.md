# Hotel-Management-System
Overview
The HostNate is a robust Spring Boot web application that streamlines hotel operations like room reservations, guest management, and role-based access. It uses MySQL for backend data storage and Thymeleaf for the frontend view layer. The system is built to increase management efficiency by up to 60%.

Features ✨
✅ Admin Dashboard for complete control over hotel operations
✅ Admin Authentication & Authorization with Spring Security 🔐
✅ Room Booking & Reservation Management 🛏️
✅ Guest Information Handling 👤
✅ Real-time Room Availability Check
✅ Payment Handling (Simulation) 💳
✅ Spring Boot + Thymeleaf UI
✅ CSRF protection + session security

Technologies Used 🛠️
Layer	Tech Stack
Backend	Java, Spring Boot, Spring MVC, Spring Security
Frontend	Thymeleaf, HTML5, CSS3, Bootstrap
Database	MySQL + Spring Data JPA
Build Tool	Maven
IDE	IntelliJ / VS Code
Security	Spring Security (form login + session-based)

Database Schema 📊
The database contains these main tables:

Table Name	Description
admins	Stores admin user credentials
guests	Contains guest details
rooms	Room configuration and availability
reservations	Booking and reservation information
user	Registered user data (if enabled)
