# Deployment Guide

## Quick Deploy to Vercel

1. Push your code to GitHub
2. Go to [vercel.com](https://vercel.com)
3. Import your GitHub repository
4. Add these environment variables:
   - `VITE_SUPABASE_PROJECT_ID` = `mpzlycsjsgecgaahcjbr`
   - `VITE_SUPABASE_PUBLISHABLE_KEY` = `eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6Im1wemx5Y3Nqc2dlY2dhYWhjamJyIiwicm9sZSI6ImFub24iLCJpYXQiOjE3NTkzODgwMzIsImV4cCI6MjA3NDk2NDAzMn0.817MyI7hroLUGqSrmPPjNysSVZyAafQUrqa2nZPV2IE`
   - `VITE_SUPABASE_URL` = `https://mpzlycsjsgecgaahcjbr.supabase.co`
5. Deploy!

## Build Commands

- **Development**: `npm run dev`
- **Production Build**: `npm run build`
- **Preview**: `npm run preview`

## Environment Variables

Make sure to set these in your hosting platform:
- `VITE_SUPABASE_PROJECT_ID`
- `VITE_SUPABASE_PUBLISHABLE_KEY` 
- `VITE_SUPABASE_URL`

## Tech Stack

- React 18
- Vite
- TypeScript
- Tailwind CSS
- shadcn/ui
- Supabase
- React Router
