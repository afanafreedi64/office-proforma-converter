OFFICE PROFORMA CONVERTER — FIRST PROTOTYPE
This is a limited proof of concept, not a finished office-grade converter.

WHAT WORKS
- Select a PDF and explicitly choose DOCX or XLSX.
- Extracts selectable text from a text-based PDF locally in the browser.
- Creates a basic editable DOCX or XLSX locally.
- Does not upload the source file.
- Includes a PWA manifest and service worker for install/cache support.

LIMITATIONS
- Complex table reconstruction, borders, merged cells, column widths, headers/footers and exact page layout are NOT implemented.
- Scanned PDF OCR and JPG/PNG OCR are NOT implemented.
- Online conversion fallback is NOT connected.
- External libraries load from CDN on first use. Open the hosted app online once to cache them; offline availability depends on browser cache and should be tested.
- No security, accuracy or retention audit has been completed.

HOW TO HOST/INSTALL
1. Host these files on an HTTPS static host (for example, a static site hosting service).
2. Open the HTTPS site in Chrome on the Galaxy Tab S9 while online.
3. Test conversion with a non-confidential text-based PDF.
4. In Chrome menu, choose Install app or Add to Home screen if offered.
5. Open once online before testing airplane-mode operation.

PRIVACY
This prototype performs local conversion only. It contains no online upload endpoint. Do not upload confidential government documents to any online service unless you have explicit authorization and have reviewed that service's terms.

NEXT DEVELOPMENT MILESTONES
1. Test on the actual tablet.
2. Add local OCR for images/scanned PDFs.
3. Add table/layout reconstruction and editable review.
4. Add a consent-gated online fallback only after selecting and reviewing a service.
