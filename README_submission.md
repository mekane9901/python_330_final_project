# Run backend:
uvicorn main:app --reload

# Open browser at http://127.0.0.1:8000

# Photo Journal App

- A FastAPI web application that lets users upload photos with text entries, view, edit, and delete them.
- Uses TinyDB for data storage and stores uploaded images in the `static/images` folder, validating and resizing images automatically.
- Supports dynamic updates with Jinja2 templates and HTMX for smooth user experience without full page reloads.
- To run, install dependencies (`fastapi`, `uvicorn`, `tinydb`, `jinja2-fragments`, `aiofiles`, `pillow`), run `uvicorn main:app --reload`, and open `http://localhost:8000` in a browser.