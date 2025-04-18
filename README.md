# GIC Cinema Booking System

The **GIC Cinema Booking System** is a console-based application designed to manage cinema seat bookings, cancellations, and seat allocation. It provides an intuitive interface for users to book tickets, view seat maps, and manage their bookings efficiently.

## Features

- **Book Tickets**: Users can book tickets for a movie, with the system automatically allocating the best available seats.
- **View Seat Map**: Displays the current seating arrangement, highlighting reserved and available seats.
- **Cancel Bookings**: Allows users to cancel their bookings by entering the booking ID.
- **Check Bookings**: Users can view details of their bookings, including seat numbers and booking IDs.
- **Dynamic Seat Allocation**: The system prioritizes seat allocation from the middle of the row outward for optimal viewing experience.
- **Manual Seat Reallocation**: Users can manually reallocate seats during the booking process.

## Technologies Used

- **Java**: Core programming language used for the application.
- **IntelliJ IDEA**: IDE used for development.
- **Console-based UI**: Simple and interactive text-based user interface.

## Project Structure
src/
└── main/
    └── com/
        └── gic/
            └── cinema/
                ├── Booking.java         # Class representing a booking
                ├── CinemaService.java   # Main service class for managing bookings
                ├── ConsoleUI.java       # Utility class for console-based I/O
                ├── MenuCommand.java     # Functional interface for menu commands
                └── SeatMap.java         # Class for managing seat allocation

## How to Run

1. Clone the repository to your local machine.
2. Open the project in IntelliJ IDEA or any Java IDE.
3. Compile and run the `CinemaService` class.
4. Follow the on-screen instructions to interact with the system.

## Usage

1. **Start the Application**: Define the movie title and view the main menu.
2. **Book Tickets**: Enter the number of tickets to book. The system will allocate the best available seats.
3. **View Seat Map**: Check the current seating arrangement.
4. **Cancel Booking**: Enter the booking ID to cancel a reservation.
5. **Check Bookings**: View details of your bookings by entering the booking ID.

## Example Menu

Welcome to GIC Cinemas

[1] Book tickets for movie (seats available) 
[2] Check bookings 
[3] View seat map 
[4] Cancel booking 
[5] Exit

## Key Classes

- **CinemaService**: Main class handling user interaction, bookings, and seat management.
- **SeatMap**: Manages the 2D grid of seats, including allocation and availability.
- **ConsoleUI**: Provides methods for console-based input and output.
- **Booking**: Represents a booking with a unique ID and allocated seats.
- **MenuCommand**: Functional interface for menu command execution.

## Future Enhancements

- Add support for multiple movies and showtimes.
- Implement a graphical user interface (GUI).
- Add payment integration for online bookings.
- Enhance seat allocation algorithms for group bookings.

## Author

Developed by **micromanikandan**.
                    
