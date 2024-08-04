# 🚌 Bus Reservation System
## Overview
The Bus Reservation System is a Java-based application that allows users to book bus tickets. It provides a simple and interactive console-based interface for users to view available bus information, book tickets, and receive confirmation of their bookings.

## Features
Display available bus information.
Book bus tickets interactively.
Check for seat availability.
Confirm bookings and handle full buses gracefully.
User-friendly input handling with appropriate prompts and error messages.
Prerequisites
Java Development Kit (JDK): Ensure you have JDK 11 or above installed on your machine.
MySQL Database: Make sure you have a MySQL database set up with the necessary tables for storing bus and booking information.
Setup and Installation
## Clone the Repository

sh
Copy code
git clone https://github.com/Preethipa19/BusReservationSystem.git
cd BusReservationSystem
Compile the Java Files

sh
Copy code
javac -d out src/BUSRESERVATION/*.java
Run the Application

sh
Copy code
java -cp out BUSRESERVATION.BusMain

## Usage
Launch the Application: Run the BusMain class to start the bus reservation system.
View Bus Information: The system will display the available buses and their details.
Book a Ticket: Follow the prompts to book a ticket. Enter 1 to book a ticket or 2 to exit the system.
Handle Full Buses: The system will notify you if the bus is full and prompt you to try another bus or date.
Exit the System: Enter 2 to exit the system and receive a thank you message.
## Example Usage
sh
Copy code
Connected
Bus ID: 101, Bus Name: RedLine, Seats Available: 10
Bus ID: 102, Bus Name: BlueLine, Seats Available: 5

Enter 1 to Book and 2 to exit
1
Enter Bus ID: 101
Enter Date (yyyy-mm-dd): 2024-08-05
Enter Number of Seats: 2
Your booking is confirmed

Enter 1 to Book and 2 to exit
2
Thank you for using the booking system!
