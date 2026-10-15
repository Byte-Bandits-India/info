# Xylozen Tech - Quick Portal UI

A modern, responsive link portal built with **HTML5** and **Tailwind CSS v3**, faithfully recreating the gradient card interface with smooth organic wave artwork and interactive PDF viewing.

## 🚀 Live Demo & Structure

- [index.html](file:///Users/abc/Desktop/Byte-Bandits/project_new/info/index.html) - Main responsive portal page.
- [documents/](file:///Users/abc/Desktop/Byte-Bandits/project_new/info/documents/) - Directory containing the PDF files for viewing and downloading.
  - [brochure.pdf](file:///Users/abc/Desktop/Byte-Bandits/project_new/info/documents/brochure.pdf) - Offers & Brochure PDF (Card 3).
  - [Xylozen Technologies.pdf](file:///Users/abc/Desktop/Byte-Bandits/project_new/info/documents/Xylozen%20Technologies.pdf) - Loyalty & Xylozen Technologies PDF (Card 4).

---

## 📋 Navigation Cards Mapping

| # | Card Theme & Gradient | Title & Subtitle | Destination / Action |
|---|----------------------|------------------|----------------------|
| **1** | 🌊 Sky Blue Gradient | **Dashboard**<br>_Employee Contract Details_ | Routes to [https://xylozentech.com](https://xylozentech.com) |
| **2** | 🌅 Golden Orange Gradient | **Online Services**<br>_All Online Services Here_ | Routes to [https://xylozentech.com/services](https://xylozentech.com/services) |
| **3** | 🎁 Coral Rose Gradient | **Offers**<br>_Ramadan Offers_ | Opens [brochure.pdf](file:///Users/abc/Desktop/Byte-Bandits/project_new/info/documents/brochure.pdf) directly in a new tab |
| **4** | 💜 Violet Purple Gradient | **Loyalty**<br>_How do we are work_ | Opens [Xylozen Technologies.pdf](file:///Users/abc/Desktop/Byte-Bandits/project_new/info/documents/Xylozen%20Technologies.pdf) directly in a new tab |
| **5** | 🌿 Turquoise Teal Gradient | **Contact - Us**<br>_Need Help? Chat with us_ | Routes to [https://xylozentech.com/contact](https://xylozentech.com/contact) |

---

## 📄 PDF Linking

The cards link directly to your documents:
- Card 3: `documents/brochure.pdf`
- Card 4: `documents/Xylozen%20Technologies.pdf`
Opening in a new tab triggers the browser's native full-featured PDF viewer with built-in preview, zoom, search, print, and download capabilities.

---

## 💻 How to View Locally

You can simply double-click [index.html](file:///Users/abc/Desktop/Byte-Bandits/project_new/info/index.html) in your file manager, or run a local server:

```bash
python3 -m http.server 8085
```
Then open `http://localhost:8085` in your browser.
