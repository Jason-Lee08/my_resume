# My Resume Website

A clean, responsive resume website that looks great on any device and includes a PDF download option.

## Setup Instructions

1. Replace the content in `index.html` with your actual resume information
2. Add your PDF resume file named `resume.pdf` to this folder
3. Customize colors and styling in `styles.css` if desired

## Hosting on GitHub Pages

1. Push this repository to GitHub
2. Go to your repository settings
3. Navigate to "Pages" in the left sidebar
4. Under "Source", select the branch you want to deploy (usually `main`)
5. Click "Save"
6. Your site will be available at `https://yourusername.github.io/repository-name/`

## Features

- Responsive design that works on desktop, tablet, and mobile
- Professional layout optimized for a 1-page resume
- Download button for PDF version
- Print-friendly styling
- Modern gradient background
- Clean, readable typography

## Customization

### Changing Colors
Edit `styles.css` and modify these values:
- Background gradient: Line 13
- Primary color (headings): Lines 95, 170 (look for `#667eea`)
- Download button: Line 30

### Adding Your PDF
Simply place your resume PDF in this folder and name it `resume.pdf`, or update the link in `index.html` on line 14.

## File Structure

```
.
├── index.html      # Main HTML file with resume content
├── styles.css      # Styling and responsive design
├── resume.pdf      # Your PDF resume (add this)
└── README.md       # This file
```