◈ Pulse — Social Media App

Where moments become memories

A full-stack mini social media platform built with Express.js, NeDB and Vanilla JS.

✨ Features

🔐 JWT Auth (Register / Login)
👤 User profiles with photo upload
📝 Posts with image & audio attachments
❤️ Like with burst animation & 💬 Comments
👥 Follow / Unfollow system
🎵 In-post music player
🎨 Custom post & profile background themes
🔍 Explore & search users


🛠 Tech Stack
LayerTechnologiesFrontendHTML5, CSS3, Vanilla JavaScriptBackendNode.js, Express.jsDatabaseNeDB (file-based NoSQL)AuthJWT + bcryptjsUploadsMulter

📋 Prerequisites
Before running this project, make sure you have installed:

Node.js v18 or higher
npm (comes with Node.js)

Check your version:
bashnode -v
npm -v

⚡ Installation & Setup
Step 1 — Clone the repository
bashgit clone https://github.com/YOUR_USERNAME/pulse-social.git
Step 2 — Go into the project folder
bashcd pulse-social/socialmedia
Step 3 — Install dependencies
bashnpm install
Step 4 — Start the server
bashnode server.js
Step 5 — Open in browser
http://localhost:3000

🧪 Demo Accounts
EmailPasswordalice@demo.compassword123bob@demo.compassword123carol@demo.compassword123

📁 Project Structure
socialmedia/
├── server.js          # Express backend & API routes
├── package.json       # Dependencies
├── public/
│   ├── index.html     # Single page app
│   ├── css/
│   │   └── style.css  # All styles
│   ├── js/
│   │   └── app.js     # Frontend logic
│   └── uploads/       # User uploaded files
│       ├── avatars/
│       ├── posts/
│       └── songs/
└── data/              # NeDB database files

🌐 API Endpoints
MethodRouteDescriptionPOST/api/auth/registerRegister new userPOST/api/auth/loginLogin userGET/api/feedGet following feedGET/api/postsGet all postsPOST/api/postsCreate new postPOST/api/posts/:id/likeLike / Unlike postGET/api/posts/:id/commentsGet commentsPOST/api/posts/:id/commentsAdd commentPOST/api/follow/:userIdFollow / UnfollowGET/api/users/:usernameGet user profilePUT/api/users/meUpdate profilePOST/api/users/me/avatarUpload avatar photo

📄 License
MIT — Made with ❤️ by Thangasaranya
