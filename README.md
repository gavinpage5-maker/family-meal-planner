# Family Meal Planner — Version 3.5: Family Accounts

Changes:
- Admin users can see and switch between all family households.
- Member users load only the household assigned to them.
- Members cannot switch to another household through the app.
- The assigned household is shown as a fixed household chip for members.
- Existing Supabase authentication, cloud meal plans, shopping lists and shared family meals remain intact.

Current family setup:
- Gavin — admin — Our House
- Toby — member — Son & Partner

Note: Version 3.5 enforces this behaviour in the application interface. Supabase Row Level Security can be tightened separately for database-level enforcement.
