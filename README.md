
# OCR Python Application

This Flask application allows users to upload an image, perform Optical Character Recognition (OCR) on the image using Tesseract, and view the extracted text along with the uploaded image.

## Features

1. **Upload and Recognize:**
   - Users can upload an image file.
   - The application performs OCR on the uploaded image.

2. **Result Display:**
   - Displays the extracted text in the result page.
   - Shows the uploaded image alongside the extracted text.

3. **Navigation:**
   - Provides a back button to return to the home page.

## Prerequisites

1. Ensure you have Python installed on your system.

2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
3.  Download and install Tesseract OCR: [Tesseract OCR](https://github.com/tesseract-ocr/tesseract).

## Instructions for Running

1.  Clone this repository:
    
    ```bash
    git clone https://github.com/your-username/ocr-flask-app.git
    cd ocr-flask-app
    
2.  Update the Tesseract path:
    
    -   Open `app.py` and update the `tesseract_cmd` variable with the path to your Tesseract executable.
3.  Run the Flask application:
    
    `python app.py` 
    
4.  Open your web browser and go to `[http://127.0.0.1:5000/](local host)` to access the OCR application.
    

## Usage

1.  **Home Page (`/`):**
    
    -   Upload an image using the provided form.
2.  **Result Page (`/result`):**
    
    -   View the extracted text alongside the uploaded image.
    -   Use the back button to return to the home page.

## Contributors

-   Sachin Kumar Singh

Feel free to explore, contribute, and enhance this OCR Flask application!
