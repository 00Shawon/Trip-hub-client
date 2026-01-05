# 🎟️ TicketBari — Online Ticket Booking Platform

## 📌 Project Overview

**TicketBari** is a full-stack **Online Ticket Booking Platform** built using the **MERN stack**. The application enables users to discover and book travel tickets (Bus, Train, Launch, Plane), while vendors manage ticket listings and bookings, and administrators oversee approvals, advertisements, and user roles.

The system is fully **role-based** (User, Vendor, Admin) and includes secure authentication, real-time booking workflows, and online payment integration.

---

## 🌐 Live Links

- **Live Website:** https://your-live-site-link.com  
- **Server API:** https://your-server-link.com  

---

## 🚀 Key Features

### 🔐 Authentication & Authorization
- Email & Password registration and login
- Google social login
- Password validation (uppercase, lowercase, minimum 6 characters)
- Role-based protected routes
- Persistent login on page reload
- Firebase authentication secured with environment variables

---

### 🏠 Home Page
- Hero banner / slider
- Advertisement section (maximum 6 admin-selected tickets)
- Latest tickets showcase
- Informative sections (Why Choose Us, Popular Routes, etc.)
- Fully responsive design (mobile, tablet, desktop)

---

### 🎫 All Tickets Page
- Displays admin-approved tickets only
- Search tickets by route (From → To)
- Filter by transport type
- Pagination for optimized performance
- Navigation to detailed ticket view

---

### 📄 Ticket Details (Protected)
- Complete ticket information
- Real-time countdown based on departure date & time
- “Book Now” modal with quantity validation
- Booking disabled automatically for expired or sold-out tickets

---

## 📊 Dashboard System

### 👤 User Dashboard
- User profile management
- View booked tickets
- Booking status: pending / accepted / rejected / paid
- Stripe payment integration
- Departure countdown
- Transaction history

---

### 🧑‍💼 Vendor Dashboard
- Vendor profile
- Add tickets (image upload via imgbb)
- Manage added tickets (update / delete)
- Handle booking requests (accept / reject)
- Revenue overview with charts

---

### 🛡️ Admin Dashboard
- Admin profile
- Approve or reject tickets
- Manage users (assign admin/vendor roles, mark fraud)
- Control advertisements (maximum 6 active tickets)
- Automatic hiding of tickets from fraud vendors

---

### 💳 Payment System
- Secure Stripe payment integration
- Automatic ticket quantity reduction after successful payment
- Payment and transaction history tracking

---

## 🛠️ Technologies Used

### 🔵 Frontend
- React 19
- React Router
- TanStack React Query
- Axios
- Firebase Authentication
- Tailwind CSS & DaisyUI
- Swiper & React Responsive Carousel
- React Hook Form
- SweetAlert2 & React Hot Toast
- Recharts
- Lucide Icons

---

### 🟢 Backend
- Node.js
- Express.js
- MongoDB
- Firebase Admin SDK
- Stripe
- dotenv
- CORS

---

## 📦 Dependencies

### Client
@tanstack/react-query
axios
firebase
react
react-router
react-hook-form
tailwindcss
daisyui
swiper
recharts
sweetalert2
react-hot-toast

📦 Dependencies
### Server
express
mongodb
cors
dotenv
firebase-admin
stripe

🔐 Security

Firebase config secured using environment variables

MongoDB credentials hidden via .env

JWT-based secure API access

CORS properly configured for production

📈 Commit History

✅ 20+ meaningful commits on client side

✅ 12+ meaningful commits on server side

Clear and descriptive commit messages

📱 Responsiveness & UI

Fully responsive (mobile, tablet, desktop)

Clean layout with consistent spacing

Equal-height cards and grid layouts

Eye-friendly color contrast

Dashboard optimized for data visualization

⚠️ Notes

No page breaks or errors on reload

Private routes persist authentication

Firebase authorized domains configured properly

Server works smoothly in production without CORS / 404 / 504 errors

👨‍💻 Author
SM Mehedi Hasan Shawon
Full Stack MERN Developer
This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) (or [oxc](https://oxc.rs) when used in [rolldown-vite](https://vite.dev/guide/rolldown)) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
