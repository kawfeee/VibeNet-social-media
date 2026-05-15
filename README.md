````md
# VibeNet – Full Stack Social Media Platform

A modern full-stack social media web application built using **Next.js 15**, **React**, **TailwindCSS**, **Prisma**, **Neon PostgreSQL**, **Clerk Authentication**, **ShadCN UI**, and **UploadThing**.

This project allows users to create posts, upload media, like posts, comment, follow other users, and interact in real time through a clean and responsive interface.

---

## 🚀 Live Demo

🔗 [Live Website](YOUR_LIVE_LINK_HERE)

## 📂 GitHub Repository

🔗 [GitHub Repository](YOUR_GITHUB_LINK_HERE)

---

# 📸 Features

- 🔐 Authentication using Clerk
- 👤 User profiles
- 📝 Create, edit, and delete posts
- ❤️ Like and unlike posts
- 💬 Comment system
- 👥 Follow / unfollow users
- 🖼️ Media uploads with UploadThing
- 🌙 Dark / Light mode
- 📱 Fully responsive UI
- ⚡ Optimized database queries and UI performance
- 🔔 Real-time social interactions
- 🔎 Suggested users system
- 🎨 Modern UI with ShadCN + TailwindCSS

---

# 🛠️ Tech Stack

## Frontend
- React.js
- Next.js 15
- TailwindCSS
- ShadCN UI

## Backend
- Next.js Server Actions
- Prisma ORM
- PostgreSQL (Neon DB)

## Authentication
- Clerk

## File Uploads
- UploadThing

## Deployment
- Vercel

---

# 📷 Screenshots

## Home Feed
<!-- Add screenshot -->
```bash
/public/screenshots/home.png
````

## Profile Page

```bash
/public/screenshots/profile.png
```

## Create Post

```bash
/public/screenshots/create-post.png
```

---

# ⚙️ Installation & Setup

## 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/vibenet.git
```

## 2️⃣ Navigate to project folder

```bash
cd vibenet
```

## 3️⃣ Install dependencies

```bash
npm install
```

## 4️⃣ Setup environment variables

Create a `.env` file in the root directory and add:

```env
# Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

# Database
DATABASE_URL=

# UploadThing
UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=

# App URL
NEXT_PUBLIC_APP_URL=http://localhost:3000
```

---

# 🗄️ Database Setup

Run Prisma migrations:

```bash
npx prisma migrate dev
```

Generate Prisma client:

```bash
npx prisma generate
```

---

# ▶️ Run the Development Server

```bash
npm run dev
```

Open:

```bash
http://localhost:3000
```

---

# 📁 Project Structure

```bash
├── app
├── components
├── actions
├── lib
├── prisma
├── public
├── hooks
├── providers
├── styles
└── utils
```

---

# 🧠 What I Learned

While building this project, I learned:

* Full-stack development using Next.js App Router
* Authentication flow with Clerk
* Database modeling using Prisma ORM
* Media upload handling with UploadThing
* Optimizing UI performance
* Building scalable backend APIs
* Managing relational data in PostgreSQL
* Responsive UI design using TailwindCSS

---

# 📚 Credits

This project was built by following and learning from the amazing tutorial by Codesistency:

🎥 YouTube Tutorial:
[https://www.youtube.com/watch?v=vUYopHWOURg&t=15455s](https://www.youtube.com/watch?v=vUYopHWOURg&t=15455s)

The project was recreated, customized, and extended for learning and portfolio purposes.

---

# 🌐 Deployment

The application can be deployed easily on:

* Vercel
* Netlify
* Railway

Recommended:

```bash
Vercel + Neon + Clerk
```

---

# 📈 Future Improvements

* 🔔 Notifications system
* 💬 Real-time chat
* 📹 Video uploads
* 📌 Saved posts
* 🔍 Advanced search
* 🤖 AI-generated captions
* 📊 Analytics dashboard

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

---

# 📄 License

This project is licensed under the MIT License.

---

# ⭐ Support

If you liked this project:

* ⭐ Star the repository
* 🍴 Fork it
* 📢 Share it

---

# 👨‍💻 Author

**Kaif**

* LinkedIn: YOUR_LINKEDIN
* GitHub: YOUR_GITHUB

---

```

This project uses technologies and concepts commonly demonstrated in modern Next.js + Prisma + Clerk tutorials. :contentReference[oaicite:0]{index=0}
::contentReference[oaicite:1]{index=1}
```
