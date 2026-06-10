Test Drive Agreement App

Open index.html in Chrome/Safari/Edge.

Features:
- Phone/iPad camera upload for driver's license image
- OCR scan using Tesseract.js CDN
- Auto-fill customer name, address, license number, issuing state, expiration date when OCR reads the license clearly
- Manual phone number entry
- Vehicle/VIN/insurance fields
- Digital signature pad
- Print / Save PDF button
- Bottom copy summary section

Important:
- Review every field after OCR before printing/signing.
- OCR needs internet the first time because it loads Tesseract.js from CDN.
- For production dealership use, host this over HTTPS so phone cameras and clipboard work reliably.
