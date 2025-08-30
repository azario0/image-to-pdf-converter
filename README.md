# Image to PDF Converter

A simple and intuitive desktop application built with Python and Tkinter to convert multiple images into a single, organized PDF document.


*(Feel free to replace this with your own screenshot of the running application!)*

## About The Project

This project provides a user-friendly graphical interface (GUI) for selecting, organizing, and converting image files into a PDF. It's designed for anyone who needs a quick and offline tool to compile photos, scans, or other images into a single document without relying on web services.

## Features

-   **Multi-File Selection**: Browse and select multiple images (`.jpg`, `.png`, `.gif`, etc.) at once.
-   **Image Preview**: See a preview of the currently selected image directly in the application.
-   **List Management**:
    -   Easily reorder images using "Move Up" and "Move Down" buttons to control their sequence in the final PDF.
    -   Remove unwanted images from the list.
-   **Page Orientation**: Choose between **Portrait** or **Landscape** layouts for your PDF pages.
-   **Fit to Page**: Images are automatically scaled to fit within the page dimensions while preserving their aspect ratio.
-   **Status Bar**: Get real-time feedback on the application's status, from selecting files to the conversion process.

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

You need to have Python 3 and `pip` installed on your system. You will also need two Python libraries: `Pillow` for image processing and `reportlab` for PDF generation.

-   Python 3.x
-   pip

### Installation

1.  **Clone the repository** (or download the source code):
    ```sh
    git clone https://github.com/azario0/image-to-pdf-converter.git
    ```

2.  **Navigate to the project directory**:
    ```sh
    cd image-to-pdf-converter
    ```

3.  **Install the required packages**:
    ```sh
    pip install Pillow reportlab
    ```
    *Alternatively, if a `requirements.txt` file is present:*
    ```sh
    pip install -r requirements.txt
    ```

### Usage

1.  **Run the application** from your terminal:
    ```sh
    python image_to_pdf_converter.py
    ```

2.  **Browse for Images**: Click the "Browse for Images" button to open a file dialog and select your image files.

3.  **Organize**:
    -   Click on a file in the list on the left to preview it on the right.
    -   Use the **▲ Up**, **▼ Down**, and **Remove** buttons to arrange the list in the desired order.

4.  **Set Options**:
    -   Use the "Orientation" dropdown to select either `Portrait` or `Landscape`.

5.  **Convert**:
    -   Click the "Convert to PDF" button.
    -   A "Save As" dialog will appear. Choose a location, enter a filename for your PDF, and click "Save".
    -   A success message will appear upon completion.

## Technologies Used

-   [Python](https://www.python.org/)
-   [Tkinter](https://docs.python.org/3/library/tkinter.html) - for the graphical user interface.
-   [Pillow](https://python-pillow.org/) - for image handling and manipulation.
-   [ReportLab](https://www.reportlab.com/opensource/) - for PDF creation.

## License

Distributed under the MIT License. See `LICENSE` file for more information.

## Contact

azario0 - [@azario0](https://github.com/azario0)

Project Link: [https://github.com/azario0/image-to-pdf-converter](https://github.com/azario0/image-to-pdf-converter)