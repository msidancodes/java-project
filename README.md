# Smart Parking Management System

Java Swing + JDBC + MySQL MVP for PBCST304.

## 1. Database
Open MySQL Workbench and run `src/main/resources/schema.sql`.

The schema creates:
- `smart_parking` database
- demo admin/user accounts
- parking slots

## 2. Database connection
Open:
`src/main/java/com/smartparking/DB.java`

Change:
- DB_USER
- DB_PASSWORD

Default database:
`jdbc:mysql://localhost:3306/smart_parking`

## 3. Run
Requirements:
- JDK 17+
- MySQL 8+
- Maven

From the project folder:
`mvn clean compile exec:java`

## Demo login
Admin:
- username: admin
- password: admin123

User:
- username: user
- password: user123

## Current MVP
- Login
- Role-based dashboard
- Vehicle registration
- Parking slot display
- Intelligent rule-based slot recommendation
- Reservation
- Start/end parking session
- Overstay detection
- Dynamic pricing
- Parking history
- Admin revenue/occupancy summary

No physical sensors are required.
