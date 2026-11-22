# X Network Ltd website — We are X Network / Book (22 Nov 2026)

Draft only. Nothing has been published, merged to main, or made live.

This branch starts from `site-support-22nov` and adds:

- `we-are.html` — We are X Network: who we are, plus every current service as a card with a **Book this service** button.
- `book.html` — enquiry / booking form. Each service button opens this page with that service already selected.
- Nav links for **We are** and **Book** on every page.

## Form backend (private, simplest option)

The booking form uses a **mailto** fallback by default. Submit opens the visitor's email app, addressed to `xnetworkltd@gmail.com`, with the form details in the message.

Formsubmit or Formspree could send enquiries straight to that inbox without opening an email app. That needs Dave's OK before it is switched on, because it uses a third-party form service.

## Preview locally

Open `we-are.html` or `book.html`, or run:

```
python3 -m http.server 8000
```

in this folder and open http://localhost:8000/we-are.html and http://localhost:8000/book.html

## Services listed

Sourced only from the live site (17 Nov 2026) and the pending `site-support-22nov` branch. No new capabilities added.

Live site: Utility Support (gas, water, power); Labour Supply; Full Subcontract Services; Excavation and Mains Support; Reinstatement (tarmac, flagging, kerbs); Logistical Support; Site Management; Problem Solving; Next Generation.

Added on `site-support-22nov`: Groundworks; Site labourers; Traffic management; Site support services (electrical engineers, plumbers and other skilled trades).

## To publish (only after Dave approves — do not do this yet)

1. Dave signs off the preview screenshots, wording, and form method.
2. Open a pull request from `we-are-xnetwork-22nov` (this branch includes the site-support work).
3. Merge only after Dave's sign-off. GitHub Pages serves `main`.
4. After it is live, check https://xnetworkltd.co.uk/we-are.html and https://xnetworkltd.co.uk/book.html on desktop and mobile, then point Facebook, LinkedIn and Instagram to the Book page.
