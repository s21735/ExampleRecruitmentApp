# ExampleRecruitmentApp

zadanie wykonane według wytycznych: 

Ticket booking app
The goal is to build a seat reservation system for a multiplex.
Business scenario (use case)
1. The user selects the day and the time when he/she would like to see the movie.
2. The system lists movies available in the given time interval - title and screening times.
3. The user chooses a particular screening.
4. The system gives information regarding screening room and available seats. 
5.The user chooses seats, and gives the name of the person doing the reservation
(name and surname).
6. The system gives back the total amount to pay and reservation expiration time.

Assumptions:
1. The system covers a single cinema with multiple rooms (multiplex).
2.  Seats can be booked at latest 15 minutes before the screening begins. 
3. Screenings should be sorted by title and screening time.
4. There are three ticket types: adult (25 PLN), student (18 PLN), child (12.50 PLN).

Business requirements:
1. The data in the system should be valid, in particular:
a. name and surname should each be at least three characters long, starting with
a capital letter. The surname could consist of two parts separated with a single
dash, in this case the second part should also start with a capital letter. b.
reservation applies to at least one seat.
2. The system should properly handle Polish characters.
 
Technical requirements:
1. Application must be written in JVM language (Java, Scala, Kotlin etc.)
2. Operations must be exposed as REST services
3. No need to stick to any particular database - relational, NoSQL or in-memory
database is fine
4. No need to build frontend
