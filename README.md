# DBS-Database-PROJECT-SE4
Project of database management system
The Integrated Event Creation & Tracking System is a database-driven platform designed to
manage events, attendees, tickets, venues, and payments efficiently. The system allows event
creators to add and manage events with details like name, date, time, type, and venue. Attendees
can register for events, receive tickets, and their registration is linked with payments for accurate
tracking.
The relational database implements tables for EventCreator, Event, Attendee, Ticket,
Registration, Payment, Venue, EventType, and EventVenue, ensuring data consistency and
enforcing business rules such as preventing overbooking of tickets and linking each registration
to a payment. CRUD operations are supported for all entities, allowing creation, reading,
updating, and deletion of data.
Additionally, triggers automatically update ticket availability or stock after registration, and
views provide quick access to critical information, such as high-priority events or topcontributing donors. With sample data and relational constraints, the system enables real-time
updates, reporting, and analytics, supporting stakeholders like event creators, attendees,
administrators, and finance staff to efficiently plan, track, and analyze events.
