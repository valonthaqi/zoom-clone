# Zoom Clone 🎥

A modern **Zoom-like video conferencing app** built with **Next.js, TypeScript, Clerk, Stream, and TailwindCSS**.  
This app allows users to authenticate, create meetings, join video calls, and collaborate in real-time.

---

## 🚀 Features
- 🔐 Authentication & user management with [Clerk](https://clerk.com/)
- 📹 Real-time video & audio powered by [Stream](https://getstream.io/)
- 🎨 Responsive UI with [TailwindCSS](https://tailwindcss.com/)
- ⚡ Fast & optimized with [Next.js](https://nextjs.org/) + TypeScript
- 📅 Schedule and manage meetings
- 👥 Multiple participants in one call

---

## 🛠️ Tech Stack
- **Frontend:** Next.js, TypeScript, TailwindCSS
- **Authentication:** Clerk
- **Video API:** Stream

---

## 🌐 Environment Variables

Create a .env.local file in the root of your project and add your API keys:

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_IN_FALLBACK_REDIRECT_URL=/
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_SIGN_UP_FALLBACK_REDIRECT_URL=/

NEXT_PUBLIC_STREAM_API_KEY=your_stream_api_key
STREAM_SECRET_KEY=your_stream_secret_key

NEXT_PUBLIC_BASE_URL=http://localhost:3000
Note: Replace all your_*_key placeholders with your own keys from Clerk and Stream.

## ⚙️ Installation
Clone the repo and install dependencies:



```bash
git clone https://github.com/valonthaqi/zoom-clone.git
cd zoom-clone
npm install
npm run dev
```


## 🌐 Environment Variables

Create a .env.local file in the root of your project and add your API keys:

```bash
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_IN_FALLBACK_REDIRECT_URL=/
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_SIGN_UP_FALLBACK_REDIRECT_URL=/

NEXT_PUBLIC_STREAM_API_KEY=your_stream_api_key
STREAM_SECRET_KEY=your_stream_secret_key

NEXT_PUBLIC_BASE_URL=http://localhost:3000
```
