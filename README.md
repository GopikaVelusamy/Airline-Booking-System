# Airline-Booking-System

A console-based airline ticket booking and management system built with Python and Pandas. This project simulates a real-world airline reservation workflow — from setting up airlines and classes to booking, searching, and cancelling tickets.

# Features

Airline Setup — Configure multiple airlines and travel classes with available seat counts
Ticket Booking — Collect customer details, validate input, auto-generate unique 7-digit ticket numbers, and confirm bookings
Customer Records — Maintain an up-to-date passenger list after every booking
Ticket Lookup — Search for a passenger's details using their ticket number
Ticket Cancellation — Cancel a booking by ticket number and automatically restore seat availability
Flight Manifest — View and export all passengers per flight as individual CSV files
Passenger Export — Save all booking records to a Passenger.csv file

# Future Enhancements

Add price/fare management per class
Implement date and route-based filtering
Add a GUI using Tkinter or a web interface with Flask/Streamlit
Persist data using a database (SQLite / PostgreSQL) instead of in-memory DataFrames
Add input validation with error handling instead of re-prompting

