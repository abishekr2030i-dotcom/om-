OM SAI INTERNATIONAL — VERSION 2

This version adds a real local backend and admin portal.

RUN:
1. Install Node.js LTS.
2. Open a terminal in this folder.
3. Run: node server.js
4. Customer site: http://localhost:3000
5. Admin: http://localhost:3000/admin

DEFAULT ADMIN (CHANGE BEFORE DEPLOYMENT):
Username: admin
Password: change-this-password

The admin can view orders, update order status and edit prices. Customer orders are stored in data/orders.json. Products are stored in data/products.json.

PRODUCTION TODO:
- Use a hosted database instead of JSON files.
- Deploy with HTTPS.
- Set strong ADMIN_USER and ADMIN_PASSWORD environment variables.
- Add the real eSewa merchant/QR details.
- Add automatic WhatsApp Business/API notifications if desired.
- Add exact product catalogue and exact TMT mm sizes.
- Add exact Google Maps pin.
