# 🎮 PixelQuest

**Your personal video game library manager.**

PixelQuest is a web application designed to help gamers organize, manage, and track their video game collections in one place.

The platform allows users to build their own game libraries, track their gaming progress, record playtime, rate games, and discover new titles through integration with the RAWG Video Games Database API.

The project is being developed as a practical study of JavaScript, TypeScript, React, and full-stack web development.

---

## 🚧 Project Status

**Currently in development.**

PixelQuest is an ongoing personal project. Features and improvements will be implemented gradually.

---

## ✨ Features

### 📚 Game Library
- Add games to your personal collection.
- Organize games by platform and genre.
- Track gaming progress.
- Manage your personal wishlist.

### 🎯 Gaming Progress
- Mark games as:
  - Playing
  - Completed
  - Abandoned
  - Backlog
- Record playtime.
- Keep track of completed games.

### ⭐ Ratings & Reviews
- Rate games.
- Write personal reviews.
- Keep a history of your gaming experiences.

### 📊 Dashboard
- View your game collection statistics.
- Track completed games.
- Monitor total playtime.
- Visualize your gaming progress.

### 🔎 Game Discovery
- Search for games using the RAWG API.
- Import game information.
- Display game covers, descriptions, genres, and release dates.

---

## 🛠️ Technologies

The project uses the following technologies:

| Technology | Purpose |
|---|---|
| Next.js | Full-stack React framework |
| React | User interface |
| TypeScript | Static typing |
| Tailwind CSS | Interface styling |
| PostgreSQL | Relational database |
| Prisma ORM | Database management |
| RAWG API | Video game information |

---

## 📁 Project Structure

```text
pixelquest/
│
├── prisma/
│   └── schema.prisma
│
├── public/
│   └── images/
│
├── src/
│   ├── app/
│   │   ├── api/
│   │   ├── dashboard/
│   │   ├── games/
│   │   ├── login/
│   │   ├── register/
│   │   ├── layout.tsx
│   │   └── page.tsx
│   │
│   ├── components/
│   ├── lib/
│   │   ├── prisma.ts
│   │   └── rawg.ts
│   │
│   └── types/
│
├── .env
├── .gitignore
├── package.json
└── README.md
```

---

## ⚙️ Installation

### Requirements

Before getting started, make sure you have installed:

- Node.js
- npm
- PostgreSQL

### 1. Clone the repository

```bash
git clone https://github.com/Taunt-byte/PixelQuest.git
```

### 2. Navigate to the project directory

```bash
cd pixelquest
```

### 3. Install dependencies

```bash
npm install
```

### 4. Configure environment variables

Create a `.env` file in the root directory:

```env
DATABASE_URL="postgresql://USER:PASSWORD@localhost:5432/pixelquest"

RAWG_API_KEY="YOUR_RAWG_API_KEY"
```

Replace the values with your PostgreSQL credentials and RAWG API key.

### 5. Run the development server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 🗺️ Roadmap

- [ ] Initial project setup.
- [ ] Database configuration with PostgreSQL and Prisma.
- [ ] User registration and authentication.
- [ ] Game catalog integration with RAWG API.
- [ ] Personal game library.
- [ ] Game status management.
- [ ] Playtime tracking.
- [ ] Ratings and reviews.
- [ ] Dashboard and statistics.
- [ ] Responsive interface.
- [ ] Testing and deployment.

---

## 🎯 Project Goals

PixelQuest was created to explore and practice full-stack web development through a practical application.

The main learning objectives include:

- Building applications with Next.js and React.
- Working with TypeScript.
- Designing relational databases.
- Implementing authentication and authorization.
- Consuming external REST APIs.
- Developing reusable components.
- Understanding full-stack application architecture.

---

## 📡 External API

Game information is provided through the [RAWG Video Games Database API](https://rawg.io/apidocs).

---

## 👨‍💻 Author

Developed as a personal learning project.

**Lucas Neves da Silva**

GitHub: [@Taunt-byte](https://github.com/Taunt-byte)

---

## 📄 License

This project is available under the MIT License.