# Onine_Flight_Reservation_Portal
Flight Ticket Booking: A web app for users to book flights. Backend &amp; DB tech stack open. Simple UI with HTML &amp; CSS. Users can log in, sign up, search flights by date/time, book tickets based on availability, view their bookings, and log out. Admins have separate login, can add/remove flights, and view bookings by flight number/time.



Introduction:

The Flight Ticket Booking project aims to develop a web application that allows users to search for flights based on date and time, book tickets, and manage their bookings. The application will also have an admin interface to manage flights and view bookings. The project will use a suitable tech stack for the backend and database, while the frontend will be implemented using HTML and CSS.


User Use Cases:

1.1 Login:

Users can log in to the application using their credentials.
Validation checks will be implemented to ensure the accuracy of the entered data.

1.2 Sign up:

New users can sign up for an account with the required information.
Data validations will be implemented to ensure the correctness of the provided data.

1.3 Searching for flights based on date and time:

Users can search for flights based on their desired date and time.
The application will query the database to retrieve flights that match the search criteria.

1.4 Booking tickets on a flight based on availability:

Users can book tickets for a flight based on the availability of seats.
The system will check the seat count for the selected flight and allow booking if seats are available.

1.5 My Booking:

Users can view a list of all their bookings.
The application will retrieve and display the bookings associated with the logged-in user.

1.6 Logout:

Users can log out from their account, ending their session.


Admin Use Cases:

2.1 Login:

Admin users can log in using separate credentials for the admin interface.

2.2 Add Flights:

Admin users can add new flights to the system.
The flight details, including flight number, time, and seat count, will be stored in the database.

2.3 Remove Flights:

Admin users can remove existing flights from the system.
The flight and associated booking data will be deleted from the database.

2.4 View all bookings based on flight number and time:

Admin users can view all the bookings for a specific flight based on flight number and time.
The application will query the database to retrieve the relevant booking information.


Advantages:

Easy Flight Search: Users can conveniently search for flights based on their preferred date and time, simplifying the booking process.
Booking Management: Users have access to their booking history, allowing them to manage their reservations effectively.
Seat Availability: The system checks seat availability before confirming bookings, ensuring a seamless experience for users.
Admin Control: The admin interface enables administrators to add and remove flights, as well as view bookings for better system management.
Improved User Experience: The web application's graphical interface enhances the user experience, making it more intuitive and user-friendly.


Limitations:

Limited Scope:		The project focuses on flight ticket booking and does not cover other aspects of travel planning, such as hotel reservations or car rentals.
Simulated Seat Count:		 The seat count is assumed to be a default value of 60, which may not reflect the actual capacity of flights.
Payment Integration:		 The project does not include payment integration, and therefore, the ticket booking process does not involve actual financial transactions.
Security Considerations:		 The report does not address specific security measures like authentication mechanisms, data encryption, and protection against common vulnerabilities.
Scalability:		 The project does not discuss scalability aspects, such as handling a large number of concurrent users or optimizing database performance for high loads.


Applications:

The Flight Ticket Booking project can be utilized in various scenarios, including:

Online Travel Agencies (OTA): OTA platforms can incorporate this application to provide flight booking services to their customers.
Airlines: Airlines can adopt this system as a part of their online ticket reservation process, enabling users to book flights directly from their websites.
Travel Management Companies:

Travel management companies can utilize the application to facilitate flight bookings for their clients, streamlining the travel planning process.


Conclusion:

The Flight Ticket Booking web application project aims to provide users with a convenient and user-friendly platform to search for flights, book tickets, and manage their bookings. The system includes user and admin interfaces to cater to their specific requirements. While the project offers advantages in terms of ease of use and booking management, it has limitations in terms of scope, seat count assumption, payment integration, security considerations, and scalability. The application finds potential applications in online travel agencies, airlines, and travel management companies, enhancing their service offerings in flight ticket reservations
