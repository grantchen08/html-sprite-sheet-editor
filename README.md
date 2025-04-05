# HTML Sprite Sheet Editor

A simple, browser-based tool to create sprite sheets from individual image files using drag-and-drop.

![Screen Shot](demon.PNG)

## Description

This tool allows users to easily combine multiple images into a single sprite sheet directly within their web browser. It provides a visual grid where images can be imported, arranged, and then exported as a single PNG file. All processing is done client-side using HTML, CSS, and JavaScript; no server is required.

## Features

* **Configurable Grid:** Set the number of rows and columns for your sprite sheet layout.
* **Configurable Frame Size:** Define the width and height (in pixels) for each individual frame/sprite.
* **Multiple Image Import:** Import several image files at once from your computer.
* **Automatic Placement:** Imported images are automatically placed into the next available grid frames.
* **Drag & Drop:** Easily rearrange imported images by dragging and dropping them onto different frames within the grid.
* **Visual Grid:** A clear grid overlay helps visualize the frames.
* **Save as PNG:** Export the final sprite sheet as a single PNG image file.
* **Filename Prompt:** Specify your desired filename before saving.
* **Client-Side:** Runs entirely in the browser - no installation or server needed.

## How to Use

1.  **Get the Code:**
    * Clone this repository: `git clone <your-repo-url>`
    * OR Download the `index.html` file directly.
2.  **Open:** Open the `index.html` file in your preferred web browser (e.g., Chrome, Firefox, Edge).
3.  **Configure:**
    * Adjust the "Grid Columns" and "Grid Rows" to match your desired sprite sheet layout.
    * Set the "Frame Width" and "Frame Height" to the dimensions required for each sprite.
4.  **Import:** Click the "Import Images" button and select the image files you want to include in the sprite sheet.
5.  **Arrange:** Drag and drop the imported images within the grid canvas to arrange them as needed.
6.  **Save:**
    * Click the "Save Sprite Sheet" button.
    * Enter a filename when prompted (e.g., `my_sprites.png`).
    * The browser will download the generated PNG sprite sheet file.

## Technologies Used

* **HTML:** Structure of the web page.
* **CSS:** Styling (using Tailwind CSS via CDN).
* **JavaScript:** Core logic for image handling, canvas drawing, drag & drop, and saving.

## Contributing

Contributions are welcome! If you find a bug or have a feature request, please open an issue on GitHub. If you'd like to contribute code, please fork the repository and submit a pull request.

## License

This project is licensed under the BSD License - see the LICENSE file for details.
