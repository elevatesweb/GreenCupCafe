# Elevent Café OS — Interactive Browser Prototype

Created for Elevent Web & Solutions. Open `index.html` in Chrome, Edge or Firefox. No installation, Python, database or server required.

## Demo walkthrough
1. Open **Customer Menu**, choose a table, add food, choose Pay Later or Pay Now (simulated), and place an order.
2. Open **Kitchen Display** to see the new ticket, mark Preparing → Ready → Served.
3. Open **Table Management** to see occupied tables and copy a table-specific demo URL (`index.html?table=5`).
4. Open **Billing & Payments** to review a consolidated table bill, record a simulated cash/UPI payment, print with browser print, and close the table.
5. Open **Café Settings** to rename the café, set table count and demo tax rate.

## Limitations — not production ready
- Data persists only in the current browser using localStorage. Different devices do not sync.
- Payments are simulated; no payment gateway, real UPI transaction, verification, refunds or settlements.
- QR URLs can be copied but physical QR image generation/printing is not implemented.
- Browser print works for a demo receipt; direct ESC/POS thermal printing is not implemented.
- The receipt is not a compliant GST tax invoice; tax is an illustrative flat percentage.
- No staff authentication, server authorization, real-time multi-device notifications, inventory or secure table session management.
- Sample menu prices, café name and address are fictional.
- Internet is only needed to load optional Google Fonts; fallback system fonts work offline.

## Production phase
Implement a backend with a database, authenticated staff roles, secure table sessions, verified gateway webhooks, correct tax configuration, invoice numbering, printer integration, multi-device real-time updates, monitoring and backups.
