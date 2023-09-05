# tswift-database
> A high level database redesign for Taylor Swift's concert ticketing system

# Taylor Swift Ticketing System Database Redesign

## Overview

Tasked with mitigating contemporary challenges in live concert ticketing—ranging from crashing websites to unfair ticket allocations—our team is redesigning the database infrastructure for TicketSwift, a startup in the ticketing industry. The repository focuses on implementing a MySQL database to support efficient, equitable, and scalable ticketing solutions.

## Features 🎶

### Concerts

- **Concert Series Details**: Includes the name, artist, and promoter.
- **Events**: Each series comprises various events distinguished by a unique number, location, venue, date/time, and URL.
- **Zone**: Events have at least one 'zone' with specifications such as type (VIP, General Admission, etc.), description, and safety limit.
  
### Fans 👨‍🎤

- **Personal Information**: Recorded details include first name, last name, email, phone number, and affiliations.
- **Warnings**: Track any warnings given to fans for misconduct.
- **Social Connections**: Unique feature allowing fans to be notified when their connections purchase tickets.

### Tickets and Waitlisting 🎟️

- **Standard Purchasing**: Information maintained about the seat, fan, payment processor, and transaction ID.
- **Waitlisting**: For high-demand events, a waitlist entry system with manual or random approval methods.

### Event Staff 👨‍💼

- **Staff Details**: Each event requires at least one staff member with recorded identification and training status.
- **Employers**: Staff assignments, employer details, and employment dates are logged.

## Business Requirements 📈

The database aims to answer pertinent business queries such as:

1. Staff involvement in multiple concerts.
2. Frequency of fan warnings.
3. Efficacy of waitlist systems.
4. Fans connected to specific individuals who haven’t purchased tickets.
5. Staff self-dealing in ticket purchases.
6. Affiliations between fans and fan clubs.
7. Event attendance among connected fans.
8. VIP ticket sales effectiveness.
9. Specific seat occupancies.
10. Training compliance of staff for specific events.
