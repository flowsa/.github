---
name: Webflow Website Go Live Checklist
about: Webflow Website Go Live Checklist
title: ''
labels: ''
assignees: ''

---

### LIVE: Google (Analytics/Tag Manager/Webmaster)

- [ ] Has google analytics account been setup on google?
- [ ] Is a tag manager account set up?
- [ ] Have you added Tag Manager code on pages
- [ ] Has analytics tag been added to tag manager?
- [ ] Has any goal/event tracking required been setup?
- [ ] Setup monthly notification on Google Analytics - to go to the PM
- [ ] Setup Google Webmaster Tools
- [ ] Have relevant 301 redirects been created for key pages in Webflow's Redirects settings - if this is not a new website.
- [ ] Check top 100 pages by traffic on Google Analytics and ensure each is 301 redirected or resolves to a correct page - if this is not a new website
- [ ] Are 404 pages working properly (using Webflow's 404 page)
- [ ] Has the global site description and keywords been added (SEO Settings)?
- [ ] Has the global title tag been set?
- [ ] Have any page specific description tags been added?
- [ ] Have any page specific title tags been added?

### LIVE: Performance

- [ ] Has site been tested on Page Speed Google Insights - not lower to score 80%?
- [ ] Have images been compressed/optimized (or set to auto-optimize) in the Webflow Asset Manager?

### LIVE: Forms (if applicable)

- [ ] Check sending and receiving email addresses for native Webflow form notifications (if used)
- [ ] Has the thank you state/page been set up for each form?
- [ ] Do all the enquiry/contact forms work?
- [ ] Has the client acknowledged the receipt of the form?
- [ ] Does the reCAPTCHA (Webflow's built-in form protection) work?
- [ ] If forms are piped to a third-party integration (Zapier, Make, CRM), has that connection been tested end-to-end?

### LIVE: Memberships (if applicable, Webflow Memberships feature only)

- [ ] Have you checked the member registration forms - sign up, log in, forgot password?
- [ ] Auto-responder: has the notification email (to the user) been set up to confirm registration?
- [ ] Auto-responder: has the client been notified (via email to client) of the new registration?
- [ ] Have access groups and gated content been tested with a test member account?

### LIVE: Hosting / DNS (if applicable)

- [ ] If DNS change is required, save old IP address/records in comments
- [ ] Have the site's DNS settings been checked per Webflow's hosting requirements (CNAME for www, A/ALIAS record or Webflow's proxy IP for the root domain)? http://www.whatsmydns.net/#A/www.flowsa.com
- [ ] Where does the MX record point to? Does the client's email still work after the DNS change?
- [ ] Notify [Sabo Ndlovu](mailto:sabo@flowsa.com) of site going live so that billing can be started.
- [ ] Confirm the correct Webflow site plan (hosting + CMS/Ecommerce tier) has been purchased for this project
- [ ] SSL certificate - confirm Webflow has auto-provisioned and it's showing as active (no manual setup needed)
- [ ] Confirm automatic HTTP → HTTPS redirect is enabled in Webflow hosting settings

### LIVE: After going live checks and tests

- [ ] Global variables - company meta data updated: phone number, social media accounts
- [ ] Global variables: social network platforms are all set
- [ ] If Memberships is used, confirm Forgot Password is functioning as expected
- [ ] Generate random password (Webflow account/CMS editor login, if applicable) and send to IT for addition to 1Password
- [ ] Have the correct email addresses been set for notifications/enquiries, etc and tested with the recipient?
- [ ] Have you added the site to Uptime Robot?
- [ ] 1 week after go live calendar entry with project manager to review traffic
- [ ] 1 month after go live calendar entry with project manager to review traffic
- [ ] Does the site have a sitemap (Webflow auto-generates sitemap.xml)?
- [ ] Has the sitemap been added to Google webmaster tools?
- [ ] Has Webmaster been verified?
- [ ] Has Webmaster property been linked to Analytics account?
- [ ] Is Analytics code tracking?
- [ ] Is robots.txt file (Webflow SEO settings) set to allow Google etc bots?
- [ ] Check Webflow hosting plan billing is on schedule
- [ ] Broken Link check
- [ ] Cross-Browser Check (Chrome, Safari, and Firefox)
- [ ] Mobile/responsive check across breakpoints (Webflow's mobile, tablet, and desktop views)

### LIVE: Campaign Monitor / Email Marketing (if applicable)

- [ ] Does the subscribe form work and log people's details in the correct subscriber list?
- [ ] Has thank you page been set up on the website?
- [ ] Has DKIM "sender signature" been set up on the domain (to pass spam blocking)

### Webflow Specific

- [ ] Graph Image URL (Open Graph settings)
- [ ] Ensure favicon and Webclip have been set with the client's logo images
- [ ] Ensure custom code implementation (in Page Settings or Site Settings > Custom Code) works as expected
- [ ] Confirm CMS collections, fields, and reference/multi-reference bindings are correct
- [ ] Confirm staging/preview domain is not indexable and production domain is set as canonical

### Webflow LIVE: Design Consistency

- [ ] Ensure all titles and paragraphs are styled to match the brand (using Webflow's Style Manager/Global Swatches)
- [ ] Utilized standard color names/global swatches rather than one-off hex values
- [ ] Margin and padding to match the design system
- [ ] Upload fonts as custom WOFF files or use Google's integrated font API
- [ ] Double-check all design elements for alignment, responsiveness

### Not relevant

Drag any checkboxes not relevant below.
