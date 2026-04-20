alright. so my plan is this
- prepare notion template for Issue Log
- prepare notion template for Acceptance Criteria
- prepare notion template for Top Five Issues
  - may be worth combining into Issue Log, just adding a tag called "Top Five Issues"
- prepare google drive storage for the screenshots
- prepare loom account

that's all for prep only, next step is the actual QA
- pass 1 - functional QA
- pass 2 - UX & conversion killers
- pass 3 - visual & responsive
- pass 4 - content & copy
- pass 5 - accessibility
- pass 6 - performance

next is writing the acceptance criteria
- pick 3 critical components
- write each

next is picking the top 5 issues ranked by impact
- pick 5
- write explainers detailing why


| # | Category | Issue | Steps to Reproduce | Expected | Actual | Severity | Evidence |
| - | -------- | ----- | ------------------ | -------- | ------ | -------- | -------- |

Critical – breaks purchase or CTA
High – hurts conversion or trust
Medium – noticeable UX problem
Low – polish / cosmetic

Functional
UX & Conversion
Visual & UI
Responsiveness
Content & Copy
Accessibility
Performance


Step 1: Open the page and act like a buyer
Go here:
👉 https://gruns.co/pages/first-order-qa-case-study
Do one clean pass pretending you want to buy:
Scroll top to bottom
Click obvious CTAs
Try to select variants (if any)
Try to add to cart
Look for trust signals, pricing clarity, guarantees
Don’t log anything yet. Just absorb.

Step 2: Do structured QA passes (this is the key)
Now you QA in layers, not randomly.
Pass 1 — Functional QA (highest value)
Check:
- CTAs: do they work? where do they go?
- Add to cart / buy buttons
- Variant selectors
- Modals (reviews, FAQs, guarantees)
- Sticky elements (headers, buy box)
- If something breaks or behaves weirdly → log it

Pass 2 — UX & conversion killers
Ask brutally:
Is it clear what’s being sold?
Is pricing obvious?
Is there cognitive overload?
Are CTAs consistent?
Anything confusing, misleading, or friction-heavy?
If you hesitate as a user → that’s a UX issue.

Pass 3 — Visual & responsive
Do this:
Desktop (full width)
Desktop (narrow)
Mobile (Chrome DevTools → iPhone 12)
Look for:
Overlapping elements
Text cut off
Buttons too small
Awkward spacing
Sticky elements blocking content

Pass 4 — Content & copy
Check for:
Typos
Inconsistent capitalization
Claims that feel unclear or legally risky
Mismatch between CTA copy and action
QA absolutely includes copy. Good to flag.

Pass 5 — Accessibility (basic, not WCAG PhD)
Do only basics:
Tab through page (can you reach CTAs?)
Focus states visible?
Images missing alt text?
Color contrast on buttons/text feel weak?
Don’t overdo this. 2–4 solid issues is enough.

Pass 6 — Performance (light touch)
Open DevTools → Lighthouse → Mobile:
Look for obvious red flags
Huge images
Lazy-loaded content popping in late
CLS (layout shifting)
You’re not a perf engineer. Just show awareness.

Link not clicking and redirecting to #reviews

CTA button leads to home page #offers instead of same page PDP

CTA not redirecting to same page PDP (cuz there is none) or to other page PDP

CTA not redirecting to same page PDP

PDP layout looks substantially different from home page's PDP

BG and possibly content container isn't filling up the width of the viewport, original page does

These statistics no longer match what's shown on the home pageDAILY TASK

https://gruns.co/
link - "4.8 stars from 85,000 reviews | 1,000,000+ members" not working
link - "4.8/5.0 (85,000), 1M+ Customers" not working
Cart - low sugar 1 quantity (otp) 4 pcs - total error
Cart - low sugar 1 quantity (otp) 5 pcs - total error
Cart - sugarfree 1 quantity (subs) 4 pcs - total error
Cart - sugarfree 1 quantity (subs) 5 pcs - total error
Cart - sugarfree 1 quantity (otp) 4 pcs - total error
Cart - sugarfree 1 quantity (otp) 5 pcs - total error
TikTok link - not working
"Try Gruns" button - 

https://gruns.co/pages/surprise
TikTok link - not working
Cart - low sugar 1 quantity (otp) 4 pcs - total error
Cart - low sugar 1 quantity (otp) 5 pcs - total error
Cart - sugarfree 1 quantity (subs) 4 pcs - total error
Cart - sugarfree 1 quantity (subs) 5 pcs - total error
Cart - sugarfree 1 quantity (otp) 4 pcs - total error
Cart - sugarfree 1 quantity (otp) 5 pcs - total error
"Try Gruns" button - 

https://gruns.co/pages/vip
link - "4.8/5.0 (85,000), 1M+ Customers" not working
Cart - low sugar 1 quantity (otp) 4 pcs - total error
Cart - low sugar 1 quantity (otp) 5 pcs - total error
Cart - sugarfree 1 quantity (subs) 4 pcs - total error
Cart - sugarfree 1 quantity (subs) 5 pcs - total error
Cart - sugarfree 1 quantity (otp) 4 pcs - total error
Cart - sugarfree 1 quantity (otp) 5 pcs - total error
TikTok link - not working
"Try Gruns" button - 

https://gruns.co/pages/links
link - "✨ Limited Time Sale ✨" not working
TikTok link - not working

https://gruns.co/pages/gruns-kids-daily
link - "4.8 stars from 85,000 reviews | 1,000,000+ members" not working
link - "4.8/5.0 (85,000), 1M+ Customers" not working
Cart - "Mango Sorbet" sugarfree - sold out
"Try Gruns" button - 
Button "Stock Up While You Can!" - not fitted well
TikTok link - not working

https://gruns.co/pages/first-order-gruns-kids-daily
link - "4.8/5.0 (85,000), 1M+ Customers" not working
Cart - "Mango Sorbet" sugarfree - sold out
Button "Stock Up While You Can!" - not fitted well
TikTok link - not working
"Try Gruns" button - 

https://gruns.co/pages/surprise-gruns-kids-daily
Cart - "Mango Sorbet" sugarfree - "There was an error adding this item to your cart. Please try again."
"Try Gruns" button - 
Button "Stock Up While You Can!" - not fitted well
TikTok link - not working

https://gruns.co/pages/vip-gruns-kids-daily
link - "4.8/5.0 (85,000), 1M+ Customers" not working
Cart - "Mango Sorbet" sugarfree - sold out
"Try Gruns" button - 
TikTok link - not working

https://nutrops.co/
Cart - "Start Now" Button - Auto check out
"Connor Weaver" image - need to enhance quality
"Madison Hughes" image - need to enhance quality
"Shop Nütrops" Button - "undefined" text will appear
"Accessibility Adjustments" Button - should be movable

https://nutrops.co/products/nutrops-daily-gummies
"Accessibility Adjustments" Button - should be movable

https://nutrops.co/pages/first-order
"Accessibility Adjustments" Button - should be movable
Cart - "Start Now" Button - Auto check out

https://nutrops.co/pages/surprise
"Accessibility Adjustments" Button - should be movable
"nutrops" link -  not working
"4.8 stars from 20,000 reviews | 250,000+ members" link - not working
Cart - "Start Now" Button - Auto check out
"Connor Weaver" image - need to enhance quality
"Madison Hughes" image - need to enhance quality

https://nutrops.co/pages/links
"Grüns Adults" link - not working
"Grüns Kids" link - not working
"Accessibility Adjustments" Button - should be movable

https://immun.co/
"Grüns Adults" link - not working
"Grüns Kids" link - not working
"Accessibility" link - not working

https://immun.co/pages/first-order
"Grüns Adults" link - not working
"Grüns Kids" link - not working
"Accessibility" link - not working

https://immun.co/pages/surprise
"Grüns Adults" link - not working
"Grüns Kids" link - not working
"Accessibility" link - not working

https://immun.co/pages/links
"View Immun Ingredients" Button - Image object is required for this component

https://juced.co/
none

https://juced.co/pages/first-order
reviews "VS Alternative" duplicate video
reviews no "Convenience" video shown

https://juced.co/pages/surprise
"View Nutrition Label" Button - not working

https://juced.co/pages/links
"Try Jüced Now" Button - not working

Buy office supplies tomorrow
Prepare invoice template
Review Asana
Review Notion

Add to cart, refresh page and confirm cart is correct
Add to cart, hard-refresh page (command + r) and confirm cart is correct
Add to cart, leave site and come back and confirm cart is correct
Add to cart, go to checkout and back to PDP, confirm cart is correct
Add products to max (5 each)
Remove products to none
Add product, add upsell
Add product, add upsell, remove upsell
Add product, add upsell, remove upsell, remove product