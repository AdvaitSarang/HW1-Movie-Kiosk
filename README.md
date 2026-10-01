# HW1-Movie-Kiosk
Guided software engineering tools practice.
## Movie Theater Ticket Kiosk
This self-service kiosk lets a customer view movies and showtimes, choose an available seat, and purchase a ticket. After a successful purchase, it displays a confirmation. The system prevents the same seat from being sold twice for the same showtime.

## Purchase Ticket

**Primary Actor:** Customer

**Precondition:** The kiosk is operational, and movie and showtime information is available. This use case describes one ticket purchase.

**Main Steps:**

1. The customer views the available movies and chooses a showtime.
2. The kiosk displays the available seats for that showtime.
3. The customer selects a seat and enters payment details.
4. The kiosk sends the purchase request to the ticket service.
5. The ticket service checks availability and temporarily holds the seat.
6. The payment service processes the payment and returns an approval.
7. The ticket service marks the seat as sold, creates the ticket, and records the payment.
8. The kiosk displays the ticket ID, movie, showtime, and seat number as confirmation.

**Postcondition:** One ticket is issued and payment is recorded. The selected seat cannot be sold again for the same showtime.
