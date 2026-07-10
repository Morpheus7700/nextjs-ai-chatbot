# Chat SDK Template 💬

A powerful, open-source AI chatbot template built with **Next.js 14** (App Router) and the **Vercel AI SDK**. 

## 🌟 Features
- **Next.js App Router:** Advanced routing for seamless navigation and performance.
- **React Server Components:** Optimized server-side rendering.
- **Vercel AI SDK:** Unified API for generating text, structured objects, and handling tool calls.
- **Database Integration:** Uses Drizzle ORM and Postgres for robust chat history persistence.
- **Modern UI:** Styled with Tailwind CSS and shadcn/ui components.

## 🛠️ Tech Stack
- Next.js 14, React 19
- Drizzle ORM, Postgres
- Vercel AI SDK (OpenAI, Anthropic, etc.)
- Tailwind CSS, Radix UI

## ⚙️ Getting Started
1. Copy `.env.example` to `.env` and add your API keys and Database URL.
2. Run database migrations:
   ```bash
   npm run db:migrate
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```
