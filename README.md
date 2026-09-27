# CHARLES — Premium Bookstore

A mobile-first React + Vite bookstore with a separate owner admin area.

## Included
- Premium editorial storefront
- Product catalog, search, categories
- Product detail pages
- Cart and checkout
- UPI + Cash on Delivery only
- Card payments intentionally disabled
- Order confirmation and stock reduction
- Separate `/admin/login` and `/admin`
- Homepage editor
- Product manager
- Local persistence for demo/prototype data

## Demo admin
URL: `/admin/login`
Password: `charlesadmin`

## Contact
WhatsApp: 8384059345
Email: charlesbooklibrary@gmail.com
UPI: 8384059345@fam

## Run
```bash
npm install
npm run dev
```

Build:
```bash
npm run build
```

## Production note
This build is a functional front-end/prototype with browser localStorage. Before accepting real payments or real customer orders, connect Supabase Auth/Postgres/Storage and implement server-side order/payment verification and RLS. Do not put private payment/provider secrets in the browser.
