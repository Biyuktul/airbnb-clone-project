# airbnb-clone

A full-stack Airbnb clone, focusing mainly on backend (server, database, API, security).

# Technology Stack
- Django - a web framework for building RESTful APIs.
- MySQL - A relational database.
- GraphQL - A non relational database.
- PostgreSQL - A relational database.
- Jenkins - tool to automate the deployment and testing process.
- Docker - for contenerizing the code.
- Github - for code base and management and collaboration.

# Feature Breakdown
- user management
- property management
- booking system

# API Security
- authentication
- authorization
- rate limiting

# Database Design
- Users:
    A user can have multiple properties (One-to-Many with Properties).
    A user can make multiple bookings (One-to-Many with Bookings).
    A user can leave multiple reviews (One-to-Many with Reviews).
- Properties:
    Each property belongs to one user (Many-to-One with Users).
    A property can have multiple bookings (One-to-Many with Bookings).
    A property can have multiple reviews (One-to-Many with Reviews).
- Bookings:
    A booking belongs to one user (Many-to-One with Users).
    A booking belongs to one property (Many-to-One with Properties).
    A booking is linked to one payment (One-to-One with Payments).
- Reviews:
    A review belongs to one user (Many-to-One with Users).
    A review belongs to one property (Many-to-One with Properties).
- Payments:
    A payment is linked to one booking (One-to-One with Bookings).

# CI/CD Pipeline
- GitHub Actions
- Docker
- Jenkins

# Team Roles
- Project manager (PM) - Makes sure a product is delivered on time and within budget and also Manages and motivates the software development team.
- Backend Developer - Implement the core of an app—its algorithms and business logic.
- Database Administrator - Design the DB.
- Devops Engineer - Facilitates cooperation between development and operations teams and Builds continuous integration and continuous delivery (CI/CD) pipelines for faster delivery.
- QA Tester - Makes sure an application performs according to requirements.
