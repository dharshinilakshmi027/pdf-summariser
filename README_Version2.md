# 📄 PDF Summarizer

A powerful, user-friendly web application that allows users to upload PDF documents and instantly generate intelligent summaries with key insights extracted using advanced text processing.

## ✨ Features

### Core Features
- 📤 **Easy PDF Upload** - Drag and drop or click to upload PDF files
- 🧠 **Smart Summarization** - Generate concise summaries in multiple lengths
- 🔑 **Key Points Extraction** - Automatically extract important points from documents
- 📋 **Document Metadata** - View document statistics (pages, word count, file size)
- 📥 **Download Summary** - Export your summary as a text file
- 📋 **Copy to Clipboard** - Quick copy functionality for summaries
- 🎨 **Beautiful UI** - Modern, intuitive interface with smooth animations
- ⚡ **Fast Processing** - Instant PDF text extraction and processing
- 📱 **Responsive Design** - Works perfectly on desktop, tablet, and mobile devices

## 🚀 How to Use

### Step 1: Upload Your PDF
Click the **"Choose PDF File"** button and select a PDF document from your device.

### Step 2: Analyze the Document
Click **"Analyze PDF"** to process and extract text from your document.

### Step 3: Configure Summarization Options
- **Choose Summary Length:**
  - 📝 Short (3-5 sentences) - Quick overview
  - 📄 Medium (5-10 sentences) - Balanced summary (default)
  - 📚 Long (10-15 sentences) - Comprehensive summary

- **Select Options:**
  - ✅ Extract Key Points - Get bullet-point summaries
  - ✅ Extract Metadata - View document information

### Step 4: Generate Summary
Click **"Generate Summary"** to create your personalized summary.

### Step 5: Download or Share
- 📥 **Download Summary** - Save as `.txt` file
- 📋 **Copy to Clipboard** - Copy to paste anywhere
- ➕ **Process New PDF** - Upload another document

## 🛠️ Technologies Used

| Technology | Purpose |
|-----------|---------|
| **HTML5** | Document Structure |
| **CSS3** | Responsive Design & Styling |
| **JavaScript (ES6)** | Application Logic & Interactivity |
| **PDF.js Library** | PDF Processing & Text Extraction |

## 📥 Installation

### Option 1: GitHub Pages (Recommended - Live Demo)
The website is already live at:
```
https://dharshinilakshmi027.github.io/pdf-summariser/
```

### Option 2: Local Setup

1. **Clone the repository:**
```bash
git clone https://github.com/dharshinilakshmi027/pdf-summariser.git
cd pdf-summariser
```

2. **Open in browser:**
   - Simply open `index.html` in your web browser
   - No server or dependencies required!

## 📁 Project Structure

```
pdf-summariser/
├── index.html          # Main HTML structure
├── styles.css          # CSS styling and responsive design
├── app.js              # JavaScript application logic
├── README.md           # Project documentation
└── .gitignore          # Git ignore file
```

## 💡 How It Works

### PDF Processing
1. User uploads a PDF file
2. PDF.js library extracts text from all pages
3. Metadata is calculated (pages, words, file size)
4. Full text is displayed in results

### Summarization Algorithm
1. Text is split into sentences
2. Top sentences are selected based on length preference
3. Key points are extracted from first few sentences
4. Summary is displayed with optional metadata

### File Export
- Summary is formatted with document info
- Downloaded as `.txt` file with timestamp
- Can be easily imported to other applications

## 🌐 Browser Compatibility

| Browser | Support |
|---------|---------|
| Chrome/Chromium | ✅ Full Support |
| Firefox | ✅ Full Support |
| Safari | ✅ Full Support |
| Edge | ✅ Full Support |
| Opera | ✅ Full Support |
| IE 11 | ❌ Not Supported |

## 🎨 Design Features

### User Interface
- 🎯 **Intuitive Navigation** - Clear flow from upload to download
- 🌈 **Beautiful Gradient** - Modern purple gradient background
- 🔘 **Interactive Buttons** - Smooth hover effects and transitions
- 📊 **Card-Based Layout** - Organized information presentation
- ⚙️ **Loading Indicators** - Animated spinner during processing
- 🎬 **Smooth Animations** - Polished user experience

### Accessibility
- 📱 Mobile-first responsive design
- ♿ Semantic HTML structure
- 🔍 Clear labels and instructions
- 🎨 High contrast color scheme
- ⌨️ Keyboard navigation support

## 📊 Supported PDF Types

- ✅ Text-based PDFs
- ✅ Scanned documents (with searchable text layer)
- ⚠️ Image-only PDFs (limited text extraction)
- ✅ Multi-page documents
- ✅ Documents with mixed content

## ⚡ Performance

- **PDF Upload**: Instant
- **Text Extraction**: 1-3 seconds (depending on file size)
- **Summary Generation**: 2 seconds (simulated processing)
- **File Download**: Instant
- **Browser Compatibility**: Works offline

## 🔒 Privacy & Security

- ✅ **No Server Storage** - Files processed locally in browser
- ✅ **No Data Collection** - Your PDFs are never uploaded to servers
- ✅ **No Tracking** - Complete privacy respected
- ✅ **Secure Processing** - All operations happen client-side

## 🚀 Future Enhancements

### Planned Features
- [ ] 🤖 AI API Integration (OpenAI, Google Cloud NLP)
- [ ] 🌍 Multi-language support
- [ ] 📦 Batch PDF processing
- [ ] 💾 Cloud storage integration
- [ ] 📊 Export to PDF/Word/Excel formats
- [ ] 🎯 OCR for scanned documents
- [ ] 🔐 Password-protected PDFs
- [ ] 📈 Advanced analytics and insights
- [ ] 🎨 Customizable themes
- [ ] 🔖 Bookmark important sections

## 🐛 Known Limitations

- Text extraction depends on PDF structure
- Complex layouts may affect accuracy
- Very large files (>50MB) may process slowly
- Scanned PDFs without OCR won't extract text

## 💬 Troubleshooting

### PDF Not Processing
- Ensure file is in valid PDF format
- Try with a different PDF file
- Check browser console for errors (F12)

### Text Not Extracting
- Verify PDF contains searchable text
- Scanned images may not extract well
- Try uploading a text-based PDF

### Summary Not Generating
- Ensure PDF has sufficient text content
- Try a different summary length
- Refresh page and try again

## 🤝 Contributing

Contributions are welcome! Here's how to help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the **MIT License** - see the LICENSE file for details.

You are free to:
- ✅ Use commercially and privately
- ✅ Modify and distribute
- ✅ Include in your projects
- ✅ Sublicense

## 👤 Author

**Dharshini Lakshmi**
- GitHub: [@dharshinilakshmi027](https://github.com/dharshinilakshmi027)
- Email: dharshinilakshmi027@gmail.com

## 🙏 Acknowledgments

- **PDF.js** - Mozilla's PDF processing library
- **Inspired by** - Modern web development best practices
- **Thanks to** - All users and contributors

## 📞 Support & Feedback

Have questions or suggestions?
- 📧 Open an [Issue](https://github.com/dharshinilakshmi027/pdf-summariser/issues)
- 💬 Start a [Discussion](https://github.com/dharshinilakshmi027/pdf-summariser/discussions)
- 🌟 Star the repository if you find it helpful!

## 🎯 Roadmap

### Version 1.0 (Current)
- ✅ Basic PDF upload and text extraction
- ✅ Summarization in multiple lengths
- ✅ Key points extraction
- ✅ Responsive design

### Version 1.1 (Coming Soon)
- 📌 Dark mode theme
- 📌 Advanced customization options
- 📌 Recent files history

### Version 2.0 (Future)
- 🔮 AI-powered summaries
- 🔮 Multi-language support
- 🔮 Cloud storage integration

---

## ⭐ If You Find This Useful

Please consider giving this project a **star** ⭐ on GitHub!

It helps the project gain visibility and encourages further development.

---

**Created with ❤️ by Dharshini Lakshmi**

**Happy Summarizing!** 📚✨

*Last Updated: June 2026*