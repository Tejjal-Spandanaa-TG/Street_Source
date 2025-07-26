# Street Food Vendor App 🍜

A full-stack web application designed to manage and streamline interactions between customers and street food vendors. Built with Next.js, Neon PostgreSQL, and Tailwind CSS.

![App Screenshot](./assets/screenshot.png)

## 🚀 Features

- Vendor profile management (CRUD)
- Customer reviews and ratings
- Order and earnings tracking
- Admin notifications
- Fully responsive UI
- Connected to Neon Postgres database

## 🗂️ Tech Stack

- **Frontend**: Next.js (App Router), Tailwind CSS
- **Backend**: API Routes (RESTful), Prisma ORM
- **Database**: Neon PostgreSQL
- **Version Control**: Git + GitHub

---

## 🛠️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/street-food-vendor-app.git
cd street-food-vendor-app
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Set Up Environment Variables

Create a `.env` file in the root and add:

```env
DATABASE_URL=your_neon_postgres_url
```

Replace with your Neon PostgreSQL connection string.

### 4. Generate Prisma Client

```bash
npx prisma generate
```

---

## 🔄 Database Setup

Run the following to apply schema to your database:

```bash
npx prisma db push
```

(Optional: Seed or reset DB if needed)

---

## 🧪 Running Locally

```bash
npm run dev
```

Visit: [http://localhost:3000](http://localhost:3000)

---

## 🔍 Demo Flow for CRUD (e.g. Vendors Table)

1. Navigate to `/vendors`
2. Create a new vendor using the **Add Vendor** form.
3. Edit or delete existing vendor entries.
4. Observe updates reflected in the database (Neon Postgres).
5. CRUD operations are connected to `/api/vendors` endpoints.

---

## 📸 Screenshot

*(You can replace the image with the actual UI screenshot)*

![Vendor Table UI](./assets/vendors.png)

---

## 📬 Contact

For queries, contact: `your.email@example.com`

---

## 📝 License

MIT License © 2025
