<h1 align="center">✨ Inview - Video Calling Interview Platform ✨</h1>

A modern, full-stack video interview platform with real-time calling, screen recording, and an inbuilt coding environment for seamless technical interviews.

---

## 🚀 Tech Stack

- **Framework**: Next.js (App Router) & TypeScript  
- **Video**: [Stream](https://getstream.io/)  
- **Database**: [Convex](https://www.convex.dev/)  
- **Authentication**: [Clerk](https://clerk.dev/)  
- **Styling**: Tailwind CSS & [shadcn/ui](https://ui.shadcn.com/)

---

## ✨ Features

- 🎥 Real-time Video Calling  
- 🖥️ Screen Sharing  
- 🎬 Screen Recording  
- 💻 Inbuilt Code Editor for Interviews  
- 🔒 Secure Authentication & Authorization  
- 🧠 Clerk + Convex Webhook Integration  
- 🎭 Client & Server Components  
- 🛣️ Dynamic & Static Routing  
- 📦 Fully Modular Component-Based Design  
- 🚀 Production-ready Deployment

---

## 🛠️ Environment Setup

Create a `.env.local` file in the root directory and add the following:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
CONVEX_DEPLOYMENT=your_convex_deployment_id
NEXT_PUBLIC_CONVEX_URL=your_convex_url
NEXT_PUBLIC_STREAM_API_KEY=your_stream_api_key
STREAM_SECRET_KEY=your_stream_secret_key
