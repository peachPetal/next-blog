# Next Blog

Next.js + Supabase 기반 블로그 프로젝트  
1주차 MVP부터 단계적으로 확장 예정

## Tech Stack
- Next.js (App Router, TypeScript)
- Tailwind CSS / shadcn/ui
- Supabase (Auth, DB, RLS)
- Axios
- TanStack Query
- Zustand
- Jest / RTL
- Vercel
- ESLint (Airbnb Extended)
- Prettier
- Husky 

## Features (MVP)
- Public post list & detail
- Auth (signup / login / logout)
- Create / Update / Delete posts (author only)
- Profile view & edit

## Notes
- Permissions are enforced via Supabase RLS

## Getting Started
```bash
pnpm install
pnpm dev
```

## Environment Variables
```
NEXT_PUBLIC_SUPABASE_URL=
NEXT_PUBLIC_SUPABASE_ANON_KEY=
```