# 🛍️ Macaron Shop – Next.js E-Commerce Site

Welcome to the **Macaron Shop** – a project-based e-commerce site built with **Next.js**. This README outlines the project dependencies and explains their roles in enabling a fast, dynamic, and production-ready storefront.

---

## 🚀 Tech Stack Overview

This project is built using the following modern web development tools:

- **Framework**: [Next.js](https://nextjs.org/) (v12)
- **UI**: React 17
- **CMS**: Sanity.io
- **Payments**: Stripe
- **Styling, interactivity, and UI enhancements**: Various React libraries

---

## 📦 Project Dependencies Explained

Here's a breakdown of the key dependencies and how they contribute to the overall functionality of the application:

### 🔧 Framework & Core Libraries

| Package        | Version | Description                                                                 |
|----------------|---------|-----------------------------------------------------------------------------|
| `next`         | 12.1.0  | The core framework for hybrid static & server-rendered React apps.          |
| `react`        | 17.0.2  | The base UI library used to build interactive components.                   |
| `react-dom`    | 17.0.2  | Responsible for rendering React components to the DOM.                      |

---

### 📷 Sanity CMS Integration

| Package                   | Version  | Description                                                                                  |
|---------------------------|----------|----------------------------------------------------------------------------------------------|
| `@sanity/client`          | ^3.4.1   | Official JS client to interact with your Sanity.io content backend.                          |
| `@sanity/image-url`       | ^1.0.1   | Helps generate responsive image URLs from Sanity's image API.                                |
| `next-sanity-image`       | ^3.2.1   | Optimizes and renders Sanity images using Next.js's `<Image>` component.                     |

---

### 💳 Stripe Payments

| Package               | Version  | Description                                                                 |
|-----------------------|----------|-----------------------------------------------------------------------------|
| `stripe`              | ^8.209.0 | Backend library for managing Stripe checkout sessions and webhooks.        |
| `@stripe/stripe-js`   | ^1.25.0  | Frontend library for securely loading Stripe.js and initializing checkout. |

---

### 💅 UI & UX Enhancements

| Package             | Version  | Description                                                                 |
|---------------------|----------|-----------------------------------------------------------------------------|
| `react-icons`       | ^4.7.1   | Collection of popular SVG-based icon packs for easy UI integration.        |
| `react-tabs`        | ^4.2.1   | Simple and accessible tabbed navigation components.                         |
| `react-hot-toast`   | ^2.2.0   | Lightweight, beautiful toast notifications. Great for status updates.      |
| `canvas-confetti`   | ^1.5.1   | Adds fun, customizable confetti animations – perfect for purchase success. |

---

## 📁 Directory Structure (Coming Soon)

We'll soon include a visual overview of how this project is structured, including how these dependencies are integrated.

---

## 📌 Getting Started

```bash
# Install dependencies
npm install

# Run the development server
npm run dev
```

## 🧠 Why This Stack?

The combination of Next.js + Sanity + Stripe offers a robust foundation for building fast, scalable, and customizable e-commerce applications. Lightweight UI tools further enhance the user experience while keeping performance high.
