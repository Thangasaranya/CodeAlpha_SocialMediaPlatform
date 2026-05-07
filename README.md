# ◈ Pulse — Social Media App

> *Where moments become memories*

A full-stack **mini social media platform** built from scratch using **Express.js**, **NeDB**, and **Vanilla JavaScript** — no frameworks, no fluff.

---

## 🚀 Live Features

| Feature | Details |
|---|---|
| 🔐 Auth | Register & Login with JWT |
| 👤 Profiles | Avatar photo upload, bio, custom background theme |
| 📝 Posts | Text posts with image & audio attachments |
| ❤️ Likes | Animated heart burst on like |
| 💬 Comments | Real-time comment add & delete |
| 👥 Follow System | Follow / Unfollow users |
| 🎵 Music Player | In-post audio player with progress bar |
| 🎨 Backgrounds | 12 post BG colors + 10 profile themes |
| 🔍 Explore | Search users, browse all posts |

---

## 🛠 Tech Stack

**Frontend**
- HTML5, CSS3, Vanilla JavaScript
- Custom dark UI with animations

**Backend**
- Node.js + Express.js
- NeDB (file-based NoSQL database)
- JWT Authentication
- Multer (file uploads)
- bcryptjs (password hashing)

---

## 📁 Project Structure
socialmedia/
├── server.js              # Express backend & API routes
├── package.json
├── public/
│   ├── index.html         # Single page app
│   ├── css/style.css      # All styles
│   ├── js/app.js          # Frontend logic
│   └── uploads/           # User uploaded files
│       ├── avatars/
│       ├── posts/
│       └── songs/
└── data/                  # NeDB database files
---

## ⚡ Getting Started

### Prerequisites
- Node.js v18+
- npm

### Installation

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/pulse-social.git
cd pulse-social

# Install dependencies
npm install

# Start the server
node server.js
```

Open your browser → **http://localhost:3000**

---

## 🧪 Demo Accounts

| Email | Password |
|---|---|
| alice@demo.com | password123 |
| bob@demo.com | password123 |
| carol@demo.com | password123 |

---

## 📸 Screenshots

> Add your screenshots here after running the app!

---

## 🌐 API Endpoints

| Method | Route | Description |
|---|---|---|
| POST | `/api/auth/register` | Register user |
| POST | `/api/auth/login` | Login user |
| GET | `/api/feed` | Get following feed |
| GET | `/api/posts` | Get all posts |
| POST | `/api/posts` | Create post |
| POST | `/api/posts/:id/like` | Like / Unlike |
| GET | `/api/posts/:id/comments` | Get comments |
| POST | `/api/posts/:id/comments` | Add comment |
| POST | `/api/follow/:userId` | Follow / Unfollow |
| GET | `/api/users/:username` | Get profile |
| PUT | `/api/users/me` | Update profile |
| POST | `/api/users/me/avatar` | Upload avatar |

---

## 🙌 Author

Made with ❤️ by Thangasaranya

---

## 📄 License

MIT License — free to use and modify
