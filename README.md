# Koperasi Merah Putih — Next.js Fullstack Demo

This is a demo **Next.js** single-repo project (frontend + backend API routes) prepared for quick deploy to **Vercel**.

**Highlights**
- Landing page, profile, articles, UMKM listing, complaint form
- Registration (upload KTP), login (demo), member & admin dashboards (UI)
- API routes included (simple in-memory / lowdb demo)
- Colors: red & white; responsive & modern UI
- Payments/buttons are UI-only (non-functional)

## Quick local run

Requirements: Node.js 18+

```bash
# clone or unzip project
npm install
npm run dev
# open http://localhost:3000
```

## Deploy to Vercel (1 repo)
1. Create a GitHub repo and push this project.
2. Sign in to https://vercel.com and Import Project → choose this repo.
3. Set Environment Variables (Vercel dashboard > Settings > Environment):
   - `JWT_SECRET` = a long random string (recommended)
4. Deploy. The app will provide a public URL.

**Note about persistence:** This demo uses simple JSON/ in-memory storage. On serverless platforms (Vercel) data may not persist between redeploys. For a production-ready app switch to a real DB (Postgres, Supabase, etc.) and cloud file storage.

Default admin credentials (for demo):
- email: admin@koperasi.test
- password: admin123

If you want, I can also:
- Push to GitHub for you (need your access)
- Configure a Render backend if you prefer separate backend
- Add additional UI polish or export ZIP

Enjoy!