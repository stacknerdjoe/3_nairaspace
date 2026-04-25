# Nairaspace — The Subscription Tracker

A clean and intuitive web app to help you measure, analyse, and take control of all your subscriptions in one place.

🔗 **Live Demo:** [nairaspace.netlify.app](https://nairaspace.netlify.app)

![Nairaspace Dashboard](./screenshot.png)

---

## ✨ Features

- 🔐 **User Authentication** — Secure sign up and login with Firebase Auth
- ➕ **Add Subscriptions** — Track any subscription with name, category, cost, currency, billing frequency, start date, status, and notes
- ✏️ **Edit & Delete** — Update or remove subscriptions at any time
- 📊 **Subscription Analytics** — At-a-glance metrics including:
  - Total Monthly & Yearly Cost
  - Average Monthly Spending
  - Active Subscriptions Count
  - Top Spending Category
  - Upcoming Billing Count
  - Most Expensive Subscription
- 📅 **Renewal Tracking** — See when each subscription started and how many days until the next charge
- 🏷️ **Status Badges** — Mark subscriptions as Active, Paused, or Cancelled
- 💾 **Persistent Storage** — All data saved to Firebase Firestore per user

---

## 🛠️ Built With

- [Next.js](https://nextjs.org/) — React framework for server-side rendering
- [React](https://reactjs.org/) — Frontend UI library
- [Firebase](https://firebase.google.com/) — Authentication and Firestore database
- [FantaCSS](https://fantacss.smashing.com/) — CSS styling framework

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) v18 or higher
- npm (comes with Node.js)
- A [Firebase](https://firebase.google.com/) project with Auth and Firestore enabled

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/stacknerdjoe/your-repo-name.git
   ```

2. **Navigate into the project directory**
   ```bash
   cd your-repo-name
   ```

3. **Install dependencies**
   ```bash
   npm install
   ```

4. **Set up environment variables**

   Create a `.env` file in the root of your project and add your Firebase config:
   ```
   NEXT_PUBLIC_FIREBASE_APIKEY=your_api_key
   NEXT_PUBLIC_FIREBASE_AUTHDOMAIN=your_auth_domain
   NEXT_PUBLIC_FIREBASE_PROJECTID=your_project_id
   NEXT_PUBLIC_FIREBASE_STORAGEBUCKET=your_storage_bucket
   NEXT_PUBLIC_FIREBASE_MESSAGINGSENDERID=your_messaging_sender_id
   NEXT_PUBLIC_FIREBASE_APPID=your_app_id
   NEXT_PUBLIC_FIREBASE_MEASUREMENTID=your_measurement_id
   ```

5. **Run the development server**
   ```bash
   npm run dev
   ```

6. **Open your browser and visit**
   ```
   http://localhost:3000
   ```

---

## 📁 Project Structure

```
app/
├── dashboard/
│   └── page.js              # Dashboard page (protected)
├── layout.js                # Root layout
└── page.js                  # Landing/home page

components/
├── Login.jsx                # Auth form (login & register)
├── SubscriptionDisplay.jsx  # Subscription cards list
├── SubscriptionForm.jsx     # Add/edit subscription form
├── SubscriptionSummary.jsx  # Analytics overview
├── Hero.jsx                 # Landing page hero section
└── GoTo.jsx                 # Navigation auth buttons

context/
└── AuthContext.jsx          # Firebase auth & Firestore logic
```

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/stacknerdjoe/your-repo-name/issues).

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 👨‍💻 Author

**Joseph Onyenemerem**

- GitHub: [@stacknerdjoe](https://github.com/stacknerdjoe/3_nairaspace)
- Live App: [nairaspace.netlify.app](https://nairaspace.netlify.app)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

© Copyright 2026-2027, Joseph Onyenemerem. All rights reserved.