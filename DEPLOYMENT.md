# Fahmad Empire — go-live checklist

## 1. Create Supabase
Create a free Supabase project, open SQL Editor, and run `supabase_schema.sql`.

## 2. Browser connection
Copy `supabase_config.example.js` to `supabase_config.js` and fill in the Project URL and anon public key. Never put the service_role key in this file.

## 3. Payment
Create a Paystack business account and use a server-side endpoint/webhook for payment verification. Do not verify payments only in browser code.

## 4. Hosting
Deploy this folder to Vercel, Netlify, or Cloudflare Pages. No paid hosting is required to test the storefront.

## 5. Domain
After deployment, connect a domain such as fahmadempire.com or a suitable .ng domain.

## Important
The current V2 UI still has a local-browser demo data mode. The database schema in this package is the production foundation. The next code step is wiring the storefront/admin mutations to Supabase and adding a secure server API for admin writes and Paystack webhooks.
