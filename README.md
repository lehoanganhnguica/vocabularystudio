[README.md](https://github.com/user-attachments/files/28082468/README.md)
# Vocab Studio

Vocab Studio is a single-file classroom vocabulary teaching tool. It runs fully in the browser and stores vocabulary locally with `localStorage`.

## Features

- Vocabulary library import from Markdown tables
- Flashcards
- Quiz mode
- Matching game
- Word scramble
- "Save the Day" letter-guessing game
- English/Vietnamese interface switcher
- In-app HTML download for local offline use
- Offline-friendly single-page HTML app

## Deploy on GitHub Pages

1. Create a new GitHub repository.
2. Upload all files from this folder to the repository root.
3. In GitHub, open **Settings**.
4. Go to **Pages**.
5. Under **Build and deployment**, choose:
   - **Source:** Deploy from a branch
   - **Branch:** `main`
   - **Folder:** `/root`
6. Click **Save**.

GitHub will publish the app at:

```text
https://YOUR-USERNAME.github.io/YOUR-REPOSITORY-NAME/
```

## Local Use

Open `index.html` directly in a browser, or run a simple local server:

```bash
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Notes

- No build step is required.
- No external JavaScript or CSS dependencies are required.
- User vocabulary is stored in each browser's local storage.
