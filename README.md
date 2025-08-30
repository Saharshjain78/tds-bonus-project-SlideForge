
# 📊 Sli## ✨ Features

* 📝 **Flexible Input**: Support for plai## 🖥️ Usage

1. **## 🛠️ Architecture

* **Frontend Interface**:
  * Modern responsive design with intuitive user experience
  * Real-time progress indicators and user feedback
  * Local storage for session persistence and generation history
  * Cross-platform compatibility with modern web browsers

* **Backend Processing (FastAPI)**:
  * Secure API endpoints for content processing and file handling
  * Advanced text analysis and intelligent slide segmentation
  * Template parsing and style application algorithms
  * Integration with multiple AI providers through unified interface
  * Optimized PowerPoint generation using python-pptx librarytent**: Paste your text, markdown, or document content into the input area
2. **Customize Style** (Optional): Add specific guidance like *"Create a professional business presentation"* or *"Make it suitable for academic presentation"*
3. **Configure AI**: Enter your preferred AI service API key (OpenAI, Anthropic, or Google Gemini)
4. **Apply Template**: Upload your existing PowerPoint template (.pptx or .potx) to maintain brand consistency
5. **Generate**: Click the generate button to create your presentation
6. **Download**: Instantly download your professionally formatted PowerPoint file

The application intelligently analyzes your content and creates slides with appropriate titles, bullet points, and formatting based on your template. markdown, or structured documents
* 🎯 **Custom Guidance**: Provide specific instructions for presentation style and tone
* 🔑 **Multi-API Support**: Compatible with OpenAI, Anthropic, Google Gemini, and custom AI endpoints
* 🎨 **Template Integration**: Apply your existing PowerPoint templates for consistent branding
* 🖼️ **Smart Image Handling**: Automatically incorporates images from your template
* 📥 **One-Click Download**: Generate and download your presentation instantly
* ⚡ **Intelligent Parsing**: Advanced text segmentation for optimal slide distribution
* 🔒 **Privacy Focused**: All processing happens locally, no data storage or logging
* 🌐 **Web-Based**: No installation required, works in any modern browserAuto-Generate Presentations from Text

**Transform Your Text into Professional Slides – Convert any text or markdown into a polished PowerPoint presentation instantly.**

SlideForge is an intuitive web application that allows users to input lengthy text content (markdown, prose, notes, or reports) and automatically transform it into a well-styled, presentation-ready PowerPoint deck. Upload your custom template, provide optional styling instructions, and enter your preferred AI API key — the tool handles the conversion seamlessly.

---

## ✨ Features

* 📝 **Input Options**: Paste large chunks of text, markdown, or prose.
* 🎯 **Guidance**: Add a one-line instruction for tone or structure (e.g., “make it an investor pitch deck”).
* 🔑 **Bring Your Own API Key**: Supports OpenAI, Anthropic, Gemini, and more (keys are never stored or logged).
* 🎨 **Template Reuse**: Upload your `.pptx` or `.potx` template to apply colors, fonts, and layouts.
* 🖼️ **Image Reuse**: Recycles existing images from your uploaded template.
* 📥 **Instant Download**: Outputs a new `.pptx` file you can download directly.
* ⚡ **Smart Splitting**: Automatically divides your text into a reasonable number of slides.
* 🔒 **Privacy First**: No logging or saving of user text, keys, or files.

---

## 🚀 Quick Start

### 1. Clone the repo

```bash
git clone https://github.com/yourusername/slideforge-auto-ppt-generator.git
cd slideforge-auto-ppt-generator
```

### 2. Install dependencies

```bash
# Backend (Python FastAPI + pptx libraries)
pip install -r requirements.txt

# Frontend (served as static HTML/JS/CSS)
# no build step needed
```

### 3. Run locally

```bash
uvicorn app:app --reload
```

Visit: [http://localhost:8000](http://localhost:8000)

### 4. Deploy (Railway/Render/Vercel/Heroku)

This app works out-of-the-box on cloud platforms. Just connect your repo and deploy.

---

## 🖥️ Usage

1. Paste your text or markdown.
2. (Optional) Add a one-line guidance like *“make it a research summary”*.
3. Paste your LLM API key (OpenAI, Anthropic, Gemini).
4. Upload a `.pptx` or `.potx` template.
5. Click **Generate** → Get your styled PowerPoint deck!

---

## 🛠️ Architecture

* **Frontend**:

  * Responsive HTML + Tailwind UI
  * Handles text input, template upload, and file download
  * Provides toasts, progress feedback, and history of past generations

* **Backend (FastAPI)**:

  * Accepts text, guidance, API key, and template
  * Splits input intelligently into slide sections
  * Maps new content onto the uploaded template’s style, layout, fonts, and images
  * Generates `.pptx` output using `python-pptx`

---

## 🌟 Optional Enhancements

* Speaker notes generation for each slide
* Predefined style templates for different presentation types
* Real-time slide preview functionality
* Enhanced error handling and retry mechanisms
* Batch processing for multiple documents
* Custom slide layout suggestions
* Integration with cloud storage services
* Export to additional formats (PDF, Google Slides)
* Collaborative editing features
* Analytics and usage tracking

---

## 📄 License

MIT License – free to use, modify, and share.

