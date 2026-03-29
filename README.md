# 📝 Doc Tools — Fast Word Compression

A lightweight Streamlit app for compressing Word (`.docx`) documents efficiently without external uploads.

Built for real-world use cases like form uploads, file size limits, and document optimization.

---

## ⚡ Features

### 📄 Word Compressor

* Reduce `.docx` size by **50–90%**
* Image recompression (JPEG conversion + resizing)
* Grayscale option for extra reduction
* Removes unnecessary metadata and bloat
* XML cleanup for additional savings

---

## 🧠 How it Works

* Extracts `.docx` (ZIP structure)
* Compresses images inside `/word/media`
* Removes unnecessary files (thumbnails, metadata)
* Rebuilds document with maximum compression

---

## 📦 Installation

```bash
git clone https://github.com/dipenduadhikari13-byte/Doc-Tools.git
cd Doc-Tools
pip install -r requirements.txt
```

---

## ▶️ Run

```bash
streamlit run app.py
```

---

## ☁️ Deployment

* No system dependencies required
* Works directly on Streamlit Community Cloud

---

## 📁 Project Structure

```Doc-Tools
word_compressor.py
```

---

## ⚠️ Notes

* Large documents (>50MB) may be slow on cloud
* High compression reduces image quality
* Best for upload-limited environments (forms, portals)

---

## 🚀 Future Improvements

* Batch document compression
* Drag & drop multiple files
* PDF ↔ DOCX conversion
* CLI support

---

## 📜 License

MIT License
