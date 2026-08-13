# Family Meal Planner — Version 3.3

Fixes Supabase email-link authentication:
- parses Supabase URL fragment tokens explicitly
- uses `setSession()` with access and refresh tokens
- recovery links route to the new-password screen
- magic links sign in and open the app
- auth errors are shown clearly
- includes a small v3.3 marker in the app header
