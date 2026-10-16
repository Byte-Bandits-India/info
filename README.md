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
| **3** | 🎁 Coral Rose Gradient | **Company Brochure**<br>_Ramadan Offers & Brochure_ | Opens [brochure.pdf](file:///Users/abc/Desktop/Byte-Bandits/project_new/info/documents/brochure.pdf) in modal preview with download button |
| **4** | 💜 Violet Purple Gradient | **Presentating Xylozen**<br>_How do we are work_ | Opens [Xylozen Technologies.pdf](file:///Users/abc/Desktop/Byte-Bandits/project_new/info/documents/Xylozen%20Technologies.pdf) in modal preview with download button |
| **5** | 🌿 Turquoise Teal Gradient | **Contact - Us**<br>_Need Help? Chat with us_ | Routes to [https://xylozentech.com/contact](https://xylozentech.com/contact) |

---

## 📄 PDF Viewing & Download Modal

The cards link directly to your documents:
- Card 3: `documents/brochure.pdf`
- Card 4: `documents/Xylozen%20Technologies.pdf`

Clicking either card opens a clean, responsive **modal screen**:
- **Inline PDF Preview**: Embedded document viewer with zoom and page controls.
- **Direct Download Button**: Prominent download button to save the document immediately.
- **External View**: Option to pop out and view the document in a full browser tab.
- **Light Dismiss**: Dismiss by clicking outside the backdrop, pressing <kbd>Esc</kbd>, or clicking the close button.

---

## 💻 How to View Locally

You can simply double-click [index.html](file:///Users/abc/Desktop/Byte-Bandits/project_new/info/index.html) in your file manager, or run a local server:

```bash
python3 -m http.server 8085
```
Then open `http://localhost:8085` in your browser.
