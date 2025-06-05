# 🕵️ Plagiarism Checker (Text and Image)

A powerful plagiarism detection system that checks for duplicate content in both text and image formats. The application uses Python's Flask framework for the backend and integrates image/text comparison logic along with optional Google Search API-based detection.

## 🚀 Features

- 🔍 **Text Plagiarism Detection**
  - Detects duplicate content using string matching and search engine validation.
  
- 🖼️ **Image Plagiarism Detection**
  - Uses perceptual hashing and pixel-level comparison to check for copied images.
  
- 🌐 **Google Search Integration**
  - Enhances accuracy by validating text snippets across the web.

- 📊 **User-Friendly Web Interface**
  - Simple UI for uploading files and viewing results.

---

## 🛠️ Tech Stack

- **Backend**: Flask (Python)
- **Frontend**: HTML5, CSS3, Bootstrap
- **Libraries**: 
  - `Pillow` for image processing
  - `difflib` or `SequenceMatcher` for text comparison
  - `requests`, `bs4` for web scraping (optional)
  - `imagehash` or `OpenCV` for image similarity

---



## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Plagiarism-Checker-Text-and-Image.git
cd Plagiarism-Checker-Text-and-Image
