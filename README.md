# Polaroid Layout Maker

A private, client-side web tool to frame and arrange your digital photos into classic Polaroid-style layouts, either as single prints or charming pairs.

## 1. Features

*   **Easy Image Input:** Drag and drop images directly onto the page or use the file dialog to upload multiple photos.
*   **Authentic Framing:** Automatically frames your images in an authentic Polaroid style.
*   **Flexible Layouts:** Choose between "2R" (two images side-by-side) or "3R" (individual images) for your final export.
*   **Intuitive Image Manipulation:**
    *   **Pan & Zoom:** Precisely position and zoom your images within the frame using mouse drag/scroll or touch gestures.
    *   **Rotation:** Rotate images by 90-degree increments.
    *   **Frame Toggle:** Switch between a classic framed look and a frameless, full-bleed style.
    *   **Orientation Toggle:** Adjust the frame orientation between portrait and landscape.
*   **Client-Side & Private:** All image processing occurs directly in your browser, ensuring your photos remain private.
*   **Efficient Export:** Utilizes Web Workers and `OffscreenCanvas` for smooth, non-blocking image processing during export.
*   **Customizable Export:** Save your creations as high-quality JPEG (with adjustable quality) or PNG files.
*   **Direct Folder Saving:** Supports the File System Access API (in compatible browsers) for direct saving to a local "polaroid" folder.
*   **Dark Mode:** A toggle for a comfortable viewing experience.

## 2. How to Use

1.  **Add Images:** Drag and drop your photos into the designated area or click the "📂" button to select files.
2.  **Adjust Layouts:** Each uploaded image will appear in its own interactive Polaroid frame.
    *   **Pan & Zoom:** Click/drag to pan, use the zoom slider below each frame, or use touch gestures (single finger drag, two-finger pinch).
    *   **Controls:** Use the buttons below each frame to `🗑️ Remove`, `🖼️ Toggle Frame`, `↔️/↕️ Toggle Orientation`, `🔄 Rotate Image`, or `🔍 Reset Zoom`.
3.  **Select Export Options:** In the main toolbar at the top:
    *   Choose your desired **Layout Mode** (`2R` for pairs, `3R` for individuals).
    *   Select the **Save Format** (JPG or PNG).
    *   If JPG is selected, adjust the **JPEG Quality**.
4.  **Save All:** Click the "📥" button to process and download all your Polaroid layouts.

## 3. Local Development

To run this project locally, simply open the `index.html` file in your web browser. No server or build tools are required.

## 4. License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Credits

Copyright (c) 2025 aisptn