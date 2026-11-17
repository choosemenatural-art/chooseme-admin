# Choose Me Natural — Admin Panel

Next.js admin dashboard for managing products, categories, orders, banners, coupons, testimonials, customers, contact messages and FAQs.

## Setup

1. `npm install`
2. Create `.env` with:
   ```
   NEXT_PUBLIC_BACKEND_URL=http://localhost:5000/api
   ```
3. Start the backend (`chooseme-backend`, `npm run dev`), then run `npm run dev` here.

Log in at `/admin-login`. All `/dashboard` pages are protected by `src/components/auth/AuthGuard.tsx`.
