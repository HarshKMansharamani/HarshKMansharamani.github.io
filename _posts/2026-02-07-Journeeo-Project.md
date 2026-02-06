---
layout: post
title: ✈️ Journeeo - A Travel Assistance Platform
---

## 🚀 The Mission
I recently wrapped up **Journeeo**, a web-based travel assistance project built entirely from scratch.

The goal was simple but ambitious: create a **centralized interface** for travelers to manage their logistics without opening ten different tabs.

## 🛠 Features & Architecture
I focused on three core areas to make the user experience smooth:

### 1. Unified Booking System
I created an aggregated view that brings together different travel partners. Instead of jumping between sites, users can access links for:
* 🚖 Taxi Services
* ✈️ Flight Partners
* 🏨 Hotel Booking

### 2. Information Architecture
Structuring data is key for any travel site. I designed **Pricing Tables** and destination guides that allow users to compare costs at a glance.

### 3. Visual Design & Responsiveness
Using **CSS3**, I built custom navigation bars and image galleries that adjust to different screen sizes.

## 💻 A Peek at the Code
Here is a snippet of the CSS used to style the navigation bar, ensuring it looks clean and modern:

```css
/* Navigation Bar Styling */
.navbar {
    display: flex;
    justify-content: space-between;
    background-color: #333;
    padding: 1rem;
}

.nav-links a {
    color: white;
    text-decoration: none;
    padding: 0 15px;
    transition: color 0.3s ease;
}

.nav-links a:hover {
    color: #ff7e5f; /* Brand accent color */
}
