# Expense-Tracker
💸 Lightweight Expense Tracker – Pure HTML, CSS &amp; JS!  A no-frills, expense manager to track spending, set budgets, and visualize trends—zero frameworks, just vanilla magi


## 📌 Overview

The Expense Tracker is a lightweight, browser-based web application that helps users manage their personal finances by tracking income and expenses. It’s fully functional offline and designed to give a quick and clear view of daily financial habits. Built using HTML, CSS, and JavaScript, this project promotes minimalism, simplicity, and performance without depending on external databases.




## 🏗️ System Architecture

Frontend (Client-side):

Built using HTML, CSS, and Vanilla JavaScript

Provides a user-friendly interface for adding and managing transactions


Transaction Logic:

JavaScript functions handle core operations:

Add/delete transactions

Calculate income, expenses, and balance

Update the DOM dynamically



Data Storage:

Uses Web Local Storage (localStorage) to store user data

Ensures data persistence even after page reloads

No backend or server required


Rendering Engine:

Updates the UI in real-time as data changes

Reflects the latest balance and transaction history instantly

  




## 🧩 Key Components

HTML Structure – Page layout for input forms, transaction list, and balance summary.

CSS Styling – Responsive design for mobile and desktop with optional themes.

JavaScript Logic:

Add/delete transactions

Calculate income, expenses, and balance

Persist data using localStorage


Transaction List UI – Shows all previous records in chronological order.





## 🔁 Data Flow

1. User inputs a new transaction (amount + description + type).


2. The JavaScript logic processes the input and updates the transaction array.


3. Local Storage is updated with the new transaction data.


4. The UI re-renders to reflect the new balance and transaction list.





## 🔗 External Dependencies

> None.
The application works completely offline using vanilla JavaScript and browser localStorage. No external libraries or APIs are required.






## 🚀 Deployment Strategy

You can deploy this project using:

GitHub Pages (free hosting)

Netlify or Vercel (drag-and-drop deployment)

Run locally by just opening the index.html file in any browser.





## 📝 Changelog

June 22, 2025 – Initial setup with basic features:

Add/Delete transactions

Balance & history view

Local storage integration






## ⚙️ User Preferences

Fully responsive on mobile and desktop.

Online support – internet required after first load.

Quick UX – no login, no delay, just add and track.

