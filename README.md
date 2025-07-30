# Next.js Dashboard App (App Router)

A beginner-friendly **Next.js App Router** project built as part of the official [Next.js Learn Tutorial](https://nextjs.org/learn). This project demonstrates core concepts of the App Router including routing, layouts, metadata, loading UI, and data fetching patterns with React Server Components.

## 🚀 Live Demo

🔗 [https://nextjs-dashboard-tau-two-26.vercel.app/](https://nextjs-dashboard-tau-two-26.vercel.app/)

---

## 📁 Project Structure

This app follows the `app/` directory routing introduced in Next.js 13+ using React Server Components by default:

```
├── app/
│   ├── layout.tsx
│   ├── page.tsx
│   └── dashboard/
├── components/
├── public/
├── styles/
├── tsconfig.json
├── next.config.js
└── ...

```

---

## 🛠️ Tech Stack

- [Next.js 14+ (App Router)](https://nextjs.org/)
- [React 18](https://reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [pnpm](https://pnpm.io/) – Fast, disk-efficient package manager
- [Vercel](https://vercel.com/) – Deployment platform for frontend frameworks

---

## 📦 Installation

> Prerequisites:
>
> - [Node.js](https://nodejs.org/) v18+
> - [pnpm](https://pnpm.io/) v8+

Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/nextjs-dashboard.git
cd nextjs-dashboard
pnpm install
```

---

## ▶️ Running Locally

Start the development server:

```bash
pnpm dev
```

Then open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 📤 Deployment

The app is deployed via **Vercel** directly from the GitHub repo. Every push to `main` (or your production branch) will auto-deploy.

If you'd like to deploy it yourself:

```bash
# Install Vercel CLI
pnpm add -g vercel

# Link the project and deploy
vercel
```

---

## 📚 Learning Outcomes

Through this project, I explored:

- ✅ File-based routing using the **App Router**
- ✅ Dynamic layouts and shared UI
- ✅ Server and Client Components
- ✅ Metadata handling for SEO
- ✅ Loading states and streaming UI
- ✅ API routes (optional)
- ✅ Deployments with **Vercel**
- ✅ Efficient project setup using **pnpm**

---

## 📎 License

This project is licensed for educational purposes. Feel free to fork and extend it.
