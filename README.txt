KR INVESTMENT payment page

Files:
- payment.html
- assets/phonepe-qr.jpg (the QR image supplied by you)

How to add it:
1. Copy payment.html into the main website/repository folder, alongside index.html.
2. Copy the assets folder into that same folder (keep the QR image at assets/phonepe-qr.jpg).
3. Commit and push both files to GitHub.
4. In the VPS terminal run:
   cd /var/www/krinvestment.in
   git pull

The payment page will then be available at:
https://krinvestment.in/payment.html

To show a Payment link in the site's existing menu, add this link to the navigation in index.html, services.html, and support.html:
<a href="payment.html">Payment</a>

The QR image is copied as supplied. The page includes a copy button for krinvestment@ibl and a mobile-friendly layout.
