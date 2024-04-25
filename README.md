1.Flight Booking Classes:
 d_booking: Handles details related to domestic flight bookings.
 i_booking: Handles details related to international flight bookings.
 
2.Passenger Class:
 Inherits from both d_booking and i_booking.
 Contains methods to input passenger details and booking choices.
 Methods for generating Passenger Name Record (PNR), selecting flights, and displaying booking details.

3.Payment Class:
 Handles payment-related functions, including the choice of payment method, processing card details, and confirming the transaction.
 File Management Functions:
 createfile: Writes booking data to a file for domestic bookings.
 createfilei: Writes booking data to a file for international bookings.
 cancelticket: Cancels a domestic booking by rewriting the file without the specified PNR.
 cancelticketi: Similar to cancelticket, but for international bookings.
 checkticket: Checks a booking by PNR for domestic flights.
 checkticketi: Similar to checkticket, but for international flights.

4.Main Function:
 Provides a user interface to interact with the booking system, allowing users to book, cancel, or check flight tickets.
 Contains input handling, switch-case structures for options, and error handling for invalid inputs.
 Overall, the code demonstrates a basic implementation of a flight booking system with various functionalities such as booking, cancellation, and checking tickets, 
 along with basic error handling. It uses file I/O operations to persist booking data and employs class inheritance to separate domestic and international flight 
 booking logic.
