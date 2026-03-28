# 🏏 Cricket Premier League

**Cricket Premier League** is a modern and responsive fantasy cricket squad builder where users assemble their ideal team through a clean, interactive, and credit-based selection experience. With dynamic player cards, six-player squad management, and real-time validation, it delivers a focused and engaging team-building journey for cricket fans.

<div align="center">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/DaisyUI-5A0EF8?style=for-the-badge" alt="DaisyUI" />
  <img src="https://img.shields.io/badge/React_Toastify-FF6B6B?style=for-the-badge" alt="React Toastify" />
  <img src="https://img.shields.io/badge/Responsive-Design-green?style=for-the-badge" alt="Responsive Design" />
</div>

## 🔗 Quick Links

- **Live Website:** [cpl-leauge.surge.sh](https://cpl-leauge.surge.sh/)
- **Repository:** [milestone-07-cricketLeague](https://github.com/zahid-official/milestone-07-cricketLeague)

## 🏆 Features of the Cricket Premier League

- **Detailed Player Profiles:** Explore polished player cards that surface key information such as country, role, batting style, bowling style, bidding price, and profile imagery in a clean visual layout.
- **Interactive Squad Builder:** Build your ideal cricket lineup through a selection flow designed to feel simple, engaging, and easy to manage from start to finish.
- **Credit-Based Decision Making:** Use a virtual coin system to select players strategically, adding budget awareness and a game-like layer to the team-building process.
- **Responsive User Experience:** Navigate the platform smoothly across mobile, tablet, and desktop devices with a layout built for consistency on every screen size.

## 🛠️ Technologies Used

| Technology           | Version                          | Purpose                                     |
| :------------------- | :------------------------------- | :------------------------------------------ |
| **React**            | `^18.3.1`                        | Component-based UI development              |
| **JavaScript**       | `ES6+`                           | Application logic and interaction handling  |
| **Tailwind CSS**     | `^3.4.14`                        | Utility-first styling and responsive layout |
| **DaisyUI**          | `^4.12.13`                       | Prebuilt UI components and patterns         |
| **Vite**             | `^8.0.3`                         | Fast development server and build tooling   |
| **React Icons**      | `^5.3.0`                         | Reusable icons for the interface            |
| **React Toastify**   | `^11.0.5`                        | Toast notifications and user feedback       |

## 🎯 Core Mechanics

- **Dynamic Currency System:** Users start with zero coins and can claim free credit before building their squad, creating a clear sense of progression.
- **Available vs Selected Views:** The interface makes it easy to switch between `Available` and `Selected` players, keeping squad building structured and easy to follow.
- **Real-Time Validation:** The app prevents duplicate selections, over-budget choices, and squads larger than six players while keeping the user informed at every step.
- **Instant Feedback:** Toast notifications provide clear success, warning, and error states for important actions such as claiming credit, selecting players, and removing them.
- **Flexible Squad Updates:** Selected players can be removed at any time, making it easy to refine the lineup and explore different combinations.

## 📂 Project Structure

```bash
milestone-07/
├── README.md                # Project documentation
├── package.json             # Dependencies and scripts
├── public/                  # Public assets and data
│   ├── players.json         # Player dataset
│   └── CNAME                # Surge deployment domain
└── src/                     # Application source code
    ├── App.jsx              # Root application component
    ├── main.jsx             # React entry point
    ├── index.css            # Global styles
    └── components/          # UI components
```

## ⚙️ How It Works

1. Claim free credit to add balance to your account
2. Browse player cards loaded from `public/players.json`
3. Select players based on your available coin balance
4. Manage your squad through the `Available` and `Selected` views
5. Receive instant validation and toast feedback for every key action

## ✅ Selection Rules

- A user must claim credit before selecting players
- A player cannot be selected more than once
- A squad can contain a maximum of **6 players**
- A player can only be selected if the available coin balance is sufficient
- Selected players can be removed and replaced at any time

## 📋 Prerequisites

- **Node.js** and **npm** installed on your machine
- A modern browser for local development preview

## 🚀 Getting Started

```bash
npm install
npm run dev
```

Open the local development server shown in the terminal to view the project in your browser.

## 📜 Available Scripts

```bash
npm run dev      # Start the Vite development server
npm run build    # Create a production build
npm run preview  # Preview the production build locally
npm run lint     # Run ESLint checks
```

## 🌟 Author

<div align="center">
  <a href="https://github.com/zahid-official">
    <img src="https://github.com/zahid-official.png" width="100" height="100" style="border-radius: 50%;" alt="Zahid Official" />
  </a>

  <h3>Zahid Official</h3>
  <p><b>Web Developer | Tech Enthusiast</b></p>

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/zahid-official)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/zahid-web)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:zahid.official8@gmail.com)

  <p>Building polished digital experiences with passion and purposeful design</p>
</div>

## 🤝 Contributing

Contributions make the project better for everyone. If you would like to improve **Cricket Premier League**, your contributions are always welcome.

```bash
1. Fork the project
2. Create your feature branch (git checkout -b feature/AmazingFeature)
3. Commit your changes (git commit -m 'Add some AmazingFeature')
4. Push to the branch (git push origin feature/AmazingFeature)
5. Open a Pull Request
```

<p align="center"><b>Cricket Premier League</b><i> - Where every selection brings your dream squad one step closer to the pitch.</i></p>
