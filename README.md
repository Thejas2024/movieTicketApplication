🏗️ Tech Stack
Frontend

React.js

Tailwind CSS

React Router

Context API / Redux (booking state)

HTML / CSS / JavaScript

Backend

Node.js

Express.js

REST APIs

Database (MongoDB / MySQL / PostgreSQL – choose based on your project)

📌 Features (Up to Payment Section)
✔️ 1. Event Browsing

Interactive homepage with event cards

List of movies/concerts/shows/bus schedules (customizable)

Event details page with date, time, venue, and pricing

✔️ 2. Seat Selection

Dynamic seat layout rendered in React

Tailwind styling for:

Available seats

Selected seats

Reserved / Sold seats

Live price calculation based on selected seats

Validation to prevent double selection

✔️ 3. Booking Summary

Displays selected seats

Event details

Subtotal, taxes, convenience fee

Promo code handler (optional)

✔️ 4. Checkout & User Info

Collects customer name, mobile number, and email

Server creates a provisional booking and reserves selected seats for a fixed time (e.g., 10–15 minutes)

✔️ 5. Payments Section (Created, Not Finalized)

Payment form UI built using React + Tailwind

Backend route generates:

Payment Intent (Stripe)

or Payment Order (Razorpay)

Client receives clientSecret or orderId

Pending: final payment confirmation & webhook handling

📍 This project includes the entire payment flow setup up to creation, but does NOT include settlement or gateway callbacks.



<img width="1890" height="900" alt="image" src="https://github.com/user-attachments/assets/366c513d-2ff8-4de1-a096-0cc98d1f003d" />
