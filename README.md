🎯 **Fix messed up Persian subtitles for editing in CapCut and other non-Persian-friendly editors.**  
This project reshapes Persian subtitles in `.srt` format to display correctly using appropriate character forms (Isolated, Initial, Medial, Final) and fixes RTL issues for use in CapCut or similar video editing apps.

---

## 🚀 Features

- 📝 Upload and reshape `.srt` subtitle files
- 🔠 Converts disconnected Persian characters into correct visual forms
- 🔢 Reverses Arabic-Indic numbers (١٢٣...) when needed
- 💻 Handles English, timestamps, numbers, and punctuation correctly
- 📥 Download the reshaped subtitle in one click
- 🧹 Clear fields and copy text with a single button

---

## 🌐 Live Demo

You can run the app locally by simply opening the `index.html` file in your browser.  
No need for backend or server — it's 100% client-side and privacy-friendly.

---

## 📂 How to Use

1. Open `index.html` in your browser
2. Click **"انتخاب فایل"** and upload your `.srt` file containing Persian subtitles
3. Review or edit the content in the first text box (optional)
4. Click **"اصلاح و دانلود"** to fix and download the reshaped subtitle
5. Optionally, copy the output text to clipboard or clear the inputs

---

## 💡 Why This Exists

CapCut and many other international editors do not support Persian script rendering correctly.  
They display disconnected characters that are hard to read. This tool reshapes the text to use appropriate glyph forms from the Arabic Presentation Forms Unicode blocks, ensuring accurate display.

---

## 🛠 Developer Notes

The reshaping logic is handled via pure JavaScript, using Unicode mappings for:
- Isolated, Initial, Medial, Final forms
- Arabic and Persian characters
- Arabic-Indic digits

Subtitles with timestamps and English text are left unchanged.

Feel free to improve, add enhancements (like drag-and-drop, batch files), or internationalize the interface.

---

## 🙌 Contributions Welcome

Pull requests, issues, and forks are welcome! If you find a bug or want to add a feature, don’t hesitate to contribute.

---

## 🔗 Credits

Made with ❤️ by Saeedeshon
Inspired by subtitle formatting issues in Persian video production.
