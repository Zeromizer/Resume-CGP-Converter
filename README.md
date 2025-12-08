# CGP Resume Converter

A web-based tool that converts candidate resumes into CGP (Cornerstone Global Partners) formatted Word documents using AI.

## Features

- 📄 **PDF Upload** - Drag and drop or click to upload resume PDFs
- 🤖 **AI-Powered Parsing** - Uses Google Gemini 2.5 Flash to intelligently extract resume information
- 📝 **Template-Based Output** - Uses the actual CGP template for perfect formatting
- 🎨 **Exact CGP Branding** - Header, footer, and all formatting exactly match your template

## Files

```
cgp-resume-converter/
├── index.html          # Main application
├── template.docx.b64   # CGP template (base64 encoded)
└── README.md           # This file
```

## How to Use

1. **Upload Resume** - Upload the candidate's resume in PDF format
2. **Enter Details** - Fill in candidate information (Name, Nationality, Gender, Salary, Notice Period)
3. **Generate** - Click "Generate CGP Resume" to process
4. **Download** - Preview and download the formatted .docx file

## Deployment on GitHub Pages

1. Create a new GitHub repository
2. Upload all three files (index.html, template.docx.b64, README.md)
3. Go to Settings > Pages
4. Select "Deploy from a branch" > "main" > "/ (root)"
5. Your app will be live at: `https://[username].github.io/[repo-name]/`

## Technology Stack

- Google Gemini 2.5 Flash API (Free tier)
- PDF.js for PDF text extraction
- JSZip for template manipulation
- FileSaver.js for downloads

## API Limits (Free Tier)

- 20 requests per day
- 250K tokens per minute

---
Built for CGP Personnel
