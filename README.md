# FarmStand — public web pages

Static pages for the FarmStand mobile app:

- `privacy.html` — privacy policy
- `terms.html` — terms of service
- `reset-password.html` — password reset page that recovery emails link to

Served via GitHub Pages. The app source lives in a separate private repository.

The Supabase URL and anon key in `reset-password.html` are public by design —
the anon key already ships inside the mobile app and all access is gated by
row-level security. The service role key is never used here.
