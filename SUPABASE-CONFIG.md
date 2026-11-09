# Supabase configuration

Project URL: https://peppndfwhnhcrswqihss.supabase.co

The frontend uses the publishable key in index.html. Never put a service_role key in frontend code.

Required setup:
- Authentication > Sign In / Providers > Anonymous Sign-Ins enabled.
- public.skies and public.stars tables with the configured RLS policies.
- Realtime enabled for skies and stars.

The app supports personal sky URLs, visitor dedications, glowing stars, live updates, and owner title/message editing.
