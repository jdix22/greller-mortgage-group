# Greller Mortgage Group: website prototype

Prototype redesign for Emilie Greller and Aaron Klimitz (mortgage agents with BRX Mortgage Inc.).
Everything on the page comes from their two BRX agent pages (brxmortgage.com/agent/emilie-greller
and /agent/aaron-klimitz). Their own domain, gmgmortgages.com, currently shows a GoDaddy
"Launching Soon" page, so this is built to become that site.

Preview: https://jdix22.github.io/greller-mortgage-group/
Add `?agent=aaron` to the link to open with Aaron's application forms selected.

## What's new compared with the BRX pages
- One team site instead of two template pages, with the Greller Mortgage Group name front and centre.
- Apply-with switch: each "Buy / Refinance / Renew" button opens Emilie's or Aaron's own Typeform.
- Canadian payment calculator: minimum down payment, default insurance premium, stress-test rate,
  accelerated payments, and a balance-over-time chart.
- Renewal planner: enter the renewal date, see when the 120-day window opens.
- Plain-answer FAQ, lender logos, full brokerage licence block, mobile call/apply bar.
- Search and AI basics: business and agent structured data, social preview image, sitemap, robots, 404.

## Before it goes live (owner questions)
1. Confirm they're happy using the name "Greller Mortgage Group" publicly (it's the name on gmgmortgages.com).
2. Logo: none existed, so a simple house-roof "G" mark was drawn. Keep it or send a real one.
3. NSID licence number: the agent block shows #2025-3000563, the BRX footer shows #2023-3000563. Page uses 2025. Confirm.
4. OK to show lender logos (TD, Scotiabank, First National, Home Trust, RMG)? They were on the BRX pages.
5. Anything to add: city or office area, years in the business, languages, reviews/testimonials, a short personal line for each.
6. Should the FAQ say how agents are paid (usually by the lender)? Left out until they confirm their wording.
7. Contact form opens the visitor's email app. For direct sending, set FORM_ENDPOINT in index.html (Formspree or similar).
8. BRX may need to approve the site under its advertising rules. Brokerage name and FSRA licence #13463 are shown in the hero strip and footer.

## At launch on gmgmortgages.com
- Remove `<meta name="robots" content="noindex">` from index.html.
- Swap every `https://jdix22.github.io/greller-mortgage-group/` (canonical, og:url, og:image, JSON-LD, robots.txt, sitemap.xml) for `https://gmgmortgages.com/`, and fix the `/greller-mortgage-group/` paths in 404.html.
- Owner to-dos: claim a Google Business Profile (service-area business, no public address), Bing Places, and use the same one-line description everywhere:
  "Greller Mortgage Group is Emilie Greller and Aaron Klimitz, licensed mortgage agents with BRX Mortgage Inc. (FSRA licence #13463) who help clients across Ontario buy a home, refinance to pay off debt or invest, and renew their mortgage."
- Ask happy clients for Google reviews.

Website designed by jdix.ca
