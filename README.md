# 🎮 The Game Website

**Explore Games. Discover New Worlds. Play Your Way.**

The Game Website is a gaming-focused website built to showcase popular video games, explore different gaming categories, and provide visitors with an engaging gaming experience. The project features a modern interface, individual game information pages, a dedicated JavaScript chess game, and signup and login interfaces.

Developed using HTML, CSS, and JavaScript, the website demonstrates frontend web development, interactive UI elements, responsive styling, and browser-based form handling.

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Game Collection](#-game-collection)
- [Technology Stack](#-technology-stack)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Authentication Workflow](#-authentication-workflow)
- [How to Use](#-how-to-use)
- [Security Considerations](#-security-considerations)
- [Future Enhancements](#-future-enhancements)
- [Contributing](#-contributing)
- [License](#-license)
- [Author](#-author)

---

## 📖 Overview

The Game Website provides a central place to discover popular games across multiple genres, including action, battle royale, simulation, adventure, and strategy.

Visitors can browse the game catalogue, open individual game pages, explore tournament-related content, and launch a browser-based chess game.

The project also includes signup and login pages with client-side form handling using JavaScript and browser `localStorage`.

### 🎯 Project Objectives

- Build an engaging gaming website using frontend technologies.
- Organize games into an accessible catalogue.
- Create dedicated pages for individual games.
- Implement interactive signup and login forms.
- Integrate a playable chess game built with JavaScript.
- Improve user experience through animations and visual design.
- Demonstrate DOM manipulation and browser storage.

---

## ✨ Features

### 🏠 Interactive Homepage

- Gaming-themed landing page.
- Navigation menu for important website sections.
- Game catalogue with cover images.
- Dedicated game information pages.
- Visually engaging layout and styling.

### 🎮 Game Catalogue

- Browse games from multiple genres.
- View game cover artwork and titles.
- Open individual game pages.
- Discover action, adventure, simulation, and strategy games.

### ♟️ Browser-Based Chess Game

- Dedicated chess game interface.
- Chess pieces and board graphics.
- JavaScript-based game functionality.
- Playable through a modern web browser.

### 👤 Signup Interface

- User registration form.
- Client-side form handling.
- Browser-based storage of submitted account details.
- Redirect to the login page after signup.

### 🔐 Login Interface

- Login form for previously registered users in the same browser.
- Client-side credential comparison.
- Success and error messages.
- Redirect to the homepage following successful login.

### 🏆 Tournament Section

- Tournament-related content on the homepage.
- Dedicated interface elements for presenting gaming events.

### 📩 Contact Page

- Dedicated contact page.
- Interface for visitors to access contact-related information.

### ✨ Animations and UI

- CSS-based visual styling.
- JavaScript-powered scroll animations.
- Intersection Observer integration for selected elements.
- Navigation active-state highlighting.
- Font Awesome icons through locally included CSS assets.

---

## 🕹️ Game Collection

The project includes individual pages for several popular games and franchises.

| Category             | Games                                          |
| -------------------- | ---------------------------------------------- |
| Action / FPS         | Call of Duty, Apex Legends                     |
| Battle Royale        | PUBG, Fortnite, Free Fire                      |
| Strategy             | StarCraft, Guild Wars                          |
| Adventure / Sandbox  | Minecraft, Terraria                            |
| Simulation           | The Sims, Stardew Valley                       |
| RPG                  | Diablo, World of Warcraft                      |
| Driving / Simulation | American Truck Simulator, Euro Truck Simulator |
| Casual / Party       | Fall Guys                                      |

*The catalogue represents the game's included pages. Actual gameplay, external downloads, purchases, and online services depend on the implementation of each individual page.*

---

## 🛠️ Technology Stack

| Technology                | Purpose                                            |
| ------------------------- | -------------------------------------------------- |
| HTML5                     | Website structure and content                      |
| CSS3                      | Styling, layouts, and animations                   |
| JavaScript                | Interactivity, DOM manipulation, and form handling |
| Browser `localStorage`    | Local storage of signup details                    |
| Font Awesome              | Icons and interface elements                       |
| Intersection Observer API | Scroll-triggered animations                        |

The main website is a frontend project and does not require a PHP server or MySQL database for its basic pages.

---

## 📂 Project Structure

```text
Gaming website/
└── Gaming website/
    │
    ├── index.html
    ├── script.js
    ├── styles.css
    │
    ├── signup.html
    ├── login.html
    ├── contact.html
    ├── concat.html
    │
    ├── american_truck.html
    ├── euro_truck.html
    ├── apex.html
    ├── call_of_duty.html
    ├── diablo.html
    ├── fall_guys.html
    ├── fortine.html
    ├── fortnite.html
    ├── free_fire.html
    ├── guild_wars.html
    ├── minecraft.html
    ├── pubg.html
    ├── starcraft.html
    ├── stardew_valley.html
    ├── terraria.html
    └── world_of_warcraft.html
    └── the_sims.html
    │
    ├── css/
    │   ├── style.css
    │   ├── game.css
    │   ├── auth.css
    │   ├── contact.css
    │   └── all.min.css
    │
    ├── images/
    │   └── Game artwork and website assets
    │
    ├── Chess-Game-using-JavaScript-master/
    │   ├── chess.html
    │   ├── chess.js
    │   ├── chess.css
    │   ├── ChessGame.jpg
    │   └── Chess piece images
    │
    └── game/
        ├── index.html
        ├── american_truck.html
        ├── euro_truck.html
        ├── apex.html
        ├── call_of_duty.html
        ├── diablo.html
        ├── fall_guys.html
        ├── fortine.html
        ├── free_fire.html
        ├── guild_wars.html
        ├── minecraft.html
        ├── pubg.html
        ├── starcraft.html
        ├── stardew_valley.html
        ├── terraria.html
        ├── the_sims.html
        └── world_of_warcraft.html
```

*Note: The project also contains additional images and assets. The structure above is simplified for readability.*

---

## 🚀 Getting Started

Follow these steps to run the project locally.

### Prerequisites

You will need:

- A modern web browser, such as Chrome, Firefox, or Edge.
- A code editor such as [Visual Studio Code](https://code.visualstudio.com/).
- Git (optional, for cloning the repository).

No backend server or database is required to browse the basic static website.

### 1. Clone the Repository

```bash
git clone <YOUR_REPOSITORY_URL>
```

Alternatively, download and extract the project ZIP file.

### 2. Open the Project

Open the extracted project folder in Visual Studio Code.

Navigate to the main project directory containing `index.html`.

### 3. Launch the Website

**Option A — Open directly**

Open `index.html` in your browser.

**Option B — Use Live Server**

1. Install the Live Server extension in Visual Studio Code.
2. Right-click `index.html`.
3. Select **Open with Live Server**.

The website should open in your default browser.

### 4. Explore the Chess Game

Open the chess game from the homepage using the **Play Now** link, or navigate to:

```text
Chess-Game-using-JavaScript-master/chess.html
```

If you use Live Server, open the chess page through the local server for consistent asset loading.

---

## 🔑 Authentication Workflow

The signup and login forms use JavaScript and browser `localStorage`.

### Signup

1. Open `signup.html`.
2. Enter the requested account information.
3. Submit the form.
4. The current implementation stores the username, email, and password in browser storage.
5. The website redirects to the login page.

### Login

1. Open `login.html`.
2. Enter the previously saved username and password.
3. The script compares the entered values with those in `localStorage`.
4. A success or error message is displayed.

**Important:** This is a demonstration of client-side form handling, not secure production authentication. The stored password is not protected by server-side hashing, and browser storage can be inspected or modified by the user.

---

## 💻 How to Use

1. Launch the homepage.
2. Explore the available games.
3. Open individual game pages to view their content.
4. Browse tournament-related sections.
5. Try the signup and login interfaces.
6. Open the chess game and test its gameplay.
7. Visit the contact page.

Some navigation links and features may require adjustments depending on the exact file paths and page implementations.

---

## 🔐 Security Considerations

The current signup and login workflow is intended for demonstration purposes.

Before using the website for real users:

- Implement authentication on a secure backend.
- Never store plaintext passwords in `localStorage`.
- Hash passwords using a suitable server-side password hashing function.
- Use HTTPS in production.
- Validate and sanitize user input.
- Implement secure sessions and authorization.
- Avoid storing sensitive information in browser storage.
- Add rate limiting and appropriate protections against automated login attempts.

The project does not establish a secure payment, purchasing, or game-distribution system merely by presenting these options in its interface.

---

## 🔮 Future Enhancements

Possible improvements include:

- [ ] Add search and filtering for games.
- [ ] Add genre-based browsing.
- [ ] Improve mobile responsiveness.
- [ ] Create a complete game detail template.
- [ ] Add favorites and a personal game library.
- [ ] Implement secure backend authentication.
- [ ] Add user profiles and account management.
- [ ] Build a functional tournament registration system.
- [ ] Integrate a database for persistent user information.
- [ ] Add accessibility improvements and keyboard navigation.
- [ ] Improve chess gameplay and user feedback.
- [ ] Add automated testing and deployment.

---

## 🤝 Contributing

Contributions and suggestions are welcome.

1. Fork the repository.
2. Create a new feature branch.
3. Make your changes.
4. Test the relevant pages and interactions.
5. Submit a pull request with a clear description of your improvements.

Please ensure that new assets, game artwork, and third-party libraries are used in accordance with their respective licenses.

---

## 📄 License

No explicit open-source license has been identified for the complete project.

Before redistributing or reusing this website, add an appropriate `LICENSE` file and verify the licensing terms of the included game artwork, images, icons, and third-party chess project.

---

## 👨‍💻 Author

**The Game Website — Web Development Project**

A gaming website project built to demonstrate frontend development, interactive web design, browser-based form handling, and JavaScript gameplay.

**Technologies:** HTML5, CSS3, JavaScript, and browser APIs.

---

⭐ If you find this project useful, consider giving the repository a star!

