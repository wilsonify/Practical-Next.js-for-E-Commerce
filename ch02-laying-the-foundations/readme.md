# 🧁 Macaron E-Commerce Demo

A macaron-themed e-commerce storefront built with **Next.js**.  
This project serves as a learning exercise and is currently in development.


# 📌 Disclaimer

This project is part of a guided tutorial and is not a real store.
All content and functionality are provided for educational purposes only.
> ⚠️ **Not intended for production use.**  
> Please do **not** attempt to place real orders or submit payments.


## 🚀 Overview

This demo replicates the core structure of a modern e-commerce website using React-based components and static routing.  
It provides a foundation for building a functional storefront, with placeholder features to be fully implemented in future chapters.

## ✅ Features Implemented

- Component-based site layout using `Layout.jsx`
- Navigation bar with links to core pages
- Static informational pages:
  - About
  - Contact (includes placeholder form)
  - Terms & Conditions
  - Privacy Policy
  - Delivery Info
- Demo banner to warn users of non-production status
- Footer with navigation links and placeholder payment icons

## 🗂️ Project Structure


├── readme.md                        # Project documentation (this file)
└── src/                             # Main source code for the app
    ├── components/                  # Reusable UI components used across pages
    │   ├── DemoBanner.jsx          # Notification banner (e.g., site is in demo mode)
    │   ├── Footer.jsx              # Footer section with links and icons
    │   ├── index.js                # Central export file for component imports
    │   ├── Layout.jsx              # Wraps pages with consistent structure (Nav + Footer)
    │   ├── NavBar.jsx              # Top navigation bar with links to pages
    │   ├── Newsletter.jsx          # Newsletter signup form component
    │   ├── PaymentIcons.jsx        # Placeholder icons for payment methods
    │   └── PerfectBanner.jsx       # Secondary or featured banner (e.g., promotions)
    ├── images/                     # Static image assets used in the site
    │   ├── frontimage.jpg          # Likely used on the homepage or hero section
    │   ├── newsletter.jpg          # Image associated with the newsletter section
    │   └── perfect.jpg             # Image for PerfectBanner or product showcase
    └── pages/                      # Next.js routing—each file is a separate route
        ├── about.js               # "/about" static page with brand info
        ├── _app.js                # Custom App component to initialize pages and wrap with layout
        ├── contact.js             # "/contact" page with a placeholder form
        ├── delivery.js            # "/delivery" info page for shipping details
        ├── index.js               # Homepage ("/") entry point
        ├── privacy.js             # "/privacy" policy page
        └── terms.js               # "/terms" and conditions page
        


## 🚀 Getting Started

1. Clone the repo
2. Navigate to the project folder
3. Install dependencies: ```npm install```
4. Start the development server: ```npm run dev```
5. Visit `http://localhost:3000` in your browser


## 📝 Next Steps

- Add styling using Tailwind CSS
- Integrate backend or product data source
- Build MiniCart and cart logic
- Add Stripe integration for payments
- Improve accessibility and SEO metadata
- Make banner dismissible and context-aware
