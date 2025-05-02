# Local Website Setup

This README explains how to run the website locally on your machine.

## Prerequisites

Before running the website, ensure you have the following installed:

- A modern web browser (e.g., Chrome, Firefox, Edge)
- A local web server (optional but recommended for some features like fetching JSON or using modules)

### Recommended: Use Live Server (for HTML/JS/CSS projects)

If you're using VS Code, you can install the **Live Server** extension:

1. Open VS Code.
2. Go to Extensions (`Ctrl+Shift+X`).
3. Search for **Live Server** and install it.
4. Right-click on your `index.html` file.
5. Click **"Open with Live Server"**.

The site will open in your default browser at `http://127.0.0.1:5500/` or similar.

---

## Alternative: Use Python HTTP Server

If you prefer not to use an editor plugin, you can run a simple HTTP server using Python.

### Using Python 3:

```bash
cd path/to/your/project
python -m http.server 8000
