# Family Meal Planner — Version 3.1

Version 3.1 adds proper Supabase password-recovery handling.

When a user clicks a Supabase password-reset email:
1. The link returns to the GitHub Pages app.
2. The app recognises the Supabase PASSWORD_RECOVERY session.
3. A "Choose a new password" screen appears.
4. The new password is saved with Supabase Auth.
5. The user is taken into the Family Meal Planner.

All Version 3 cloud-sync features remain unchanged.
