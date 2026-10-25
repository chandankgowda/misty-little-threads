# Misty Little Threads — Storefront Demo

A mobile-responsive static storefront prototype for made-to-order baby and toddler outfits, with product-only catalog photographs and a demo shopping cart.

## Run locally

Open `index.html` in Chrome or Edge. All images are included inside the `assets/` folder. No dependencies or build commands are required.

## Deploy with GitHub Pages

1. Create a **new public GitHub repository** named `misty-little-threads`.
2. Upload all contents of this folder (`index.html`, `assets/`, `README.md`, `.gitignore`) to the repository root and commit.
3. Open **Settings → Pages → Build and deployment**. Under **Source**, select **Deploy from a branch**, **main**, **/(root)**, then **Save**.
4. Once deployment finishes, the site should be at `https://YOUR-USERNAME.github.io/misty-little-threads/`.

Alternatively using Git:
```bash
git init
git add .
git commit -m "Initial Misty Little Threads storefront"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/misty-little-threads.git
git push -u origin main
```

## IMPORTANT: Demo only

- Products are listed at **₹2,000 each**, as requested.
- This is **not** a live e-commerce backend; cart behavior is browser-side only.
- No payments, customer accounts, secure order processing, inventory management, or GST invoicing are connected.
- GitHub Pages hosts **static sites only**. Do not collect real customer payment or sensitive information here. For live sales, connect a secure commerce backend such as WooCommerce on suitable managed hosting and deploy that separately.
- Product images are concept/stylized catalog renders based on reference photos, so confirm actual tailoring details and final product matches before accepting orders.
- GitHub public repos and Pages sites are publicly accessible; all included images will be public.
