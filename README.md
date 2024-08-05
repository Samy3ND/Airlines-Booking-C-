# Airline Ticket Booking System

This is a simple console-based airline ticket booking system written in C. It allows users to perform various operations like booking a ticket, viewing all tickets, finding a ticket, booking a seat, viewing all records, and deleting a record.

Features

1. Booking a Ticket**: Allows the user to book a ticket by entering ticket code, passenger name, date, and ticket price.
2. View All Tickets**: Displays all the booked tickets.
3. Find a Ticket**: Searches for a ticket using the ticket code.
4. Book a Seat**: Books a seat for a passenger by entering the ticket code, passenger details, and total seats.
5. View All Records**: Displays all the records of booked tickets.
6. Delete a Record**: Deletes a record from the system.



Menu Options:
   - Enter `1` to book a ticket.
   - Enter `2` to view all tickets.
   - Enter `3` to find a ticket.
   - Enter `4` to book a seat.
   - Enter `5` to view all records.
   - Enter `6` to delete a record.
   - Enter `0` to exit the program.

File Structure

- `data.txt`: Stores the details of all booked tickets.
- `record.txt`: Stores the records of booked seats.

Notes

- Ensure that `data.txt` and `record.txt` are present in the same directory as the executable.
- The current implementation does not handle all edge cases and is intended for educational purposes.

