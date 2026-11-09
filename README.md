# Mumbai Zone Desk

Single-page web app for zone lookup and Ready Reckoner valuation (Mumbai). Everything lives in `index.html` (maps, rate data and logic are embedded); no build step.

**Live:** https://sai-1322.github.io/Mumbai-Zone-Desk/

- Saved outlines, approvals and lookups are stored in the browser (localStorage) and are not shared between users or devices.
- PDF reports download directly. The PDF library (jsPDF) and fonts load from CDNs, so an internet connection is needed.

To run locally, open `index.html` in a browser.
