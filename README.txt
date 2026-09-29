NOVA Luxury Footwear
====================

NOVA is a responsive luxury sneaker storefront built with HTML, CSS and
vanilla JavaScript. Open index.html to start the site.

Pages
-----
- index.html       Home storefront, categories, product collection and FAQ
- product.html     Product detail page with sizes, quantity and purchase actions
- cart.html        Full shopping cart and order summary
- checkout.html    Shipping and checkout form
- auth.html        Sign in and sign up experience
- faq.html         Shipping, sizing, returns and care information

Main user flows
---------------
- Home -> View Product -> Add to Cart or Buy Now
- Home -> Add to Cart -> Cart drawer -> cart.html -> checkout.html
- Account -> auth.html?mode=signin or auth.html?mode=signup
- Search, category filters, wishlist buttons and FAQ accordions are supported

Features
--------
- Responsive layouts for mobile, tablet, iPad, laptop and desktop
- Shared responsive navigation with menu, search, login and cart actions
- Shared footer across the dedicated pages
- Mobile horizontal product carousel and desktop sticky product panel
- Product filtering, product detail links and cart count updates
- Cart persistence using browser localStorage
- Demo account, coupon and newsletter interactions
- Luxury editorial sections, product cards and responsive forms

Project files
-------------
- style.css        Site design system, responsive layouts and component styling
- script.js        Product data and storefront, cart, account and checkout logic
- assest/          NOVA logo files and supplied visual assets

How to run
----------
1. Open index.html directly in a browser, or serve the folder with any static
	web server.
2. Use the navigation to test products, cart, account and checkout flows.

External resources
------------------
- Product and editorial images are loaded from Unsplash URLs.
- Fonts are loaded from Google Fonts.
- Icons and Bootstrap utilities are loaded from jsDelivr CDNs.
- Internet access is required for external images, fonts and CDN resources.

Storage note
------------
The demo stores cart contents, account details and newsletter signup data in
browser localStorage. No real payment or backend order processing is connected.


ORDER EMAIL SETUP
This GitHub Pages version uses FormSubmit to send checkout order details to shariq.mailbox1@gmail.com. On the first real order, FormSubmit may send a one-time activation/confirmation email to that inbox. After activation, orders can be forwarded from the static site without a custom backend.
LIVE CARD PAYMENTS
The checkout now has premium payment-method UI. Actual card charging requires a merchant gateway/backend (for example Stripe) and API credentials; this static package does not fake a successful card charge.


UPDATE: Added premium 3D Contact Us page and compact redesigned 3D homepage slider.

V3 UPDATE
- Added shop.html and categories.html with premium editorial image layouts.
- Shared sticky 3D navbar/footer is injected across inner pages for consistent geometry.
- Shop/category/about imagery uses remote Unsplash-hosted images; internet connection is required for those images to load.
- About page now includes an additional editorial gallery.
