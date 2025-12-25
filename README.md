# PetBoardingProject

🐾 Gem City Pet Boarding

Gem City Pet Boarding is a practice ASP.NET MVC web application built to demonstrate core MVC concepts, layout management, routing, and UI customization. The project simulates a pet boarding facility where public users, registered users, and administrators each interact with the site through role-specific layouts and navigation.

This project was developed as part of structured MVC training and later enhanced for portfolio presentation.

✨ Key Features
🧱 MVC Architecture

Controllers handle routing and server-side logic

Views (.cshtml) render dynamic HTML to the client

Layouts provide shared structure and navigation

🎨 Multiple Layouts

The application supports three distinct layouts:

Public Layout

Home

Hours

Contact Us

User Layout

My Account

Manage Pets

Manage Bookings

Admin Layout

Admin Home

Manage Pets

Manage Bookings

Each layout uses its own navigation bar while sharing a consistent visual theme.

🧭 Navigation & Routing

Razor Html.ActionLink is used for strongly typed routing

Each page includes a visible heading confirming the active view

Navigation routes are wired explicitly to their corresponding controllers and actions

🎨 UI & Styling

Custom dark theme inspired by University of Dayton colors

Animated gradient navbar

Card-style content containers for readability

Unified color variables using CSS custom properties

Custom favicon generated and integrated into the project

📁 Project Structure
Controllers/
  HomeController.cs
  HoursController.cs
  ContactUsController.cs
  MyAccountController.cs
  PetsController.cs
  BookingsController.cs
  AdminController.cs

Views/
  Shared/
    _Layout.cshtml
    _UserLayout.cshtml
    _AdminLayout.cshtml
  Home/
  Hours/
  ContactUs/
  MyAccount/
  Pets/
  Bookings/
  Admin/

Content/
  Site.css

🧠 What This Project Demonstrates

Understanding of ASP.NET MVC fundamentals

Layout inheritance and overrides using Razor

Clean separation of concerns

Custom theming layered on top of Bootstrap

Debugging static assets (CSS, favicon, caching, IIS behavior)

Git workflow and version control best practices

🚀 Future Enhancements (Planned)

Pet and booking data models

CRUD functionality for pets and reservations

Role-based authorization

Pricing and availability views

Enhanced home page content (cards, carousel, CTA sections)

🛠️ Tech Stack

ASP.NET MVC (C#)

Razor Views

Bootstrap

CSS (custom theming + animation)

IIS Express

Git & GitHub

👤 Author

Vincent Ryan Arceo
Software Developer | Realtor | Musician
📍 Dayton, OH
