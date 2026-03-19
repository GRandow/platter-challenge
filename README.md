# 🚀 Platter Challenge - eCommerce Product Grid

A high-performance, fully responsive product grid carousel built as a technical challenge to showcase proficiency in Tailwind CSS, semantic HTML, and Vanilla JavaScript. This project focuses on delivering complex interactive design patterns while maintaining clean code and optimal Core Web Vitals.

## 📋 Challenge Requirements Delivered
This project strictly follows all the constraints and objectives specified in the challenge instructions:

Product Display: Renders a minimum of 10 product cards.

Responsive Layout: fully functional on both desktop and mobile devices.

Mobile-Specific Interaction (Show More):

Only the first 4 products are visible on mobile.

A "Show More" button triggers a smooth dropdown animation to reveal the remaining 6 products.

Interactive Features:

Image Swap on Hover: Hovering over a product image swaps it with a secondary image.

Custom Scrollbar UI: The scrollbar thumb width/height increases to 6px when hovered over or touched.

Specific Tech Stack: Built with semantic HTML, JavaScript (Vanilla JS) for all functionality, and Tailwind CSS.

Placeholders: Used free stock images from Unsplash.

## 🛠 Tech Stack & Tools

HTML5: Semantic markup for improved SEO and accessibility.

CSS3: Tailwind CSS framework used for utility-first styling.

JavaScript (ES6+): Plain Vanilla JS for all dynamic interactions.

## ✨ Implementation Highlights

Smooth Dropdown (Mobile): Implemented using CSS transitions and height manipulation for a clean, non-blocking animation.

Optimized Image Swapping: Pre-loaded or lazy-loaded secondary images to ensure no delay or jank during hover interactions.

Custom Styling: Utilized Tailwind's customization capabilities to create a precise UI matching the requested design and custom scrollbar behavior.

## 📦 How to Run

Clone the repository:

Bash

git init

git remote add origin https://github.com/GRandow/platter-challenge.git

git pull origin main

Open index.html (or your local development environment) to preview.

## 🧠 Engineering Decisions

Choosing Vanilla JavaScript

Instead of relying on heavy third-party carousel or animation libraries, I opted for Vanilla JS. This keeps the initial bundle size incredibly small, crucial for eCommerce stores where fast initial load times are directly linked to conversion rates.
