<details>
<summary>English</summary>
  
[日本語](/README.md)
  
</details>


# PDFdiff

An online difference checker that can be run locally using JavaScript.

PDFdiff is a simple yet powerful tool for visually comparing two PDF files in your browser.

You can overlay the old and new files and use a slider to see the differences.

## Main Features

- **Visual Comparison**: Overlays two PDFs and displays differences in different colors.

- <span style="color: #ff6666;">■</span> **Red**: Before deletion/modification

- <span style="color: #6666ff;">■</span> **Blue**: After addition/modification

- <span style="color: #cc66ff;">■</span> **Purple**: Common parts

- **Slider Mode**: Intuitively switch between old and new files by moving the slider left or right for comparison.

- **Multi-Page Support**: Allows you to compare multiple pages of a PDF by flipping through the pages.

- **Fullscreen Display**: View details in a larger screen.

- **Privacy**: All processing is done in the browser; no files are uploaded to the server.

## How to Use

1. Open `index.html` in your browser.

2. Upload the PDF files you want to compare to the "Source (Old)" and "Target (New)" fields on the screen.

3. Select the comparison mode (overlay or slider) from the "Options" tab.

4. Navigate pages using the "Previous" and "Next" buttons, or the arrow keys (←/→) on your keyboard, to view the results.

## Technology Stack

- [PDF.js](https://mozilla.github.io/pdf.js/) - Used for PDF rendering
- HTML5 / CSS3 / JavaScript (Vanilla JS)

---
© 2026 htvoffcial
