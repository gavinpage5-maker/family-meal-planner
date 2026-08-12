# Family Meal Planner — Version 3 (Supabase Cloud Sync)

This version connects the prototype to the Supabase project:

`https://oydczlyqrgghhmruqhoz.supabase.co`

## What is now cloud-backed
- email/password sign-in
- family membership
- households
- household default serving sizes
- Monday–Sunday meal plans for the current week
- shared Family Meals
- shopping-list items and ticked state

## What is still local/sample data
- the sample recipe catalogue itself starts inside the app
- after first successful sign-in, those sample recipes are copied into the family's Supabase `recipes` table
- live internet recipe discovery is not yet enabled

## Current test user
The database already links Gavin to Page Family → Our House.

## Next phase
1. Publish this Version 3 build via GitHub Pages.
2. Test sign-in and syncing on two devices.
3. Invite the other family members.
4. Tighten member permissions if desired so non-admin users default to their own household.
5. Add live recipe discovery/import.
