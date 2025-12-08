# CGP Resume Converter

A web-based tool that converts candidate resumes into CGP (Cornerstone Global Partners) formatted Word documents using AI.

![CGP Resume Converter](https://img.shields.io/badge/Powered%20by-Gemini%20AI-blue)
![License](https://img.shields.io/badge/License-Private-red)

## Features

- 📄 **PDF Upload** - Drag and drop or click to upload resume PDFs
- 🤖 **AI-Powered Parsing** - Uses Google Gemini 2.5 Flash to intelligently extract resume information
- 📝 **Structured Output** - Generates professionally formatted Word documents
- 🎨 **CGP Branding** - Orange section headers matching CGP template style
- 📱 **Responsive Design** - Works on desktop and mobile devices

## How to Use

1. **Upload Resume** - Upload the candidate's resume in PDF format
2. **Enter Details** - Fill in candidate information:
   - Name
   - Nationality
   - Gender
   - Expected Salary
   - Notice Period
3. **Generate** - Click "Generate CGP Resume" to process
4. **Download** - Preview and download the formatted .docx file

## Deployment

This is a static website that can be hosted on GitHub Pages:

1. Fork or clone this repository
2. Go to repository Settings > Pages
3. Select "Deploy from a branch"
4. Choose `main` branch and `/ (root)` folder
5. Click Save

Your site will be available at: `https://[your-username].github.io/[repo-name]/`

## Technology Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **AI**: Google Gemini 2.5 Flash API
- **PDF Processing**: PDF.js
- **Document Generation**: docx.js
- **File Download**: FileSaver.js

## Files

```
cgp-resume-converter/
├── index.html      # Main application (single file)
└── README.md       # This file
```

## API Usage

This app uses the Google Gemini API with a free tier:
- 20 requests per day
- 250K tokens per minute

For higher usage, consider upgrading to a paid plan at [Google AI Studio](https://aistudio.google.com/).

## Privacy

- Resume data is processed client-side for PDF text extraction
- Resume text is sent to Google Gemini API for AI processing
- No data is stored on any server

## License

Private - For Cornerstone Global Partners Pte Ltd use only.

---

Built with ❤️ for CGP Personnel
