project-root/
├── 📂 public/
├── 📂 routes/
├── 📂 views/
├── 📂 models/
├── app.js
├── package.json
└── README.md


user-auth-system/
├── 📂 config/
│   ├── database.js
│   ├── environment.js
│   └── passport.js
├── 📂 controllers/
│   ├── authController.js
│   ├── userController.js
│   └── dashboardController.js
├── 📂 middleware/
│   ├── auth.js
│   ├── validation.js
│   ├── errorHandler.js
│   └── rateLimiter.js
├── 📂 models/
│   └── User.js
├── 📂 routes/
│   ├── auth.js
│   ├── users.js
│   ├── dashboard.js
│   └── index.js
├── 📂 public/
│   ├── 📂 css/
│   │   ├── bootstrap.min.css
│   │   ├── style.css
│   │   └── auth.css
│   ├── 📂 js/
│   │   ├── bootstrap.min.js
│   │   ├── validation.js
│   │   └── main.js
│   ├── 📂 images/
│   │   └── logo.png
│   └── 📂 assets/
│       └── favicon.ico
├── 📂 views/
│   ├── 📂 partials/
│   │   ├── header.ejs
│   │   ├── footer.ejs
│   │   ├── navbar.ejs
│   │   └─lt─ messages.ejs
│   ├── auth/
│   │   ├── login.ejs
│   │   ├── register.ejs
│   │   └── forgot-password.ejs
│   ├── dashboard/
│   │   ├── index.ejs
│   │   ├── profile.ejs
│   │   └── settings.ejs
│   ├── errors/
│   │   ├── 404.ejs
│   │   └── 500.ejs
│   └── layout.ejs
├── 📂 utils/
│   ├── helpers.js
│   ├── validators.js
│   └── tokenGenerator.js
├── 📂 tests/
│   ├── auth.test.js
│   ├── user.test.js
│   └── setup.test.js
├── 📂 docs/
│   ├── API.md
│   └── SETUP.md
├── .env
├── .env.example
├── .gitignore
├── package.json
├── server.js
├── README.md
└── ecosystem.config.js
