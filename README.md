# x4nthProductions
Static, responsive video-editor portfolio. No build or dependencies required.

## GitHub Pages
1. Upload this folder's contents to a GitHub repository (including .github).
2. In Settings → Pages → Build and deployment, select GitHub Actions.
3. Push to main. The included workflow deploys dist/.

## Behavior
Navigation swaps pages, rather than scrolling. All five supplied video links open on YouTube.
Basic: 2 requests, followed by a countdown of three calendar months. Premium: 5 requests. Full Pack: 20 requests. Paid packs reset after their last request. Only closing a panel after submitting a valid email counts a request; closing the initial form does not.
Payments and sending email happen outside this website. Copy email copies the address; Send an email opens a draft in the visitor's email app. No email is sent automatically.

## Limits and Admin
Progress uses localStorage in each browser. It is not tied to a verified customer, can be cleared, and is not a payment or completion record. The entered email is not sent to a server or stored.
The visible Admin route is locked, with no customer data or fake client-side password. A production private admin, verified accounts and shared limits require an authentication service and database. Those are not configured in this static delivery.

## Edit
Text, links and interactions: dist/app.js. Appearance: dist/style.css. Page shell: dist/index.html.
