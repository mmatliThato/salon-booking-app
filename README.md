# Bloom & Braid — Salon Booking App

A responsive React + Vite salon appointment booking demo.

## Run locally

```bash
npm install
npm run dev
```

Open the local URL printed by Vite (usually http://localhost:5173).

## Features
- Browse and filter salon services and prices
- Select a service, appointment date (next 14 days), and time
- Collect customer name, phone, and email
- Save, view, and cancel bookings in browser localStorage
- Prevent duplicate booking of the same time on the same device
- Responsive layout

## Important: prototype limits
Bookings are saved **only in the current browser**. They are not shared across devices; they may be lost if browser storage is cleared. There is no authentication, payment processing, notification delivery, server-side time-zone handling, or real live salon availability. Time-slot validation is a basic demo, not a production scheduling engine. Service hours and prices are illustrative. Do not use the app for real customer bookings until a backend, shared database, authentication, and server-side conflict checks are added.

## Build for deployment

```bash
npm run build
```

Deploy the generated `dist/` directory to a static hosting provider.
