[![Next.js](https://img.shields.io/badge/Next.js-16-black)](https://nextjs.org)
[![React](https://img.shields.io/badge/React-19-61DAFB)](https://react.dev)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-3178C6)](https://www.typescriptlang.org)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-4-06B6D4)](https://tailwindcss.com)

# Auth UI

A modern authentication UI built with Next.js 16, React 19, and Tailwind CSS.

## Features

- Login & Signup pages
- Password management (strength indicator, match validation)
- OAuth authentication buttons
- Phone number input
- Dark/Light theme support
- Responsive design
- Accessible components (Radix UI)

## Tech Stack

- **Framework:** Next.js 16
- **UI Library:** React 19
- **Styling:** Tailwind CSS 4
- **Components:** Radix UI + shadcn/ui
- **Validation:** React Hook Form + Zod

## Getting Started

```bash
# Install dependencies
npm install

# Run development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to view the app.

## Project Structure

```
├── app/                  # Next.js app router pages
│   ├── auth/            # Authentication pages
│   └── ...
├── components/
│   ├── auth/            # Auth-specific components
│   ├── ui/              # Reusable UI components
│   └── marketing/       # Marketing components
├── hooks/               # Custom React hooks
└── lib/                 # Utility functions
```

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint
