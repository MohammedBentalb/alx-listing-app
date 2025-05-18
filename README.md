# ALX Listing App

## 📌 Project Overview

**ALX Listing App** is a foundational project that aims to replicate the core functionality of an Airbnb-style property listing page. Built using **Next.js**, **TypeScript**, and **Tailwind CSS**, this application serves as the starting point for building a fully responsive and modular booking interface.

This milestone focuses on scaffolding the app with the correct structure, reusable components, and essential configurations to ensure a clean and maintainable codebase.

---

## 🧱 Project Structure

```bash
alx-listing-app/
│
├── components/
│   └── common/
│       ├── Card.tsx        # Reusable Card component for property display
│       └── Button.tsx      # Reusable Button component for UI actions
│
├── constants/
│   └── index.ts            # Centralized file for static data and config values
│
├── interfaces/
│   └── index.ts            # TypeScript interfaces for component props and models
│
├── public/
│   └── assets/             # All images, SVGs, and static assets
│
├── pages/
│   └── index.tsx           # Home page of the app
│
├── styles/
│   └── globals.css         # Global styles using Tailwind directives
│
├── tailwind.config.js      # Tailwind CSS configuration
└── README.md               # Project documentation
```
---

## 🛠️ Tech Stack

- **Framework:** Next.js
- **Language:** TypeScript
- **Styling:** Tailwind CSS
- **Linting:** ESLint (enabled during setup)

---

## 🚀 Getting Started

To run the project locally:

1. **Clone the repository**
   ```bash
   git clone https://github.com/MohammedBentalb/alx-listing-app.git
   cd alx-listing-app 
    ```
2. **Install dependencies**

    ```bash
    npm i
    ```
3. **Start the development server**
    ```bash
    npm run dev
    ```

 - Open your browser Visit http://localhost:3000