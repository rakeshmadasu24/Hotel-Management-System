# Hotel-Management-System<br>
Overview<br>
The Hotel Management System is a robust Spring Boot web application that streamlines hotel operations like room reservations, guest management, and role-based access. It uses MySQL for backend data storage and Thymeleaf for the frontend view layer. The system is built to increase management efficiency by up to 60%.<br>
<br>
Features ✨<br><br>
✅ Admin Dashboard for complete control over hotel operations<br>
✅ Admin Authentication & Authorization with Spring Security 🔐<br>
✅ Room Booking & Reservation Management 🛏️<br>
✅ Guest Information Handling 👤<br>
✅ Real-time Room Availability Check
✅ Payment Handling (Simulation) 💳<br>
✅ Spring Boot + Thymeleaf UI<br>
✅ CSRF protection + session security<br>

Technologies Used 🛠️<br>
Layer	Tech Stack<br>
Backend:	Java, Spring Boot, Spring MVC, Spring Security<br>
Frontend:	Thymeleaf, HTML5, CSS3, Bootstrap<br>
Database:	MySQL + Spring Data JPA<br>
Build Tool:	Maven<br>
IDE:	IntelliJ / VS Code<br>
Security	Spring Security (form login + session-based)<br>
<br>
Database Schema 📊<br>
The database contains these main tables:<br>

Table Name  &nbsp; 	Description<br>
admins    &nbsp; 	Stores admin user credentials<br>
guests	  &nbsp;   Contains guest details<br>
rooms     &nbsp;    	Room configuration and availability<br>
reservations  &nbsp; Booking and reservation information<br>
user        	 &nbsp; Registered user data (if enabled)<br>
