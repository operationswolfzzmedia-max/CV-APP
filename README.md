# CV Screening App (Vercel + Neon)
Candidates apply at `/`. Admin dashboard: `/admin.html`.
Environment variables (set in Vercel > Project > Settings > Environment Variables): ANTHROPIC_API_KEY, DATABASE_URL (Neon connection string), ADMIN_PASSWORD. Optional: CLAUDE_MODEL, SHORTLIST_MIN, MAYBE_MIN.
Tables are created automatically on the first visit. Uploaded PDFs are stored in the database (max 3 MB each).
