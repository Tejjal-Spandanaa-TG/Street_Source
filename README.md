# Street Food Vendor Management System

A full-stack web application designed to manage street food vendors, suppliers, volunteers, products, and overall marketplace operations. This system provides role-based dashboards, product management, earnings tracking, and a clean UI for real-time interaction between users and the database.

---

## Features

### User Management

* Vendor, Supplier, and Volunteer registration
* Role-based login and dashboards
* Profile management with detailed attributes for each role

### Vendor Dashboard

* Product listing and management
* Add, edit, update, and delete products
* Real-time reflection of database updates
* Ratings, reviews, and earnings overview

### Supplier Dashboard

* Supply management
* Specialization tracking
* Order statistics

### Volunteer Dashboard

* Delivery tracking metrics
* Availability and emergency details

### General Modules

* Notifications center
* Reviews and feedback
* Data visualization and performance metrics

---

## Technology Stack

### Frontend

* Next.js
* React
* Tailwind CSS

### Backend

* Node.js
* Express.js
* REST API Architecture

### Database

* MySQL
* MySQL Workbench

---

## Project Structure

```
street-food-vendor-app/
│
├── app/                 # Frontend pages and components
├── backend/             # Backend API and database connection
├── scripts/             # Database initialization scripts
├── public/              # Assets
├── .env.local           # Environment variables
└── README.md
```

---

## Database Setup

1. Install MySQL and open MySQL Workbench.
2. Create a new database:

   ```sql
   CREATE DATABASE streetsource;
   ```
3. Run the schema:

   ```
   scripts/database-schema.sql
   ```
4. Seed initial users, vendors, or products as needed.

To reinitialize:

```
node scripts/init-database.js
```

---

## Environment Variables

Create `.env.local` at the project root:

```
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=yourpassword
DB_NAME=streetsource
DB_PORT=3306
```

---

## Running the Project

### 1. Install Dependencies

```
npm install
```

### 2. Start the Backend

```
npm run server
```

### 3. Start the Frontend

```
npm run dev
```

Visit:

```
http://localhost:3000
```

---

## CRUD Demo

The project includes full CRUD operations for products.
Actions include:

* Adding new products from MySQL Workbench or UI
* Editing or updating product details
* Deleting products
* Automatically showing updated products on the vendor dashboard

---

## GitHub Setup

### Initializing the repository

```
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/your-username/your-repo-name.git
git push -u origin main
```

---

## Contribution Guidelines

Pull requests are welcome.
For major changes, please open an issue first to discuss what you would like to modify.

---


