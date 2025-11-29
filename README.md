# PDF-Compile
Image to PDF Converter
A powerful, browser-based application that converts multiple images into a single PDF file with intuitive controls and keyboard shortcuts.

## Features

- **Bulk Image Upload**: Upload hundreds of images at once (browser-dependent limit)
- **Smart Navigation**: Navigate through images with buttons, thumbnails, or keyboard shortcuts
- **Image Rotation**: Rotate images before adding to PDF (preserves rotation in final PDF)
- **Dynamic PDF Pages**: Each PDF page automatically matches the dimensions of its image
- **Keyboard-Driven Workflow**: Comprehensive keyboard shortcuts for efficient processing
- **Real-time Preview**: Visual feedback with thumbnails and status indicators
- **No Server Required**: All processing happens locally in your browser

## Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `←` / `→` | Previous/Next image (repeats when held) |
| `Home` / `End` | First/Last image |
| `Space` | Rotate right |
| `Shift + Space` | Rotate left |
| `Enter` | Add/Update image in PDF |
| `Delete` | Remove image from PDF |
| `Ctrl/Cmd + S` | Export PDF |

## How to Use

1. **Upload Images**: Click "Select Images" to choose your images (sorted by upload time)
2. **Navigate**: Use arrow keys or navigation buttons to browse through images
3. **Rotate**: Adjust image orientation with spacebar or rotation buttons
4. **Add to PDF**: Press Enter to include images in your PDF (marked with ✓)
5. **Export**: Use Ctrl/Cmd + S when ready to download your compiled PDF

## Technical Details

- **Frontend**: Pure HTML, CSS, and JavaScript (no frameworks required)
- **PDF Generation**: jsPDF library for client-side PDF creation
- **Image Processing**: Canvas API for rotation and dimension handling
- **File Handling**: FileReader API for local file processing
- **Responsive Design**: Works on desktop and mobile devices

## Benefits

- **Privacy**: Your images never leave your computer
- **Speed**: Keyboard shortcuts enable rapid processing of large image collections
- **Quality**: Each PDF page is optimized for its specific image dimensions
- **Flexibility**: Add, remove, or update images at any point in the process

## Browser Compatibility

Works in all modern browsers that support:
- FileReader API
- Canvas API
- ES6+ JavaScript features

## Installation

No installation required!

```bash
# For local development
python -m http.server 8000
# Then visit http://localhost:8000
