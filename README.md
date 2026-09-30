

🌐 Live Website: https://25bca101-cmd.github.io/LegalEase-AI-Powered-Legal-Document-Generator/
# LegalEase – Naan Mudhalvan Project

## What is included
- `website/index.html` – responsive web application
- `website/style.css` – responsive UI styling
- `website/script.js` – document generation, editing, TXT download, print/PDF
- `LegalEase_Naan_Mudhalvan_Documentation.pdf` – project report

## How to run
1. Extract the ZIP.
2. Open `website/index.html` in Chrome.
3. Enter document type, parties, terms and effective date.
4. Click **Generate Document**.
5. Edit the generated text if needed.
6. Use **Print / Save PDF** to create a PDF.

## Project architecture
Frontend: HTML5 + CSS3 + JavaScript.
The prototype is intentionally deployable without a server, so it is easy to demonstrate from a laptop or mobile browser.

## AI extension
The original LegalEase concept uses a Gemini-powered backend with FastAPI and a Streamlit frontend. This submission version provides a working browser prototype. A future version can connect `generateDocument()` to a secure backend API such as `/generate`, keeping the API key on the server.

## Important
This is an educational prototype. Generated documents are drafts and should be reviewed by a qualified legal professional before real-world use.
