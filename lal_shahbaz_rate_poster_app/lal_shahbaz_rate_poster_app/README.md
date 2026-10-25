# Lal Shahbaz Rate Poster Generator

A browser-based poster generator for the Lal Shahbaz Roller Floor Mill rate poster. The default blank template is embedded inside `index.html`, so the page does not need to fetch a separate background image.

## Quick start
1. Extract the ZIP.
2. Open `index.html` in a modern browser. If your browser restricts local HTML files, use the hosted setup below.
3. Edit the date, contact number, and any product rows.
4. Select **Download PNG** or **Download PDF**.

## Use it from any device (recommended)
Upload `index.html` to a static host such as GitHub Pages. In GitHub, create a repository, upload `index.html`, then open **Settings → Pages** and enable deployment from the main branch/root. Open the published URL on your iPad, phone, or computer. No backend/server is needed.

## Notes
- Poster rendering happens in the browser; product data is not sent to a server.
- PNG export is local. Direct PDF download uses jsPDF from a CDN, so internet access is needed for that button. If the library cannot load, the app opens a print dialog; choose **Save as PDF**.
- Four products fit the existing blank template table while preserving its table lines. If you add a different number of products, the app redraws only the table body and separators so all rows fit; the rest of the template remains unchanged.
- Use the optional template upload to test another blank background. If changing the template design or dimensions, the date/table placement coordinates may need adjustment in the code.
