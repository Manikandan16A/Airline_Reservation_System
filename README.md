# Airline_Reservation_System

The **Airline Reservation System** is a Java-based project that allows users to manage airline bookings, cancellations, flight details, and payment options. This system helps automate the process of booking airline tickets and provides a user-friendly interface for customers to handle various aspects of their travel.

## Features

### 1. **User Authentication**
   - Users can sign up, log in, and recover their forgotten passwords.
   - The system provides secure authentication methods for both regular users and administrators.

### 2. **Flight Management**
   - **Add Flight Details**: Admins can add flight details including flight number, destination, departure time, and fare.
   - **Search Flight Details**: Users can search for available flights based on their destination and travel date.
   
### 3. **Ticket Booking and Cancellation**
   - **Book Ticket**: Users can book tickets for available flights by providing necessary information such as personal details, flight selection, and payment method.
   - **Cancel Flight Ticket**: Users can cancel their booked tickets through the cancellation system.

### 4. **Payment Options**
   - **Credit Card and Debit Card Payments**: The system supports both credit and debit card payment options.
   - **Payment Option Selection**: Users can select their preferred method of payment and proceed with ticket purchases.

### 5. **User-Friendly Interface**
   - A simple and easy-to-use interface for navigating through flight booking, ticket cancellations, and payment processing.
   - **Home Page**: Displays key functionalities and navigation links to other features.

## Project Structure

- **Add_Flight_Details.java**: Manages adding and updating flight information.
- **Book_Ticket.java**: Handles ticket booking for users.
- **Cancel_Flight_Ticket.java**: Allows users to cancel their booked tickets.
- **Credit_Card.java**: Manages payment through credit cards.
- **Debit_Card.java**: Manages payment through debit cards.
- **Forgot.java**: Provides functionality for users to recover forgotten passwords.
- **Home.java**: The main homepage for the system.
- **Login.java**: Manages user login.
- **Payment_Option.java**: Allows users to choose payment methods.
- **Search_Flight_Details.java**: Facilitates searching for available flights.
- **Signup.java**: Manages user signups and account creation.

## How to Run the Project

1. Clone this repository to your local machine.
   ```bash
   git clone https://github.com/your-username/Airline_Reservation_System.git
   ```
2. Open the project in your preferred IDE (e.g., IntelliJ IDEA, Eclipse).
3. Compile and run the project using the main entry point in `Home.java`.
4. Ensure that all the necessary libraries are added to your project classpath.

## Prerequisites

- **Java Development Kit (JDK)**: Version 8 or higher.
- **MySQL Database**: For storing user and flight details.
- **JDBC Driver**: To facilitate database connectivity.

## Future Enhancements

- **Flight Seat Selection**: Add a seat selection feature during ticket booking.
- **User Profiles**: Implement user profiles to store booking history and frequent flyer details.
- **Mobile Payment Integration**: Support mobile payments through services like PayPal or Google Pay.

## Contributing

If you would like to contribute to this project, feel free to submit pull requests with detailed descriptions of your changes.

---

This structure should provide a good starting point for documenting your Airline Reservation System project! Let me know if you’d like to adjust anything.
