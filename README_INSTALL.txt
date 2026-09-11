UMROH + ANDALUSIA 2026 — PWA V3.2

This package preserves the V3.2 + Transport dashboard and adds PWA support.

IMPORTANT:
A local HTML file opened from Downloads/File Manager cannot normally be installed as a true PWA by Chrome because PWA installation/service workers require a web origin (normally HTTPS, or localhost for testing).

Recommended easiest route:
1. Put this folder on a simple HTTPS static host (for example GitHub Pages or Netlify).
2. Open the HTTPS dashboard URL in Chrome on the Samsung tablet.
3. Chrome menu should show “Install app” / “Add to Home screen”.
4. Install it. It will open without the normal browser address bar (standalone mode).

The dashboard's voucher storage uses IndexedDB in the browser. Keep using the same installed browser app/origin so uploaded vouchers remain available.
