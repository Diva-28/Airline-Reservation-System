Airline Reservation System
The Airline Reservation System is a web-based administrative application that allows administrators to manage flight and airport details. This system is designed to provide a user-friendly interface for administrators to oversee and make changes to flight and airport information.

Table of Contents
Features
Getting Started
Prerequisites
Installation
Technologies Used
License
Features
View Available Airports: Users can see a list of available airports in the system, along with their details such as name, location, and facilities.

Book a Flight: Users can search for flights based on various criteria like destination, departure date, and number of passengers. They can then book a flight and receive a booking confirmation.

View Available Flights: Users can search for available flights based on their travel preferences. The system displays a list of flights with relevant information such as departure time, arrival time, and ticket price.

Delete and Cancel Booking: Users can delete their bookings or cancel their reservations, freeing up seats for other passengers.

Edit Flight and Airport Details: Admin users can modify flight and airport information, such as changing departure times, adding new airports, or updating existing airport details.

Getting Started
Prerequisites
Before you can run the Airline Reservation System (Admin), ensure you have the following prerequisites:

Node.js installed on your system.
MySQL database server installed and running.
Java Development Kit (JDK) for running the Spring Boot backend
Installation

Navigate to the project directory: cd airline-reservation-system

Install the project dependencies for the frontend (React): cd frontend npm install

Return to the project root directory: cd ..

Configure the MySQL database connection by editing the application.yaml file in the backend.

Build and run the Spring Boot backend ./mvnw clean install ./mvnw spring-boot:run

Technologies Used
Spring Boot: Backend framework for building the server-side application.
React: Frontend framework for building the user interface.
Redux: State management library for React.
HTML/CSS: For styling and structuring the front end.
MySQL: Database for storing flight and airport information.
RESTful API: For communication between the frontend and backend
License
This project is licensed under the MIT License.

Thank you for reading!
