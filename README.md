# ✍️ Modern Blog App

A full-featured, modern **blog application** built with **Next.js 14 (App Router)**, **Prisma**, and **TypeScript**. Designed with modular architecture and scalable patterns for developers and content creators.

---

## 🚀 Features

- 📝 Create, edit, and delete blog posts
- 📂 Organize content with categories/tags
- 🔍 Full-text search support
- 🖼️ Image uploads (with static `public/` support or cloud)
- 🌐 SEO-friendly pages with dynamic routes
- 🔐 Auth-ready (custom or 3rd party like NextAuth.js)
- ⚡ Fast with SSR + ISR via Next.js App Router
- 🧠 Prisma ORM + PostgreSQL (or MySQL/SQLite)

---

## 🗂️ Folder Structure

├── actions/ # Server-side actions (e.g. createPost, deletePost)
├── app/ # Next.js App Router directory
│ ├── layout.tsx # Shared layout
│ └── page.tsx # Home/blog page
├── components/ # Reusable UI components (PostCard, Navbar, etc.)
├── lib/ # Database, utils, API helpers
├── prisma/ # Prisma schema & migrations
├── public/ # Static files (images, favicon, etc.)
├── middleware.ts # Middleware for auth/routing
├── package.json
├── tsconfig.json
├── next.config.ts
├── postcss.config.mjs
├── eslint.config.mjs
└── README.md

## 🧱 Tech Stack

| Layer       | Tech                        |
|-------------|-----------------------------|
| Framework   | Next.js 14 (App Router)     |
| Language    | TypeScript                  |
| ORM         | Prisma                      |
| Styling     | Tailwind CSS (PostCSS)      |
| DB          | PostgreSQL                  |
| Auth        | JWT                         |
| Linting     | ESLint                      |
