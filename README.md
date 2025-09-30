# Railway Reservation System (JSP + Servlets + MySQL)

A full-stack web application that allows customers to search train schedules, book/cancel reservations, and view booking history. Includes dedicated roles for Customers, Representatives, and Admins.

---

## Features
- Search schedules and make reservations
- Role-based UIs (Customer/Rep/Admin)
- Secure login system with session management
- Representatives can respond to customer questions
- Admins can view monthly sales reports and revenue breakdowns
- Automated fare calculation by distance/line with discounts and round-trip support

---

## Tech Stack
- **Frontend:** JSP, HTML/CSS (embedded modern styling)
- **Backend:** Java Servlets, JDBC
- **Database:** MySQL (schema provided in `DatabaseSQL (1).sql`)

---

## Database
Key tables include:
- `Customer`, `Employee`
- `Station`, `Transit_Line`, `Train`, `Train_Schedule`
- `Schedule_Stop`, `Reservation`, `Customer_Questions`

> To set up locally, import `DatabaseSQL (1).sql` into MySQL.

---

## How to Run Locally
1. Create a MySQL database (e.g., `railwaydb`) and import `DatabaseSQL (1).sql`.
2. Update DB credentials in your app (e.g., `db.properties` or servlet context).
3. Deploy the project on Apache Tomcat.
4. Open `http://localhost:8080/railway/` in your browser.

---

## Download
- [Latest release ZIP](https://github.com/Siddiq2shah/railway-reservation-system/releases) (Login system + DB schema)

---

## Project Structure
