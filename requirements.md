# Movie Kiosk Requirements

- R1: The customer shall be able to view available movies and their showtimes.
- R2: The customer shall be able to select an available seat for a chosen showtime.
- R3: The customer shall be able to purchase a ticket for the selected showtime and seat.
- R4: After a successful purchase, the system shall display a confirmation with the ticket ID, movie, showtime, and seat number.
- R5: The system shall prevent more than one issued ticket for the same seat and showtime.

## Seat availability rule
Availability is specific to a showtime. The same physical seat can be sold for different showtimes, but it cannot be sold twice for the same showtime. In this model, checking availability and placing a temporary hold happen as one indivisible operation. The hold is converted to a sale after successful payment or released if the purchase fails.
