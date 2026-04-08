# Advanced Pro Calculator

This project is an advanced scientific calculator built with HTML/CSS/JS frontend and a Python Flask backend.

## Features
- **Scientific Functions**: `sin`, `cos`, `tan`, `log`, `ln`, `sqrt`, `factorial`, `pi`, `e`.
- **Backend Calculation**: Uses Python's `math` library for precise and safe evaluation.
- **Modern UI**: Glassmorphism design with responsive layout.

## Setup & Run

1.  **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

2.  **Run Server**:
    ```bash
    python app.py
    ```

3.  **Open Calculator**:
    Open `index.html` in your browser.

## Backend APIs
-   `POST /calculate`: Accepts JSON `{ "expression": "..." }` and returns `{ "result": <number> }`.
