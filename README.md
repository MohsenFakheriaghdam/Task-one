# Task Two - User Account Dashboard

## Overview

This project is a responsive user account dashboard built as part of a coding bootcamp assignment. It showcases a clean, modern UI for displaying user account information, navigation menu, order statuses, and a list of recent orders. The design is fully in Persian (RTL) and uses semantic HTML and CSS for styling.

## Features

- **User Account Information**: Displays user name, phone number, and edit icon.
- **Navigation Menu**: Includes options like "My Orders", "Account Info", "Messages" with notification badges, "My Reviews", and "Logout".
- **Order Status Dashboard**: Visual cards showing counts for orders in different states:
    - Processing (در حال پردازش)
    - Delivered (تحویل شده)
    - Returns (مرجوعی)
    - Canceled (لغو شده)
- **Order List**: Detailed view of individual orders with:
    - Order code and delivery date
    - Total price
    - Product images with quantities
    - Status indicators

## Technologies Used

- **HTML5**: Semantic markup for structure
- **CSS3**: Responsive design with Grid and Flexbox layouts
- **Vazirmatn Font**: Persian typography for RTL text
- **SVG Icons**: Custom vector graphics for UI elements

## Project Structure

```
Task-tow/
├── public/
│   └── index.html          # Main HTML file
├── src/
│   ├── css/
│   │   └── main.css        # Main stylesheet
│   ├── fonts/
│   │   └── Vazirmatn-font-face.css  # Font definitions
│   ├── img/
│   │   ├── product 1.png   # Product images
│   │   ├── product 2.png
│   │   └── product 3.png
│   └── svg/                # SVG icons
│       ├── User.svg
│       ├── home.svg
│       └── ... (other icons)
└── README.md               # This file
```

## How to View

1. Clone or download the repository
2. Open `public/index.html` in your web browser
3. The page is fully static and requires no server setup

## Design Notes

- **RTL Layout**: Designed for right-to-left reading with `dir="rtl"`
- **Responsive**: Uses CSS Grid and Flexbox for mobile-friendly layout
- **Color Scheme**: Clean design with status-specific colors (blue for processing, green for delivered, etc.)
- **Typography**: Consistent use of Vazirmatn font family for Persian text

## Bootcamp Context

This project was created as Task Two in an HTML & CSS bootcamp course, demonstrating proficiency in:

- Semantic HTML structure
- CSS layout techniques (Grid, Flexbox)
- Responsive design principles
- Working with custom fonts and SVG assets
- RTL (Right-to-Left) layout for Persian content
