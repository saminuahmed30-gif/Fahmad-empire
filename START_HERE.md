# Fahmad Empire — Connected Admin Build

Your Supabase project and administrator account are already configured.

## 1. Run the security patch
In Supabase SQL Editor, run `admin_security_patch.sql` once. You should see `Success. No rows returned`.

## 2. Use the site
Open `index.html` from a web server (not `file://` if your browser blocks CDN modules). Press `Ctrl+Shift+A` or add an admin button to open the admin sign-in.

Sign in using the administrator email/password you created in Supabase.

## 3. Add products
Admin → Products → Add Product. Product records are written to Supabase and images upload to the `product-images` bucket.

## 4. Important
This build is a connected development/production-foundation package. Paystack, real customer order writes, email notifications, and deployment/domain are separate next stages.
