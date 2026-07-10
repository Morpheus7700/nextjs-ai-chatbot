# Next.js AI Chatbot

> A full-featured AI chatbot built on the Next.js App Router and the Vercel AI SDK.

> **Note:** This project is built on Vercel's open-source [Chat SDK / ai-chatbot template](https://github.com/vercel/ai-chatbot). It is used here as a foundation for learning and customisation rather than an original template.

A chatbot app featuring authenticated sessions, persistent chat history, and streaming responses, using React Server Components and the Vercel AI SDK.

## Features
- Next.js App Router with React Server Components
- Vercel AI SDK for text generation, structured output, and tool calls
- Authentication via NextAuth
- Chat history persistence with Drizzle ORM and Postgres
- UI styled with Tailwind CSS and shadcn/ui

## Tech Stack
- Next.js, React, TypeScript
- Vercel AI SDK, Drizzle ORM, Postgres
- Tailwind CSS, Radix UI

## Getting Started
1. Copy `.env.example` to `.env.local` and add your API keys and database URL.
2. Run migrations, then start the dev server:
   ```bash
   npm run db:migrate
   npm run dev
   ```
