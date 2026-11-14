# SEO audit: lendingworkshop.com.au

Checked live on 14 Nov 2026. 8 pages crawled.

Every fix, step, snippet and page list from the audit is in this one file. Tick the boxes as you go.

## At a glance

- **Business:** a one-broker mortgage broker (Roopali Shah, credit rep under Connective) selling home, investment, refinance, first home buyer, business and vehicle loans.
- **Site platform:** this is a WordPress site built with Elementor, not hand-written static HTML. Most "code" fixes are clicks inside WordPress with a free SEO plugin.
- **Total fixes:** 30
  - Quick wins: 21 (30 min or less)
  - Medium: 5 (1 hour to half day)
  - Bigger: 4 (ongoing work)

**Fix this first:** Google has little to go on. The site shows no suburb or city anywhere, has no meta descriptions, a home page title of just "Lending workshop", no H1 headings and no business markup.

## Your question: is it just code plus Search Console?

**Not quite.** Code and Search Console are the foundation. For a local broker, what happens off the website often matters more.

The work falls into three steps and three groups:

**Step 1: Fix in the code**
- Titles, descriptions, headings
- Suburb and phone on the page
- Business markup (schema)
- Speed and images

**Step 2: Tell Google**
- Verify the site in Search Console
- Submit the sitemap
- Request indexing
- Watch the Pages report

**Step 3, separate group: Beyond the site**
- Google Business Profile (biggest local lever)
- Google reviews
- Bing Webmaster Tools
- Directories and backlinks
- Pages people search for
- Clear facts for AI answers

Search Console does not fix anything. It only shows what Google sees. All three groups are in the fix list below.

## Summary of all fixes

Numbers follow the order of the report: quick wins first, then medium, then bigger. Within each group, High impact comes first.

| # | Fix | Impact | Effort | Where it is fixed |
|---|-----|--------|--------|-------------------|
| 1 | Home page title says only 'Lending workshop' | High | 5 min | Code |
| 2 | No meta descriptions on any page | High | 30 min | Code |
| 3 | No suburb, city or address anywhere | High | 30 min | Code |
| 4 | No business markup (schema) at all | High | 30 min | Code |
| 5 | Check the four testimonials are real | High | 5 min | Code |
| 6 | Set up Google Search Console (5 steps) | High | 30 min | Search Console |
| 7 | Other page titles have no keyword either | Med | 15 min | Code |
| 8 | Five main pages have no H1 heading | Med | 15 min | Code |
| 9 | Delete the 'Hello world!' test post | Med | 5 min | Code |
| 10 | Images have empty alt text | Med | 15 min | Code |
| 11 | Phone number is not tap-to-call | Med | 5 min | Code |
| 12 | Logo and photos are far too big | Med | 30 min | Code |
| 13 | Resubmit the sitemap after adding Yoast | Med | 5 min | Search Console |
| 14 | 'Lending workshop' sounds like a training course | Med | 15 min | Other |
| 15 | No social share tags (Open Graph, Twitter) | Low | 5 min | Code |
| 16 | www version takes two hops to the real site | Low | 30 min | Code |
| 17 | About page URL ends in '-2' | Low | 15 min | Code |
| 18 | Footer says 2023 and links to a redirect | Low | 5 min | Code |
| 19 | No visitor tracking found | Low | 30 min | Code |
| 20 | Add Bing Webmaster Tools | Low | 5 min | Other |
| 21 | Make the facts easy for AI answers | Low | 30 min | Other |
| 22 | Claim your Google Business Profile | High | 1 hour | Google Business |
| 23 | Page loads too many fonts and scripts | Med | 1 hour | Code |
| 24 | Elementor and PHP are out of date | Med | Half day | Code |
| 25 | Home and contact pages are very thin | Med | Half day | Code |
| 26 | List the business in Australian directories | Med | Half day | Other |
| 27 | Give each loan type its own page | High | Ongoing | Code |
| 28 | Collect real Google reviews | High | Ongoing | Google Business |
| 29 | Publish answers to real buyer questions | Med | Ongoing | Code |
| 30 | Earn a few links from local partners | Med | Ongoing | Other |

---

## Quick wins (21)

### - [ ] 1. Home page title says only 'Lending workshop'

**Impact:** High. **Effort:** 5 min. **Where:** Code.

**What's wrong:** The home page title is 16 characters and has no keyword or place. It is what shows as the blue link in Google.

**Evidence:** https://lendingworkshop.com.au/  ->  <title>Lending workshop</title>

**How to fix:**
1. Install the free Yoast SEO plugin (Plugins > Add New). Rank Math is a fine alternative.
2. Pages > Home > Edit. Scroll to the Yoast box, find SEO title.
3. Paste the title below. Replace [SUBURB] with the area you serve.
4. Update. Repeat for each page (titles are in the next card).

**Paste this:**

```html
<title>Mortgage Broker [SUBURB] | Home Loans | Lending Workshop</title>
```

**Affected pages:**
- https://lendingworkshop.com.au/

### - [ ] 2. No meta descriptions on any page

**Impact:** High. **Effort:** 30 min. **Where:** Code.

**What's wrong:** All 8 pages have no description tag. Google writes its own, often badly. A good one lifts clicks.

**Evidence:** grep for name="description" returns 0 matches on all 8 pages.

**How to fix:**
1. In Yoast, fill the Meta description box on each page (aim for 120 to 155 characters).
2. Use the drafts below. Replace [SUBURB]. Every claim in them is already on your site.

**Paste this:**

```text
Home:
Lending Workshop helps [SUBURB] home buyers, investors and business owners find the right loan. Ex-banker. No overseas call centres. Call 0415 719 759.

Services:
First home buyer, refinance, investment, business and vehicle loans from a [SUBURB] mortgage broker. See how Lending Workshop can help you.

Process:
From first chat to settlement and beyond: our 7-step home loan process, explained simply. Get started with Lending Workshop today.

About:
Meet Roopali Shah, a mortgage broker and ex-big-4 banker with nearly 10 years in banking. Learn how Lending Workshop works for you.

Contact:
Call 0415 719 759 or send a message. Lending Workshop, mortgage broker in [SUBURB]. We reply quickly.
```

**Affected pages:**
- https://lendingworkshop.com.au/
- https://lendingworkshop.com.au/services/
- https://lendingworkshop.com.au/process/
- https://lendingworkshop.com.au/about-us-2/
- https://lendingworkshop.com.au/contact-us/
- https://lendingworkshop.com.au/privacy-policy/
- https://lendingworkshop.com.au/hello-world/
- https://lendingworkshop.com.au/category/uncategorized/

### - [ ] 3. No suburb, city or address anywhere

**Impact:** High. **Effort:** 30 min. **Where:** Code.

**What's wrong:** A local broker is found by place. The site never says where you are or which areas you serve. Google cannot match you to 'mortgage broker near me'.

**Evidence:** Contact page text is only: 0415 719 759, info@lendingworkshop.com.au and a form. No address, no suburb, no map. Footer shows ABN and licence only.

**How to fix:**
1. Decide: shop-front address or service-area only (many brokers hide the address and list areas).
2. Add a short line to the home page and footer: 'Mortgage broker serving [SUBURB], [CITY] and surrounds.'
3. Add the address (if public) and a Google Map embed to the Contact page (Elementor widget: Google Maps).
4. Use the exact same name, address and phone everywhere (Business Profile, directories, footer). This is called NAP consistency.
5. Add a service-area line listing suburbs you actually serve. Do not list places you do not work in.

**Paste this:**

```html
<p>Lending Workshop Pty Ltd<br>[STREET ADDRESS], [SUBURB] [STATE] [POSTCODE]<br><a href="tel:+61415719759">0415 719 759</a><br><a href="mailto:info@lendingworkshop.com.au">info@lendingworkshop.com.au</a></p>
```

**Affected pages:**
- https://lendingworkshop.com.au/
- https://lendingworkshop.com.au/contact-us/
- Footer on every page

### - [ ] 4. No business markup (schema) at all

**Impact:** High. **Effort:** 30 min. **Where:** Code.

**What's wrong:** Schema is hidden labels that tell Google 'this is a financial service, here is the phone and area'. There is none on any page.

**Evidence:** 0 occurrences of application/ld+json on all 8 pages.

**How to fix:**
1. Yoast Local SEO is paid. Instead use the free 'Insert Headers and Footers' plugin (WPCode) and add the snippet to the home page only.
2. Fill every [PLACEHOLDER]. Delete a line if you do not have it.
3. Test at search.google.com/test/rich-results with the home URL.
4. Do not add star ratings here unless they are real, public Google reviews.

**Paste this:**

```html
<script type="application/ld+json">
{
 "@context":"https://schema.org",
 "@type":"FinancialService",
 "name":"Lending Workshop",
 "url":"https://lendingworkshop.com.au/",
 "logo":"https://lendingworkshop.com.au/wp-content/uploads/2023/01/LOGO-1-scaled.jpg",
 "telephone":"+61415719759",
 "email":"info@lendingworkshop.com.au",
 "description":"Mortgage broker for first home buyers, refinance, investment, business and vehicle finance.",
 "address":{"@type":"PostalAddress","streetAddress":"[STREET]","addressLocality":"[SUBURB]","addressRegion":"[STATE]","postalCode":"[POSTCODE]","addressCountry":"AU"},
 "areaServed":["[SUBURB]","[CITY]"],
 "founder":{"@type":"Person","name":"Roopali Shah"},
 "sameAs":["[GOOGLE BUSINESS PROFILE URL]","[LINKEDIN URL]"]
}
</script>
```

**Affected pages:**
- https://lendingworkshop.com.au/ (add once, on the home page)

### - [ ] 5. Check the four testimonials are real

**Impact:** High. **Effort:** 5 min. **Where:** Code.

**What's wrong:** The About page shows four testimonials with generic names and Elementor's grey placeholder image. They look like sample text. Fake reviews are a legal and trust risk for a finance business.

**Evidence:** /about-us-2/: 'Sarah Williams', 'Michael Thompson', 'Jessica Anderson', 'David Gonzalez', each with wp-content/plugins/elementor/assets/images/placeholder.png. Not verified whether they are real clients.

**How to fix:**
1. If they are real: get permission, add a photo or first name and suburb, and check with Connective compliance before publishing testimonials.
2. If they are not real: remove them today.
3. Replace with real Google reviews once you have them (see the reviews card, fix 28).

**Affected pages:**
- https://lendingworkshop.com.au/about-us-2/

### - [ ] 6. Set up Google Search Console (5 steps)

**Impact:** High. **Effort:** 30 min. **Where:** Search Console.

**What's wrong:** There is no sign Google has been told about this site. Search Console is free and shows what Google sees.

**Evidence:** A site: search through my search tool returned no pages from lendingworkshop.com.au (not verified, the tool may ignore the operator). Sitemap is at /wp-sitemap.xml and listed in robots.txt.

**How to fix:**
1. Open the step-through in the section "Search Console setup, step by step" below: 5 steps. Tick each step as you go.

**Affected pages:**
- Whole site

### - [ ] 7. Other page titles have no keyword either

**Impact:** Med. **Effort:** 15 min. **Where:** Code.

**What's wrong:** Every page is '[Name] - Lending workshop' (32 to 39 characters). Short, no loan type, no place.

**Evidence:** /services/ -> 'Services – Lending workshop' (33). /process/ (32). /about-us-2/ (33). /contact-us/ (35).

**How to fix:**
1. In Yoast, set each SEO title as below (all under 60 characters, so Google will not cut them).
2. Keep the brand last.

**Paste this:**

```text
/services/    Home Loans, Refinance & Business Finance | Lending Workshop
/process/     Our 7-Step Home Loan Process | Lending Workshop
/about-us-2/  About Roopali Shah, Mortgage Broker | Lending Workshop
/contact-us/  Contact a Mortgage Broker [SUBURB] | Lending Workshop
```

**Affected pages:**
- https://lendingworkshop.com.au/services/
- https://lendingworkshop.com.au/process/
- https://lendingworkshop.com.au/about-us-2/
- https://lendingworkshop.com.au/contact-us/

### - [ ] 8. Five main pages have no H1 heading

**Impact:** Med. **Effort:** 15 min. **Where:** Code.

**What's wrong:** The H1 is the page's main headline. Elementor outputs every headline as H2, so the 5 key pages have none. Contact starts at H5.

**Evidence:** H1 count: / 0, /services/ 0, /process/ 0, /about-us-2/ 0, /contact-us/ 0 (first heading is <h5>Get In Touch</h5>).

**How to fix:**
1. Pages > the page > Edit with Elementor.
2. Click the main headline. Left panel > Content > HTML Tag > H1.
3. Home: change 'Let us work for you!' to H1 and add the keyword, e.g. 'Mortgage broker in [SUBURB]: let us work for you'.
4. Contact: make 'Contact Us' the H1 and change 'Get In Touch' to a normal text/H2.
5. About: the page has both 'About US' and 'About us' headings. Delete one and make the other the H1.
6. Only one H1 per page.

**Paste this:**

```html
<h1>Mortgage Broker in [SUBURB]: Let Us Work for You</h1>
```

**Affected pages:**
- https://lendingworkshop.com.au/
- https://lendingworkshop.com.au/services/
- https://lendingworkshop.com.au/process/
- https://lendingworkshop.com.au/about-us-2/
- https://lendingworkshop.com.au/contact-us/

### - [ ] 9. Delete the 'Hello world!' test post

**Impact:** Med. **Effort:** 5 min. **Where:** Code.

**What's wrong:** A WordPress sample post and its 'Uncategorized' category page are live and listed in the sitemap. They are thin pages with an open comment form (spam risk).

**Evidence:** wp-sitemap-posts-post-1.xml lists /hello-world/ (200, 126 words, comment form). wp-sitemap-taxonomies-category-1.xml lists /category/uncategorized/ (200, no canonical tag).

**How to fix:**
1. Posts > All Posts > Hello world! > Trash.
2. Settings > Discussion: untick 'Allow people to submit comments on new posts'.
3. Posts > Categories: keep Uncategorized (WordPress needs it) but it will be empty. Once Yoast is on, set Categories to noindex (Yoast > Settings > Content types > Categories > Show in search results: No).

**Affected pages:**
- https://lendingworkshop.com.au/hello-world/
- https://lendingworkshop.com.au/category/uncategorized/

### - [ ] 10. Images have empty alt text

**Impact:** Med. **Effort:** 15 min. **Where:** Code.

**What's wrong:** Alt text describes an image for screen readers and Google. All real photos and the logo have alt="".

**Evidence:** Home: 3 images, 3 with alt="" (logo twice, hero photo). Same logo with alt="" on every page. About page testimonial avatars have names but are template placeholders.

**How to fix:**
1. Media > Library > click the logo > Alternative Text: 'Lending Workshop logo'.
2. Click each photo and describe it, e.g. 'Couple signing home loan documents'.
3. In Elementor: click image > Content > Image > Alt text if it is overridden there.

**Paste this:**

```html
<img src="https://lendingworkshop.com.au/wp-content/uploads/2023/01/LOGO-1-scaled.jpg" alt="Lending Workshop logo">
```

**Affected pages:**
- https://lendingworkshop.com.au/
- https://lendingworkshop.com.au/services/
- https://lendingworkshop.com.au/process/
- https://lendingworkshop.com.au/about-us-2/
- https://lendingworkshop.com.au/contact-us/

### - [ ] 11. Phone number is not tap-to-call

**Impact:** Med. **Effort:** 5 min. **Where:** Code.

**What's wrong:** On a phone, people want to tap the number. It is plain text, only on the contact page, and not in the header or footer.

**Evidence:** 0 tel: links on any page. 0415 719 759 appears only on /contact-us/ as text.

**How to fix:**
1. Elementor: edit the Contact page, select the phone text, add link: tel:+61415719759.
2. Add the same link to the header and footer so it shows on every page.

**Paste this:**

```html
<a href="tel:+61415719759">0415 719 759</a>
```

**Affected pages:**
- https://lendingworkshop.com.au/contact-us/
- Header and footer (all pages)

### - [ ] 12. Logo and photos are far too big

**Impact:** Med. **Effort:** 30 min. **Where:** Code.

**What's wrong:** The logo is 2560 x 1731 pixels (170,595 bytes) but shown small, and loads 2 to 3 times per page. Photos are JPEG, not WebP.

**Evidence:** LOGO-1-scaled.jpg = 170,595 bytes. ann-danilina...-1024x683.jpg = 138,896 bytes. northfolk...-1024x576.jpg = 69,807 bytes. No WebP or AVIF used.

**How to fix:**
1. Export the logo at about 400 px wide as PNG or WebP (aim under 20 KB) and re-upload.
2. Install the free ShortPixel or Imagify plugin. Turn on WebP conversion and bulk-optimise the Media Library.
3. In Elementor, replace the logo with the smaller file.

**Affected pages:**
- Header and footer logo (all pages)
- https://lendingworkshop.com.au/ (hero photo)
- https://lendingworkshop.com.au/process/ (photo)

### - [ ] 13. Resubmit the sitemap after adding Yoast

**Impact:** Med. **Effort:** 5 min. **Where:** Search Console.

**What's wrong:** Yoast replaces WordPress's own sitemap with its own address. If you do not resubmit, Google keeps the old one.

**Evidence:** Today: /sitemap.xml 301 -> /wp-sitemap.xml (index of 3 sitemaps: 1 post, 5 pages + home, 1 category). Yoast will use /sitemap_index.xml.

**How to fix:**
1. Search Console > Sitemaps.
2. Remove wp-sitemap.xml if listed. Add sitemap_index.xml and click Submit.
3. Status should say Success within a day or two.
4. Confirm robots.txt now lists the new sitemap line.

**Paste this:**

```text
Sitemap: https://lendingworkshop.com.au/sitemap_index.xml
```

**Affected pages:**
- https://lendingworkshop.com.au/robots.txt

### - [ ] 14. 'Lending workshop' sounds like a training course

**Impact:** Med. **Effort:** 15 min. **Where:** Other.

**What's wrong:** A search for the name mostly returns industry training events, not you. The name alone will not carry you, so tell Google what you are.

**Evidence:** Web search for site:lendingworkshop.com.au returned no pages from the domain. A search for the brand with owner name returned unrelated brokers and training pages (not verified in Google itself).

**How to fix:**
1. Always pair the name with 'mortgage broker' and your suburb in titles, H1 and Business Profile description.
2. Use one consistent form: 'Lending Workshop' (capital W), 'Lending Workshop Pty Ltd' for legal use.
3. Add the sameAs links in the schema snippet once profiles exist.

**Affected pages:**
- https://lendingworkshop.com.au/
- Business Profile

### - [ ] 15. No social share tags (Open Graph, Twitter)

**Impact:** Low. **Effort:** 5 min. **Where:** Code.

**What's wrong:** When someone shares the link on Facebook, WhatsApp or LinkedIn, there is no controlled title or image.

**Evidence:** 0 og: or twitter: meta tags in the home page source.

**How to fix:**
1. Yoast SEO > Settings > Site basics (or Social). Switch on Open Graph and Twitter card data.
2. Upload a default share image (1200 x 630 px) with the logo.
3. Yoast adds the tags to every page automatically.

**Paste this:**

```html
<meta property="og:title" content="Mortgage Broker [SUBURB] | Lending Workshop">
<meta property="og:description" content="Home, investment, refinance and business loans.">
<meta property="og:image" content="https://lendingworkshop.com.au/[SHARE-IMAGE-1200x630].jpg">
<meta property="og:url" content="https://lendingworkshop.com.au/">
<meta name="twitter:card" content="summary_large_image">
```

**Affected pages:**
- All pages

### - [ ] 16. www version takes two hops to the real site

**Impact:** Low. **Effort:** 30 min. **Where:** Code.

**What's wrong:** http://www goes to https://www and then to the non-www site. One hop is cleaner and a little faster.

**Evidence:** http://www.lendingworkshop.com.au/ -> 301 https://www.lendingworkshop.com.au/ -> 301 https://lendingworkshop.com.au/ (2 hops). http://lendingworkshop.com.au/ -> 301 https://lendingworkshop.com.au/ (1 hop, fine).

**How to fix:**
1. Ask the host, or edit .htaccess, to send both http and https www straight to https non-www in one rule.
2. Test again with: `curl -sIL http://www.lendingworkshop.com.au`

**Paste this:**

```apache
RewriteEngine On
RewriteCond %{HTTP_HOST} ^www\.lendingworkshop\.com\.au$ [NC]
RewriteRule ^(.*)$ https://lendingworkshop.com.au/$1 [R=301,L]
```

**Affected pages:**
- http://www.lendingworkshop.com.au/

### - [ ] 17. About page URL ends in '-2'

**Impact:** Low. **Effort:** 15 min. **Where:** Code.

**What's wrong:** The About page lives at /about-us-2/. /about-us/ redirects to the home page instead, which looks sloppy and wastes a good URL.

**Evidence:** /about-us-2/ = 200. /about-us -> 301 -> /  (home). Menu and sitemap use /about-us-2/.

**How to fix:**
1. Pages > About Us > Quick Edit: change the slug to about-us.
2. WordPress keeps a redirect from the old URL automatically.
3. Check the menu link still works.

**Affected pages:**
- https://lendingworkshop.com.au/about-us-2/

### - [ ] 18. Footer says 2023 and links to a redirect

**Impact:** Low. **Effort:** 5 min. **Where:** Code.

**What's wrong:** A 2023 copyright makes the site look unmaintained. The Privacy Policy link has no trailing slash so it redirects.

**Evidence:** Footer: 'Copyright ©2023 Lending Workshop'. Link href="https://lendingworkshop.com.au/privacy-policy" -> 301 -> /privacy-policy/.

**How to fix:**
1. Appearance > Elementor > Theme Builder > Footer > edit.
2. Change to '©2026' (or use a dynamic year).
3. Re-pick the Privacy Policy page in the link field so it uses the slash version.

**Affected pages:**
- Footer on every page

### - [ ] 19. No visitor tracking found

**Impact:** Low. **Effort:** 30 min. **Where:** Code.

**What's wrong:** Without analytics you cannot see which pages bring enquiries.

**Evidence:** No gtag, googletagmanager or analytics script in the home page source.

**How to fix:**
1. Create a free Google Analytics 4 property.
2. Install the Site Kit by Google plugin and connect it. It also shows Search Console data inside WordPress.
3. Check consent and privacy policy wording with your licensee.

**Affected pages:**
- Whole site

### - [ ] 20. Add Bing Webmaster Tools

**Impact:** Low. **Effort:** 5 min. **Where:** Other.

**What's wrong:** Bing has a smaller share, but it also feeds some AI and voice tools. It takes five minutes.

**Evidence:** Not verified whether the site is registered.

**How to fix:**
1. Go to bing.com/webmasters and sign in.
2. Choose 'Import from Google Search Console' and approve.
3. Also claim your listing at bingplaces.com (free).
4. Sitemap and verification carry across.

**Affected pages:**
- https://bing.com/webmasters

### - [ ] 21. Make the facts easy for AI answers

**Impact:** Low. **Effort:** 30 min. **Where:** Other.

**What's wrong:** AI tools quote clear, consistent facts. Today the site says little about where, who and what.

**Evidence:** /llms.txt returns 404. No schema on any page.

**How to fix:**
1. Add the business schema snippet and clear service pages (cards above).
2. State the basics in plain sentences on the About page: who, where, loan types, licence number.
3. Keep directory and Business Profile details identical.
4. llms.txt is optional and unproven. No major search engine has said it uses it. Skip it unless you have spare time.

**Affected pages:**
- https://lendingworkshop.com.au/about-us-2/
- https://lendingworkshop.com.au/

---

## Medium (5)

### - [ ] 22. Claim your Google Business Profile

**Impact:** High. **Effort:** 1 hour. **Where:** Google Business.

**What's wrong:** For 'mortgage broker near me', the map results at the top of Google come from your Business Profile, not your website. This is usually the biggest local lever.

**Evidence:** Not verified whether a profile exists. The site has no map embed and no link to a profile.

**How to fix:**
1. Go to business.google.com and search 'Lending Workshop'. Claim it if it exists, create it if not.
2. Name: exactly 'Lending Workshop' (no keywords stuffed in).
3. Category: Mortgage broker. Add Financial planner or Loan agency only if true.
4. If clients do not visit you, choose 'service area business' and hide the address. List the suburbs you serve.
5. Phone 0415 719 759, website https://lendingworkshop.com.au/, hours, services, a short description.
6. Verify (video or postcard). Add 5 or more photos.
7. Use the exact same name, address and phone as on the website.

**Affected pages:**
- Google Maps and Search

### - [ ] 23. Page loads too many fonts and scripts

**Impact:** Med. **Effort:** 1 hour. **Where:** Code.

**What's wrong:** Each page requests 3 Google font families in every weight (Roboto, Roboto Slab, Poppins), 15 stylesheets and 17 scripts. That slows the first view on mobile.

**Evidence:** Home source: fonts.googleapis.com request for 3 families x 18 variants (10,537 bytes of CSS before any font file). 15 stylesheets, 17 script tags, about 145 KB of own CSS/JS (Brotli).

**How to fix:**
1. Elementor > Site Settings > Global Fonts: pick one family and 2 weights. Remove the rest.
2. Elementor > Settings > Features: turn on 'Optimized Gzip' options and 'Inline Font Icons' if offered.
3. Install the free LiteSpeed Cache plugin (the host runs LiteSpeed): enable CSS/JS minify and combine, and Load JS deferred.
4. Re-test at pagespeed.web.dev.

**Affected pages:**
- All pages

### - [ ] 24. Elementor and PHP are out of date

**Impact:** Med. **Effort:** Half day. **Where:** Code.

**What's wrong:** Old software is a security and speed risk, and hackers on a finance site hurt trust. The server also tells the world its PHP version.

**Evidence:** Elementor and Elementor Pro 3.10.1 (CSS dated Jan 2023), WPForms Lite 1.7.9.1, PHP/8.0.30 (header x-powered-by, PHP 8.0 reached end of life in Nov 2023). /xmlrpc.php returns 200.

**How to fix:**
1. Take a full backup first (host control panel or UpdraftPlus).
2. Update on a staging copy if your host offers one: Elementor, Elementor Pro, WPForms, theme, WordPress.
3. In the host control panel, switch PHP to 8.3 or newer and re-check the site.
4. Block xmlrpc.php (Wordfence free, or ask the host).

**Affected pages:**
- Whole site

### - [ ] 25. Home and contact pages are very thin

**Impact:** Med. **Effort:** Half day. **Where:** Code.

**What's wrong:** Home has 138 words and Contact has 94. Google has little to judge you on.

**Evidence:** Visible words: / 138, /contact-us/ 94, /services/ 503, /process/ 496, /about-us-2/ 562.

**How to fix:**
1. Home: add 300 to 500 words: who you help, the 5 loan types with links, the areas you serve, 3 reasons to choose you, short FAQ.
2. Contact: add address or service area, opening hours, a map and what happens after they submit.
3. About: add Roopali's photo, her years in banking and her credentials.

**Affected pages:**
- https://lendingworkshop.com.au/
- https://lendingworkshop.com.au/contact-us/

### - [ ] 26. List the business in Australian directories

**Impact:** Med. **Effort:** Half day. **Where:** Other.

**What's wrong:** Consistent listings confirm to Google that the business is real and where it is. They can also send direct enquiries.

**Evidence:** The site links to no directories. Not verified which listings exist.

**How to fix:**
1. Use identical name, phone and address in every listing.
2. Do these first: Connective's find-a-broker page, your FBAA member profile (member M-353524 is in your footer), Apple Business Connect, Bing Places, Yellow Pages, True Local, Facebook and LinkedIn.
3. Add a link back to https://lendingworkshop.com.au/ in each.
4. Skip paid or spammy directory bundles.

**Affected pages:**
- Off-site

## Bigger (4)

### - [ ] 27. Give each loan type its own page

**Impact:** High. **Effort:** Ongoing. **Where:** Code.

**What's wrong:** All 5 services share one page. People search for one thing at a time ('first home buyer broker [suburb]'). One page can only rank for one of them.

**Evidence:** /services/ holds 5 H2 sections (First Home Buyers, Business Loan, Home/Investment Loan Refinance, Vehicle/Asset Finance, Investment Property Loan), 503 words in total.

**How to fix:**
1. Create one page per loan type, 400 to 600 words each, on its own URL.
2. Suggested set: /first-home-buyer-loans/, /refinance-home-loan/, /investment-property-loans/, /business-loans/, /vehicle-and-asset-finance/.
3. Add the suburb and a short FAQ to each. Link them from the Services page and menu.
4. Then add location pages only for areas you really serve, e.g. /mortgage-broker-[suburb]/, each with unique, useful text (no copy-paste).

**Affected pages:**
- https://lendingworkshop.com.au/services/

### - [ ] 28. Collect real Google reviews

**Impact:** High. **Effort:** Ongoing. **Where:** Google Business.

**What's wrong:** Reviews are the second biggest local factor and the trust signal for finance. There is no review link on the site.

**Evidence:** No Google review link or reviews markup anywhere on the site.

**How to fix:**
1. In your Business Profile click 'Ask for reviews' and copy the short link.
2. Send it by SMS or email a few days after each loan settles.
3. Reply to every review, short and polite.
4. Check with Connective compliance about what you can say in replies and testimonials.
5. Add the link and a 'Review us on Google' button to the site footer.

**Affected pages:**
- Google Business Profile

### - [ ] 29. Publish answers to real buyer questions

**Impact:** Med. **Effort:** Ongoing. **Where:** Code.

**What's wrong:** There is no blog and no FAQ. The only post is the 'Hello world!' sample.

**Evidence:** /wp-sitemap-posts-post-1.xml contains one URL: /hello-world/.

**How to fix:**
1. Write 1 short guide a month from real client questions: 'How much deposit do I need in [STATE]?', 'First home owner grants in [STATE]', 'When to refinance'.
2. Add a FAQ section to each loan page. FAQ markup will not show as rich results for most sites now, but the plain answers still help people and AI tools.
3. Link each guide to a loan page and the contact page.

**Affected pages:**
- New pages

### - [ ] 30. Earn a few links from local partners

**Impact:** Med. **Effort:** Ongoing. **Where:** Other.

**What's wrong:** Links from other trusted sites tell Google you are credible. A new broker site has almost none.

**Evidence:** Not measured. The site is small (8 URLs) and has no public content others are likely to link to yet.

**How to fix:**
1. Ask partners you already work with: local real estate agents, conveyancers, accountants, financial planners. Offer a link on their 'trusted partners' page, and link back.
2. Sponsor a local club or event that lists sponsors with links.
3. Publish one useful local guide (see content card, fix 29) that partners can share.
4. Avoid bought links.

**Affected pages:**
- Off-site

---

## Search Console setup, step by step

Do these in order. Tick each step as you go in the report.

1. **Verify the domain.** search.google.com/search-console > Add property > Domain > lendingworkshop.com.au. Copy the TXT record and add it at your domain registrar's DNS page. Click Verify. (Easiest alternative: URL prefix > install the Site Kit plugin.)
2. **Submit the sitemap.** Left menu > Sitemaps. Enter sitemap_index.xml (or wp-sitemap.xml until Yoast is on). Submit.
3. **Request indexing for the key pages.** Top search bar > paste each URL: /, /services/, /process/, /about-us-2/, /contact-us/ > Request indexing. Do this after the fixes above go live, not before.
4. **Check the Pages report.** Left menu > Pages. Look at 'Why pages are not indexed'. Anything under 'Crawled, currently not indexed' or 'Discovered' needs better content. Check again in 2 weeks.
5. **Connect with your Business Profile.** There is no direct link between the two tools. Make sure the website field in your Business Profile is exactly https://lendingworkshop.com.au/ and use Site Kit to see both in one place.

---

## What is already fine

- HTTPS works, http redirects to https
- Canonical tag on every main page
- Viewport tag present (mobile ready)
- Pages 301 to trailing slash, not duplicates
- Real 404 for missing pages
- robots.txt valid and lists the sitemap
- Sitemap: all 8 listed URLs return 200
- HTTP/2, Brotli compression, LiteSpeed
- Credit licence and CRN in every footer
- First image not lazy-loaded (good for speed)
- Static files cached for 7 days
- Favicon set (32, 192, 180 px)

---

## Every page checked

| URL | Status | Title (chars) | Meta desc | H1 | Words |
|-----|--------|---------------|-----------|----|-------|
| https://lendingworkshop.com.au/ | 200 | Lending workshop (16) | none | 0 | 138 |
| https://lendingworkshop.com.au/services/ | 200 | Services – Lending workshop (33) | none | 0 | 503 |
| https://lendingworkshop.com.au/process/ | 200 | Process – Lending workshop (32) | none | 0 | 496 |
| https://lendingworkshop.com.au/about-us-2/ | 200 | About Us – Lending workshop (33) | none | 0 | 562 |
| https://lendingworkshop.com.au/contact-us/ | 200 | Contact Us – Lending workshop (35) | none | 0 (starts at H5) | 94 |
| https://lendingworkshop.com.au/privacy-policy/ | 200 | Privacy Policy – Lending workshop (39) | none | 1 | long |
| https://lendingworkshop.com.au/hello-world/ | 200 | Hello world! – Lending workshop (37) | none | 1 | 126 |
| https://lendingworkshop.com.au/category/uncategorized/ | 200 | Uncategorized – Lending workshop (38) | none | 1 | 89 |

---

## Not measured

Core Web Vitals (Google's speed scores) were not measured. The PageSpeed Insights API refused with "quota exceeded" (HTTP 429), so no scores are shown. Run it at pagespeed.web.dev after the fixes.

## Not verified

- **Whether the site is in Google's index.** A site: search through the search tool used in the audit returned no pages from this domain, but that tool may not support the operator, so confirm in Search Console.
- **Brand and owner search.** A search for the brand and owner returned nothing about the business either.
- **Google Business Profile.** Not verified whether a profile exists (fix 22).
- **Bing.** Not verified whether the site is registered (fix 20).
- **Directory listings.** Not verified which listings exist (fix 26).
- **Testimonials.** Not verified whether the four testimonials on the About page are real clients (fix 5).
- **Brand search in Google.** The brand search result was not verified in Google itself (fix 14).
- **Search Console site: check.** Not verified, the tool may ignore the operator (fix 6).
- **Links.** Not measured (fix 30).
- **Word counts** are visible text outside menu and header.
- **Versions.** Elementor and plugin versions come from the file version tags in the page source.

## Placeholders to fill in

The report does not give a separate list, so these are the placeholders found in the snippets and steps. Replace each one with the real detail, or delete the line if you do not have it.

- [SUBURB]: the area you serve. Used in fixes 1, 2, 3, 4, 7, 8 and 15, and in the Services and Contact drafts.
- [CITY]: used in fix 3 (footer line) and in the schema areaServed list (fix 4).
- [STREET ADDRESS]: the shop-front address if it is public (fix 3).
- [STREET]: the street address for the schema (fix 4).
- [STATE]: used in fix 3 (address), fix 4 (addressRegion), and fix 29 (guide topics).
- [POSTCODE]: used in fix 3 (address) and fix 4 (postalCode).
- [GOOGLE BUSINESS PROFILE URL]: the Business Profile link for the schema sameAs list (fix 4).
- [LINKEDIN URL]: the LinkedIn page link for the schema sameAs list (fix 4).
- [SHARE-IMAGE-1200x630]: the default share image file name, 1200 x 630 px (fix 15).
- [PLACEHOLDER]: the general instruction in fix 4 to fill every placeholder in the schema.
- [suburb]: lower case form used in the suggested location page URL /mortgage-broker-[suburb]/ (fix 27) and the search example in fix 27.
