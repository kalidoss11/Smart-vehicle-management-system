# 🚘 FrontendParkingApp

A dynamic and responsive **Angular frontend** for a smart parking management system. This application enables company employees (managers and team leaders) to reserve parking spots, manage their vehicles, view their reservation history, and interact with a live dashboard. It is tightly integrated with a Spring Boot backend API.

## 🌐 Overview

The interface provides:

- Secure user login and registration
- Visual dashboard for administrators
- Parking spot listing and booking system
- Reservation tracking for users
- Profile management
- Detailed **statistics and charts** for usage insights

---

## ⚙️ Technologies Used

- **Angular**
- **TypeScript**
- **RxJS**
- **Angular Router**
- **JWT-based auth interceptor**
- **NgCharts / Chart.js** for statistics
- **Bootstrap** or custom SCSS for styling

---

## 📁 Project Structure (Highlights)

```
src/app/
├── Component/
│   ├── accueil/             # Landing/home page
│   ├── dashboard/           # Admin visual dashboard
│   ├── parking/             # Parking space listings
│   ├── profile/             # Profile view & edit
│   ├── reservations/        # Booking and history
│   ├── statistics/          # Analytics & charts
│   └── user/                # User-related UI components
├── Guards/                  # Route protection
├── Service/                 # Auth, parking, reservation services
├── login/                   # Login page
├── registration-form/       # User registration
├── app.module.ts            # Main module
├── app-routing.module.ts    # Route configuration
└── auth.interceptor.ts      # JWT token interceptor
```

---

## 🚀 How to Run Locally

### Prerequisites

- Node.js
- Angular CLI

### Steps

1. **Clone the repository**

```bash
git clone https://github.com/MezhoudMedIsmail/FrontendParkingApp.git
cd FrontendParkingApp
```

2. **Install dependencies**

```bash
npm install
```

3. **Run the app**

```bash
ng serve
```

4. Open your browser and go to `http://localhost:4200`

---

## 🔐 Authentication

- Users must login to access the system
- Auth guard restricts routes based on login state
- JWT tokens are automatically appended to outgoing requests via **auth.interceptor.ts**

---

## 📊 Charts & Statistics

- Admins can access usage charts under the `statistics/` component
- Charts display reservation trends, most-used spots, and user activity
- Built using `NgCharts` (Chart.js wrapper for Angular)

---

## 🤝 Contributing

We welcome feedback and contributions! Fork the project and submit a pull request for improvements or feature suggestions.


---

Built with 💡 using Angular by [MezhoudMedIsmail](https://github.com/MezhoudMedIsmail)
