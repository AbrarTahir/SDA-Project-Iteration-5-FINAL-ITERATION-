Ride Management System 

A robust Ride Management System built in Java, demonstrating advanced Object-Oriented Programming (OOP) concepts and design patterns. This system streamlines the booking, tracking, and ride management processes for passengers, wheelchair users, and drivers. It emphasizes clean architecture, scalability, and maintainability by leveraging key design patterns such as Singleton, Factory, and Strategy.

Key Features

Admin Panel: Manage passengers, wheelchair users, and drivers effortlessly.

Dynamic Ride Management: Book normal or pre-scheduled rides with options to complete or cancel them.

Inclusive Design: Seamlessly integrates functionality for wheelchair users alongside regular passengers.

Real-Time Tracking: Drivers can track passengers, and passengers can track drivers.

Ride History: View and manage ride records for individual users.

Advanced Cancellation Policies: Flexible handling of normal and pre-scheduled ride cancellations.

Design Patterns Implemented

1. Singleton Pattern
Purpose: Ensure a single instance of critical classes like Admin to centralize and manage global application state.
Implementation: Provides a consistent, shared resource for managing users and rides across the system.

3. Factory Pattern
Purpose: Simplify object creation and decouple code from specific implementations.
Implementation: Handles the creation of Passenger, Driver, and WheelchairUser objects dynamically, making the system extensible for new user types in the future.

5. Strategy Pattern
Purpose: Enable interchangeable and flexible algorithms for specific behaviors.
Implementation: Applied to payment methods, ride cancellation policies, and booking behaviors, allowing easy customization and scalability.

Technologies Used

Java: Core programming language for building the system.
OOP Principles: Encapsulation, Inheritance, Polymorphism, and Abstraction for modular and reusable code.
