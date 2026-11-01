# The Travel Desk - Travel Management System

This is a complete B2B travel management CRM for Misty Voyages.

## How to deploy on GitHub Pages
1. Upload all files in this folder to your GitHub repository (e.g., travel-desk)
2. Go to Settings > Pages
3. Branch: main, Folder: / (root) -> Save
4. Your site will be live at https://username.github.io/travel-desk/

## Custom Domain
In Settings > Pages > Custom Domain, enter your domain (e.g., www.mistyvoyages.in)
Then add DNS records:
- CNAME: www -> username.github.io
OR
- A records: @ -> 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153

Enable Enforce HTTPS after DNS propagates.

## Files
- index.html - Main CRM (The Travel Desk)
- Hotel_Master.html, Cab_Master.html, etc - Standalone views (iframe wrappers)
