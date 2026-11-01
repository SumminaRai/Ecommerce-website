
# Swiftie

An e-commerce storefront built to practice modern frontend development with
Next.js, TypeScript and global state management.

## Features

- Product grid with search, category filter and price sorting
- Dynamic product detail pages (`/products/[id]`) rendered on the server
- Shopping cart with add, remove and quantity controls
- Cart persisted in localStorage across page refreshes
- Dark / light theme toggle using the Context API
- Typed props, state and API responses with TypeScript (strict mode)

## Tech Stack

- **Framework:** Next.js (App Router, Server and Client Components)
- **Language:** TypeScript
- **Styling:** Tailwind CSS
- **State management:** Zustand (cart), React Context (theme)
- **Data:** Fake Store API

## What I Learned

- Splitting pages into Server Components for data fetching and small Client
  Components for interactivity
- Dynamic routing and 404 handling in the App Router
- Choosing between local state, Context and a global store
- Avoiding hydration mismatches with persisted client state
- Building typed, reusable components and custom hooks

## Getting Started

```bash
git clone https://github.com/SumminaRai/swiftie.git
cd swiftie
npm install
npm run dev
```

Open http://localhost:3000

