# 📊 SlideForge – Auto-Generate Presentations from Text

**Transform Your Text into Professional Slides – Convert any text or markdown into a polished PowerPoint presentation instantly.**

SlideForge is an intuitive web application that allows users to input lengthy text content (markdown, prose, notes, or reports) and automatically transform it into a well-styled, presentation-ready PowerPoint file.

---

## ✨ Features

* 📝 **Flexible Input**: Paste large chunks of text, markdown, or prose.
* 🎯 **Custom Guidance**: Provide specific instructions for presentation style and tone (e.g., “make it an investor pitch deck”).
* 🔑 **Multi-API Support**: Compatible with OpenAI, Anthropic, Google Gemini, and custom AI endpoints (keys are never stored or logged).
* 🎨 **Template Integration**: Apply your existing PowerPoint templates (`.pptx` or `.potx`) for consistent branding—colors, fonts, layouts.
* 🖼️ **Smart Image Handling**: Automatically recycles images from your uploaded template.
* 📥 **One-Click Download**: Generate and download your presentation instantly as a new `.pptx` file.
* ⚡ **Intelligent Parsing**: Advanced text segmentation for optimal slide distribution.
* 🔒 **Privacy Focused**: No data storage or logging; all processing happens locally.
* 🌐 **Web-Based**: No installation required; works in any modern browser.

---

## 🚀 Quick Start

### 1. Clone the repo

```bash
git clone https://github.com/Saharshjain78/tds-bonus-project-SlideForge.git
cd tds-bonus-project-SlideForge
```

### 2. Install dependencies

```bash
# Backend (Python FastAPI + pptx libraries)
pip install -r requirements.txt

# Frontend (served as static HTML/JS/CSS)
# No build step needed
```

### 3. Run locally

```bash
uvicorn app:app --reload
```

Visit: [http://localhost:8000](http://localhost:8000)

### 4. Deploy (Railway/Render/Vercel/Heroku)

This app works out-of-the-box on many cloud platforms. Just connect your repo and deploy.

---

## 🖥️ Usage

1. **Paste Content**: Paste your text, markdown, or document content into the input area.
2. **Customize Style** (Optional): Add a one-line guidance like _“Create a professional business presentation”_ or _“Make it suitable for academic presentation”_.
3. **Configure AI**: Enter your preferred AI service API key (OpenAI, Anthropic, or Google Gemini).
4. **Apply Template**: Upload your existing PowerPoint template (`.pptx` or `.potx`) to maintain brand consistency.
5. **Generate**: Click the **Generate** button to create your presentation.
6. **Download**: Instantly download your professionally formatted PowerPoint file.

The application intelligently analyzes your content and creates slides with appropriate titles, bullet points, and formatting based on your template.

---

## 🛠️ Architecture

* **Frontend**:
  * Modern, responsive design with an intuitive user experience
  * Handles text input, template upload, and file download
  * Real-time progress indicators, user feedback, toasts, and history of past generations
  * Local storage for session persistence and generation history
  * Cross-platform compatibility with modern web browsers

* **Backend (FastAPI)**:
  * Secure API endpoints for content processing and file handling
  * Advanced text analysis and intelligent slide segmentation
  * Maps new content onto the uploaded template’s style, layout, fonts, and images
  * Integration with multiple AI providers through a unified interface
  * Optimized PowerPoint generation using `python-pptx`

---

## 📄 License

MIT License – free to use, modify, and share.
