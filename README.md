# Pitchers Showdown

Pitchers Showdown is an interactive platform by the Entrepreneurship Cell of VIT Chennai where users can pitch business ideas, explore other ventures, and invest virtual currency. The project combines **real-time engagement**, **secure authentication**, and **scalable backend architecture** to create a dynamic entrepreneurship ecosystem.

---

## 🚀 Features

- **User Authentication & Authorization**
  - Secure login and signup using JWT and session-based authentication
  - Middleware protection for restricted routes
- **Business Pitch Management**
  - Submit new pitches
  - Browse and invest in other pitches
- **Virtual Investment System**
  - In-app currency (Rbalance) for investing in ideas
  - Track investments and returns
- **Responsive Frontend**
  - Modern and interactive UI for smooth navigation
- **Scalable Backend**
  - Built on Node.js and Express.js with MongoDB as the database
- **Club Transparency**
  - Open-source under AGPL v3 to encourage collaboration and learning

---

## 🛠 Tech Stack

**Frontend:**
- HTML5, CSS3, JavaScript
- React.js (Vite setup)
- Responsive design principles

**Backend:**
- Node.js
- Express.js
- MongoDB with Mongoose

**Authentication:**
- JSON Web Tokens (JWT)
- Express Sessions

**Other Tools:**
- dotenv for environment configuration
- bcrypt for password hashing
- nodemon for development

---

## 📂 Project Structure

```
Pitchers-Showdown/
├── server/
│   ├── controllers/
│   │   ├── BusinessList.js
│   │   └── authController.js
│   ├── middleware/
│   │   └── middleware.js
│   ├── models/
│   │   ├── init.js
│   │   ├── pitcher.js
│   │   └── user.js
│   ├── routes/
│   │   ├── BusinessInfo.js
│   │   └── authRoutes.js
│   ├── server.js
│   ├── package.json
│   ├── package-lock.json
│   └── .env.example
├── client/
│   ├── public/
│   │   └── vite.svg
│   ├── src/
│   │   ├── App.css
│   │   ├── App.jsx
│   │   ├── index.css
│   │   ├── main.jsx
│   │   └── assets/
│   │       └── react.svg
│   ├── eslint.config.js
│   ├── index.html
│   ├── package.json
│   ├── README.md
│   ├── vite.config.js
│   └── .gitignore
├── LICENSE
├── README.md
└── .gitignore

```

---

## ⚙️ Installation

### Prerequisites
- Node.js >= 16
- MongoDB (local or cloud via MongoDB Atlas)
- npm or yarn

### Steps
1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-org-or-username>/pitchers-showdown.git
   cd pitchers-showdown
   ```

2. **Install backend dependencies**
   ```bash
   cd server
   npm install
   ```

3. **Install frontend dependencies**
   ```bash
   cd ../client
   npm install
   ```

4. **Set environment variables**
   Create a `.env` file inside the `server` directory based on `.env.example`:
   ```env
   PORT=5000
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```

5. **Run the backend server**
   ```bash
   cd server
   npm run dev
   ```

6. **Run the frontend**
   ```bash
   cd client
   npm run dev
   ```
   The frontend will run at `http://localhost:5173` (default Vite port).

---

## 📌 Usage

- **Sign up / Login** to create your account.
- **Pitch an idea** using the "Add Pitch" option.
- **Browse pitches** submitted by other users.
- **Invest** using your virtual currency.
- **Track** your investments and earnings.

---

## 🤝 Contributing

We welcome contributions from developers, designers, and enthusiasts.  
To contribute:

1. Fork the repo
2. Create a new branch (`feature/your-feature`)
3. Commit your changes
4. Push to your fork and open a Pull Request

Please follow the [Code of Conduct](CODE_OF_CONDUCT.md) if available.

---

## 📜 License

This project is licensed under the **GNU Affero General Public License v3.0**  
See the [LICENSE](LICENSE) file for details.

---

## 👥 Maintainers

- **Entrepreneurship Cell, VIT Chennai** – [Official Website](https://ecell-vit.vercel.app/)
- Technical Team – Backend & Full Stack Development
- Design Team – UI/UX & Branding

---

> 💡 _This project is maintained by the Entrepreneurship Cell of VITC. It is open-source for learning and collaboration but modifications must remain open as per AGPL v3._
