# 🎮 Pixelog: Your Personal Game Backlog & Review Log

![Pixelog Banner](https://pixelog.jonatasoliveira.dev/banner.png)

[![Live Preview](https://img.shields.io/badge/Live%20Demo-View-orange?style=flat-square)](https://pixelog.jonatasoliveira.dev/)
\[![Status](https://img.shields.io/badge/Status-In%20Development-yellow?style=flat-square)]
\[![Built with Rust](https://img.shields.io/badge/Rust-000000?style=flat-square\&logo=rust\&logoColor=white)]
\[![Frontend Svelte](https://img.shields.io/badge/Svelte-FF3E00?style=flat-square\&logo=svelte\&logoColor=white)]
\[![Backend Axum](https://img.shields.io/badge/Axum-%236c3b9c?style=flat-square\&logo=rust\&logoColor=white)]
[![License](https://img.shields.io/github/license/jonatasoli/pixelog?style=flat-square)](LICENSE)

---

> *"Remember what you played, what you loved, and what's next in your gaming journey."*

## 📋 Table of Contents

1. [About Pixelog](#about-pixelog)
2. [Tech Stack](#tech-stack)
3. [Getting Started](#getting-started)
4. [Features](#features)
5. [Architecture](#architecture)
6. [Contributing](#contributing)
7. [Connect & Stay Updated](#connect--stay-updated)
8. [License](#license)

---

## 🎯 About Pixelog

Pixelog is a minimalistic, open-source web app for tracking your video game backlog, rating titles, and capturing your play history. Built for gamers who value control, privacy, and a clean interface.

> ⚠️ **In active development** — features are evolving and contributions are welcome!

---

## 🛠️ Tech Stack

|        Layer | Technology                                                                                                                                                                                        |
| -----------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Frontend** | ![Svelte](https://img.shields.io/badge/Svelte-FF3E00?style=flat-square\&logo=svelte\&logoColor=white)                                                                                             |
|  **Backend** | ![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square\&logo=rust\&logoColor=white) + ![Axum](https://img.shields.io/badge/Axum-6B3B9C?style=flat-square\&logo=rust\&logoColor=white) |
| **Database** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square\&logo=postgresql\&logoColor=white)                                                                                 |
|  **Hosting** | ![Dokku](https://img.shields.io/badge/Dokku-5B4F87?style=flat-square\&logo=docker\&logoColor=white)                                                                                               |

---

## 🚀 Getting Started

[WIP]

---

## ✨ Features

* **Backlog Management:** Add, edit, remove games with status tags (Wishlist, Playing, Completed)
* **Ratings & Reviews:** Star-based rating with free-text reviews
* **Progress Insights:** Visualize playtime and genre distribution
* **Search & Filters:** Quickly find games by name, tag, or status
* **Responsive PWA:** Mobile-first design with offline support
* **Theming:** Light/dark modes using Catppuccin palette

---

## 🏗️ Architecture

```
Browser <-> Svelte Frontend (PWA)
                  |
                  v
          Axum API (Rust)
                  |
          PostgreSQL & Redis
```

*(ASCII diagram for GitHub compatibility)*

---

## 🤝 Contributing

1. ⭐ Star this repository
2. 🍴 Fork the project
3. 🛠️ Create your feature branch (`git checkout -b feature/YourFeature`)
4. 📤 Commit and push (`git push origin feature/YourFeature`)
5. 🔀 Open a Pull Request

Please review [CONTRIBUTING.md](CONTRIBUTING.md) for more details.
## 📜 License

Distributed under the MIT License. See [LICENSE](LICENSE) for details.
