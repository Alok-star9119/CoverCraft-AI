# 🚀 CoverCraft AI – Professional AI Cover Letter Generator

<div align="center">

![React](https://img.shields.io/badge/React-18-blue?logo=react)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow?logo=javascript)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3.x-38B2AC?logo=tailwind-css)
![Gemini AI](https://img.shields.io/badge/Google-Gemini%20AI-4285F4?logo=google)
![License](https://img.shields.io/badge/License-MIT-green)

### ✨ Generate ATS-Friendly, Recruiter-Ready Cover Letters in Seconds

</div>

---

## 📖 Overview

**CoverCraft AI** is an intelligent AI-powered cover letter generation platform that creates professional, recruiter-friendly, single-page cover letters tailored to any company or job role.

Instead of using generic templates, CoverCraft AI analyzes:

- 📄 Your Resume
- 💼 Job Role
- 🏢 Target Company
- 📝 Job Description
- 🛠 Technical Skills

and generates a concise, personalized cover letter optimized for **ATS systems**, recruiter readability, and A4 printing.

---

# ✨ Features

## 🤖 AI-Powered Cover Letter Generation

Generate personalized cover letters using **Google Gemini AI** based on:

- Resume content
- Job description
- Company name
- Target role
- Technical skills

---

## 📄 Resume Parsing

Supports:

- PDF Resume
- TXT Resume
- Markdown Resume

The application automatically extracts readable text using **PDF.js**.

Features:

- Drag & Drop upload
- Resume preview
- Word count
- Context extraction

---

## 🎯 ATS Optimized Output

Generated cover letters are:

- Recruiter friendly
- ATS compatible
- Professional formatting
- Single-page layout
- Quantified achievements
- Executive writing style

---

## 🖨️ A4 Print Optimization

The application automatically formats the generated letter for:

- Standard A4 paper
- 1-inch margins
- Professional typography
- Print-ready layout

Users can directly print from the browser.

---

## 📝 Live Markdown Editor

Every generated letter can be edited before downloading.

Features include:

- Markdown source view
- Live editing
- Instant preview
- Professional formatting

---

## 📂 Draft History

The application automatically stores generated cover letters inside Local Storage.

Features:

- Restore previous drafts
- Delete drafts
- Company-based history
- Last 10 generations stored

---

## 📋 Copy & Download

Users can:

- Copy cover letter
- Download as TXT
- Print instantly
- Edit before exporting

---

## 🔐 Secure API Key Handling

Supports two modes:

### Automatic Mode

Uses environment variables for Gemini API.

### Manual Mode

Users may optionally enter their own Gemini API Key.

Keys are stored locally in browser Local Storage.

---

## 🎨 Modern UI

Designed using

- Tailwind CSS
- Slate Color Theme
- Responsive Layout
- Animated Components

---

# 🖼 Application Workflow

```text
Upload Resume
        │
        ▼
PDF Parser
        │
        ▼
Extract Resume Context
        │
        ▼
Enter Company & Role
        │
        ▼
(Optional) Paste Job Description
        │
        ▼
Gemini AI Prompt Engineering
        │
        ▼
Generate Professional Cover Letter
        │
        ▼
Preview
Edit
Print
Download
```

---

# 🛠 Tech Stack

| Technology | Purpose |
|------------|----------|
| React 18 | UI Development |
| JavaScript (ES6) | Application Logic |
| Tailwind CSS | Styling |
| Google Gemini API | AI Generation |
| PDF.js | Resume Parsing |
| Local Storage | Draft Management |
| Babel Standalone | JSX Compilation |
| HTML5 | Structure |

---

# 📁 Project Structure

```
CoverCraft-AI/
│
├── index.html          # Complete application (HTML + CSS + JavaScript + React + JSX)
├── README.md
│
└── assets/             # (Optional) Screenshots and project images
    ├── home.png
    ├── upload.png
    ├── preview.png
    └── editor.png
```

> **Note:** This project is intentionally built as a **single-file application**. The entire frontend—including the HTML structure, Tailwind CSS configuration, React components, JSX logic, SVG icons, AI integration, PDF parsing, markdown rendering, and printing functionality—is contained within **`index.html`**. This makes the project lightweight, easy to deploy, and simple to share or host on any static web server.

# ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/CoverCraft-AI.git
```

Navigate to the project folder:

```bash
cd CoverCraft-AI
```

Using Python:

```bash
python -m http.server
```

Or using Node.js:

```bash
npx serve .
```

Open your browser and visit:

```
http://localhost:8000
```

No build process, package installation, or bundler is required.

# 🔑 Gemini API Setup

Option 1

Use your own Gemini API Key.

Store it inside:

```
REACT_APP_GEMINI_API_KEY
```

or manually enter it inside the application.

---

# 📷 Screenshots

screenshots/

home.png
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/a471932f-e9ff-4a4e-b83b-8a169fa69d29" />


upload.png
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/28fe1caa-1fee-4a36-901c-7878e00476be" />

preview.png
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/1de09673-56b8-4d2a-a8c7-42c1fcea2ad6" />


print.png
<img width="1358" height="688" alt="image" src="https://github.com/user-attachments/assets/063023c3-4a9b-4536-869a-52954ab417fd" />

```

---

# 📈 Key Functionalities

✅ Resume Upload

✅ PDF Parsing

✅ AI Content Generation

✅ ATS Optimized Writing

✅ Recruiter Friendly Layout

✅ Markdown Editing

✅ Print Preview

✅ Download

✅ Draft History

✅ Responsive Design

---

# 💡 Future Improvements

- DOCX Resume Parsing
- Multiple Cover Letter Templates
- Dark / Light Mode
- Export as PDF
- LinkedIn Profile Generator
- Resume Optimizer
- ATS Score Checker
- Multi-language Support
- AI Rewrite Suggestions
- Cover Letter Templates Library

---

# 🎯 Use Cases

Perfect for:

- Students
- Freshers
- Software Engineers
- AI Engineers
- Data Scientists
- ML Engineers
- Full Stack Developers
- Job Seekers
- Internship Applications

---

# 👨‍💻 Author

## Alok Kumar Mishra

AI & Machine Learning Enthusiast

- 🎓 B.Sc. (Hons.) Computer Science & Data Analytics — IIT Patna


### Skills

- Python
- Generative AI
- Machine Learning
- Deep Learning
- TypeScript
- RestAPI
- React
- Tailwind CSS

---

# 🤝 Contributing

Contributions are welcome.

Feel free to

- Fork the repository
- Create a feature branch
- Commit your changes
- Open a Pull Request

---

# ⭐ Support

If you found this project helpful, please consider giving it a ⭐ on GitHub.

It helps the project reach more developers and motivates future improvements.

---

# 📜 License

This project is licensed under the MIT License.

