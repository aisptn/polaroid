
# Polaroid Maker

A minimal, private, client-side tool for framing and laying out images in Polaroid style pairs or singles.

## Features

- **Drag & Drop Interface**: Simply drag images onto the canvas to add them
- **Frameless & Framed Modes**: Toggle between Polaroid-style frames and frameless layouts
- **Image Editing**: Zoom, pan, and rotate images within their frames
- **Multiple Export Formats**: Save as PNG or JPEG with adjustable quality settings
- **Batch Export**: Export multiple images at once with automatic timestamped naming
- **Dark Mode**: Toggle between light and dark themes (legacy version)
- **Keyboard Shortcuts**: Quick actions for rotation, zoom, and frame toggling
- **100% Private**: All processing happens in your browser—no data is sent to servers

## Usage

1. Open the application in your web browser
2. Drag and drop images onto the canvas to add them
3. Use controls to adjust zoom, pan, and position each image
4. Rotate images using keyboard shortcuts or controls
5. Toggle frames on/off as desired
6. Select export format and quality
7. Click "Save All" to download your images

## Keyboard Shortcuts

- `Delete` / `R` - Remove image
- `F` - Toggle frame
- `0`/`9`/`1`/`2` - Rotate 0°/90°/180°/270°
- `P`/`L` - Switch to portrait/landscape
- `+`/`-` - Zoom in/out
- `N`/`V` - Fit contain/cover mode

## Technical Stack

- **HTML5 Canvas API** for image rendering
- **Web Workers** for off-thread image processing
- **Drag & Drop API** for file handling
- **CSS Grid/Flexbox** for responsive layouts

## Browser Support

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+

## License

MIT License © 2025 aisptn