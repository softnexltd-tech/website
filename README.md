# SoftNex Multi-Page Site

Real, separate, crawlable pages, tuned for SEO and now with a mobile-friendly menu.

## Files to upload (all into your web root, same folder)
HTML pages: index.html (Home), services.html, oracle-apex.html, oracle-erp.html,
business-intelligence.html, support.html, big-data.html, customization.html,
products.html, hims.html, erp-mug.html, edu-soft.html, about.html, contact.html,
projects.html
Shared assets: style.css (REQUIRED pages are unstyled without it), sitemap.xml, robots.txt
Images (use EXACTLY these names): "Company Logo.png" (nav logo), "Tab logo.png" (tab/favicon),
og-image.png (social preview)

index.html must be the default document for "/".

## Mobile navigation
- On phones, "Services" and "Products" now show an animated chevron (arrow) on the right.
  Tap the arrow to smoothly expand/collapse its sub-menu; tapping the text still opens the
  overview page. Only one sub-menu stays open at a time, and they reset when the menu closes.
- Desktop is unchanged (hover still reveals the sub-menus).

## SEO state
- Exactly one real <h1> per page; shared cacheable style.css; per-page title, description,
  canonical and breadcrumb data; real <a href> internal links; full schema markup;
  sitemap.xml + robots.txt.

## How to implement the sitemap
1. Upload sitemap.xml and robots.txt to the web root (sitemap reachable at
   https://softnexltd.com/sitemap.xml).
2. Verify https://softnexltd.com in Google Search Console.
3. Search Console -> Sitemaps -> type "sitemap.xml" -> Submit.
4. URL Inspection -> Request indexing for top pages (home, oracle-erp, oracle-apex,
   products, contact).
5. Optional: repeat in Bing Webmaster Tools.
6. Update sitemap.xml whenever you add/remove a page.

## Filename tip
Filenames with spaces work in browsers. If your host ever fails to load them, rename to
company-logo.png / tab-logo.png and tell me I'll update every page.
