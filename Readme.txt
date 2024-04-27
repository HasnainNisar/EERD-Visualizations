Hotel Management System ER Diagram
This repository contains an Enhanced Entity-Relationship Diagram (ERD) for a hotel management system. The ERD visually represents the database design for efficiently managing hotel operations. Below are the key components:

Entities:
Guests: Track guest information (name, contact details, nationality, preferences).
Rooms: Maintain room details (number, type, rate, availability).
Reservations: Record guest reservations (guest ID, room ID, dates, requests).
Staff: Store staff information (name, position, contact, schedule).
Billing: Track charges incurred during guest stays.
Relationships:
Guests reserve Rooms.
Rooms are assigned to Reservations.
Staff manage Reservations.
Billing is linked to Reservations.
Constraints:
Ensure unique IDs for Guests, Rooms, Staff.
Prevent double-booking of Rooms.