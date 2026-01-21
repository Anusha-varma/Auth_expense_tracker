
## Expense Tracking System – Angular

This is a web-based Expense Tracking System built using Angular (Standalone Components) and JSON Server.
The application allows authenticated users to manage their personal income and expenses and view a dashboard with their financial summary.


## Screenshots

### Login Page

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/214ecc71-979d-4dee-a56a-8e1395bf14b0" />


### Expense Dashboard

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/899d2ca1-bdac-4335-a8a2-9e0055558d5f" />

### Transaction Form page
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7eaf7476-ed98-46ff-acb2-80b9a2c5a22b" />

## Features

* User authentication (login and registration)
* Route protection using Angular Auth Guards
* Add income and expense transactions
* View income and expense lists separately
* Edit and delete transactions
* Dashboard showing:

  * Total income
  * Total expenses
  * Net balance
* User-specific data visibility
* Data stored using JSON Server (`db.json`)
* Clean and responsive user interface


## Tech Stack

* Angular (Standalone Components)
* TypeScript
* JSON Server
* Angular Router and Auth Guards
* HTML and CSS


## How to Run

1. Install dependencies

   ```bash
   npm install
   ```

2. Start JSON Server

   ```bash
   npx json-server --watch db.json --port 3000
   ```

3. Run Angular application

   ```bash
   ng serve
   ```

4. Open in browser

   ```
   http://localhost:4200
   ```


## Notes

* Each user can view and manage only their own income and expenses
* Auth Guards are used to restrict access to protected routes
* Ensure JSON Server is running before using the application
 Optimize this README for resume or GitHub profile

