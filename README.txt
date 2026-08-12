# Bike Zone Website Project

Customer website: index.html
Admin panel: admin.html

Pre-filled contact:
- WhatsApp: 8878051833
- WhatsApp group: supplied by owner
- Instagram group: supplied by owner

Supabase already prepared by the owner:
- public.bikes table
- image_url column
- bike-images storage bucket
- authentication user

FINAL CONNECTION STILL REQUIRED:
The browser files must be connected to the owner's Supabase URL + publishable/anon key, then the admin panel must use Supabase Auth, database CRUD and Storage upload. Never put the service-role key or admin password in browser code.

After connection, customer site will read bikes online and admin changes will be visible to customers.
