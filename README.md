Testing Project: Movie Booking System
Project Overview
A comprehensive testing report for an online movie booking system, focused on verifying business logic accuracy, security protocols, and user experience.

Backend: Spring Boot, Spring Data JPA, Spring Security.

Database: MySQL.

Testing Tools: Manual Testing, Excel.

Testing Scope
1. Unit Testing
Verified independent methods to ensure core logic functions correctly.

Authentication: Validated BCrypt password encryption and email format verification.

Authorization: Verified Role-Based Access Control (RBAC) for Admin and Customer roles via Spring Security.

Business Logic: Tested automated seat suggestions (Auto-seat) and total price calculations for tickets and catering.

2. Integration Testing
Ensured seamless data flow across system modules (Booking → Payment → Ticket Generation).

Movie Booking Flow: Validated the end-to-end journey from movie selection and showtimes to final checkout.

Seat Reservation: Verified the temporary seat-locking mechanism (10-minute timer).

Payment Integration: Tested Bank Webhook processing and automated order status updates to "CONFIRMED".

Seat Release: Confirmed automatic seat release and database status updates upon booking expiration (Timeout).

##Testing Deliverables

* **Detailed Test Case Report (PDF):** [View PDF Report](https://github.com/NhanNW/Movie-Booking-System-Testing-Report/blob/main/Online%20Movie%20Ticket%20Booking%20System%20Report.pdf)
