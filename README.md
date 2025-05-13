# 🎬 iCinema

A full-stack **MERN** website for movie theaters that allows users to:

- Browse available films  
- Filter them by categories and ratings  
- Admins can add new films to the list



---

<h2>📦 Installation</h2>

Use the package manager <a href="https://www.npmjs.com/" target="_blank">npm</a> to install iCinema.

<h3>🔁 Fork and Clone the Project</h3>

```bash
git clone https://github.com/orifmilod/iCinema.git
````

<h3>📁 Navigate into the Project</h3>

```bash
cd iCinema
```

<h3>📥 Install Dependencies</h3>

```bash
npm run setup
```

<h3>🚀 Run the Development Server</h3>

```bash
npm run dev
```

Visit `http://localhost:3000` to view the app in your browser.

---

<h2>🛠️ Built With</h2>

<ul>
  <li><strong>Frontend:</strong> React.js, Redux, Bootstrap, HTML, CSS</li>
  <li><strong>Backend:</strong> Node.js, Express.js</li>
  <li><strong>Database:</strong> MongoDB, Mongoose</li>
</ul>

---

<h2>✨ Features</h2>

<ul>
  <li>🔐 User Authentication: Sign Up / Sign In / Sign Out</li>
  <li>📧 Welcome Email via Nodemailer upon registration</li>
  <li>🎬 Admin: Add, Update, and Delete Movies</li>
  <li>🔎 Filter Movies by Genre and Ratings</li>
</ul>

---

<h2>📡 API Endpoints</h2>

<h3>👤 Users</h3>

<ul>
  <li><b>POST</b> /api/auth/signUp – Register a new user</li>
  <li><b>POST</b> /api/auth/signIn – Login existing user</li>
  <li><b>PATCH</b> /api/users/:userId – Update user info</li>
  <li><b>DELETE</b> /api/users/:userId – Delete user</li>
</ul>

<h3>🎥 Movies</h3>

<ul>
  <li><b>GET</b> /api/movies – Get all movies</li>
  <li><b>GET</b> /api/movies/:movieId – Get movie by ID</li>
  <li><b>POST</b> /api/movies/addMovie – Add a new movie</li>
  <li><b>PATCH</b> /api/movies/:movieId – Update movie</li>
</ul>

<h3>🎭 Genres</h3>

<ul>
  <li><b>GET</b> /api/genres – List all genres</li>
</ul>

---

<h2>📁 Folder Structure</h2>

```bash
iCinema/
│
├── client/           # Frontend
│   └── src/
│       ├── components/
│       ├── redux/
│       └── pages/
│
├── server/           # Backend
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   └── utils/
│
├── .env
├── package.json
└── README.md
```

---

<h2>🤝 Contributing</h2>

Want to contribute?
Feel free to fork the repo and submit a pull request. For issues, open a ticket on the [GitHub repository](https://github.com/orifmilod/iCinema).

---

```

---

Let me know if you'd like me to generate a **PDF version** directly or help you style it even more (like adding badges, contact info, or demo links).
```
