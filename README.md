# movie-theatre-ticket-booking-system
MondyCinema is a web-based movie ticket booking system developed using HTML, CSS, PHP, and MySQL, following an object-oriented programming (OOP) approach. The system is designed to simplify the process of browsing movies, booking tickets, and managing cinema operations through separate customer and admin interfaces.
Read.me file
1. Customer Section
Step 1 Home page (any users can access)index.php
Step 2 Registration
1.	Open the website and click on Register.
2.	Fill in the required fields:
o	Name
o	Email
o	Password
o	Confirm Password
3.	Click Submit.
4.	After successful registration, you will receive a confirmation message.

Step 3 Login
1.	Go to the Login page.(only register customers can login)
2.	Enter your Email and Password.
3.	Click Login.
4.	If credentials are correct, you will be redirected to the movie booking Page.
5.	If credentials are wrong, an error message will appear.

Step 4 Browsing Movies
1.	On the movie Page, select movie 
2.	Click on book button any movie poster to view details like description, duration, and trailer.

Step 5 Booking a Movie and payment
1.	On the selected movie page, click Book Now.
2.	Choose your date, time, and seats.
3.	Click Confirm Booking.
4.	Your booking details will be stored in the Bookings table.
5.	A confirmation message will appear with booking ID and seat numbers.
6.	After clicking confirm button payment page will appear
7.	After filling card details click pay button
8.	After clicking payment button payment successful message appear


Step 6 Checking Booking Status
1.	Go to Booking Status in the menu.
2.	Enter your Booking ID or login to see all your bookings.
3.	You can view:
o	Movie name
o	Date and time
o	Number of seats
o	Status (Pending / paid)

2. Admin Section
Step 1  Admin Login (admin/login.php)
1.	Navigate to the Admin Login page.
2.	Enter Admin Username and Password.(admin username :admin, password :admin123  )
3.	Click Login.
4.	Successful login redirects to the Admin Dashboard.

Step 2 Managing Movies
1.	Click Manage Movies in the admin dashboard.
2.	Options available:
o	Add Movie: Enter name, description, upload poster, and trailer.
o	Edit Movie: Modify existing movie details.
o	Delete Movie: Remove a movie from the database.
3.	Click Save after adding or editing a movie.

Step 3 Managing Bookings
1.	Go to Manage Bookings.
2.	View all customer bookings.
3.	Admin can edit or Cancel bookings.
4.	Updated status is reflected in the Customer Booking Status.

Step 4 Viewing Current Customer Visits
1.	Navigate to Current Customer Visits.
2.	On the selected movie page, click Book Now.
3.	Choose your date, time, and seats.Click Confirm Booking 
4.	This feature for customer current booking 
Step 5 Logout
1.	Click Logout in the admin panel.
2.	You will be redirected to the Admin Login page.
3.Installation / Setup Instructions
3.1 Server Setup
•	Install XAMPP/WAMP/LAMP.
•	Start Apache and MySQL.
3.2 Database Setup
1.	Open phpMyAdmin.
2.	Create a new database called mondycinema.
3.	Import mondymovie.sql to create tables: 
3.3Code flow and password
1.open browser index.php
2.customer username: will@gmail.com
                     Password:000000
                     username: ton@gmail.com
                     Password:000000

3.open browser admin/login page                     username: admin
                                                                                 Password: admin123


