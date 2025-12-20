# VoidText

VoidText is a modern, client-side web application for extracting text from images, PDFs, and PowerPoint files using OCR and document parsing libraries.

It runs directly in the browser, requires no backend server, and prioritizes privacy while still offering optional cloud OCR for scanned documents.

---

## Features

- Image to Text (OCR)
- PDF to Text (text-based PDFs + OCR support)
- PowerPoint to Text (.pptx)
- Client-side processing (no server required)
- Optional cloud OCR via OCR.space
- Drag & drop file uploads
- Batch processing
- Copy individual results or all extracted text
- Responsive, modern UI
- Works fully in the browser

---

## Supported Formats

- Images: PNG, JPG, JPEG, GIF, BMP  
- Documents: PDF  
- Presentations: PPTX, PPT  

---

## How It Works

VoidText uses a combination of client-side libraries:

- **Tesseract.js** for OCR
- **PDF.js** for extracting text from PDFs
- **PizZip + Docxtemplater** for reading PowerPoint files

For scanned images or image-based PDFs, optional cloud OCR can be enabled using an OCR.space API key.

No files are uploaded to a server when using client-side mode.

---

## Privacy

- Client-side extraction runs entirely in your browser
- No backend or database
- API keys (if used) are stored locally in browser storage
- Files are never uploaded unless cloud OCR is explicitly selected

---

## Getting Started

1. Clone or download the repository
2. Open `index.html` in your browser
3. Upload files and extract text instantly

No build step or server setup required.

---

## Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript
- Tesseract.js
- PDF.js
- PizZip
- OCR.space API (optional)

---

## Use Cases

- Extract text from scanned documents
- Copy text from PDFs
- Convert presentation slides into editable text
- Quick OCR without installing software

---

## License

MIT License
