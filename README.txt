TEST DRIVE AGREEMENT APP - VERCEL READY

How to deploy:
1. Upload this whole folder to GitHub, or drag this folder into Vercel.
2. Vercel settings:
   Framework: Other / Vite
   Install Command: npm install
   Build Command: npm run build
   Output Directory: dist
3. Open the Vercel https link on iPhone/iPad.
4. Tap Add to Home Screen for app-style use.

How to use:
- Best scan: take photo of the BACK of the driver's license barcode first.
- If barcode scan is not supported on that phone, use OCR photo scan.
- Always review fields before customer signs and before printing.

Notes:
- Camera requires HTTPS. Vercel provides HTTPS automatically.
- OCR needs internet because it loads Tesseract from CDN.
