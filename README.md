# Vocab Studio

**Vocab Studio** is a browser-based classroom vocabulary teaching tool. It helps teachers import vocabulary tables and turn them into interactive classroom activities, including flashcards, quizzes, matching tasks, word scramble practice, and the **Save the Day** guessing game.

The app is designed as a single-file HTML application. It can be hosted on GitHub Pages, embedded into another website, or saved locally and opened directly in a browser.

## Features

- Import vocabulary from a Markdown table
- Built-in prompt for generating vocabulary tables with ChatGPT or other AI tools
- Flashcard teaching mode
- Multiple-choice quiz mode
- Word–meaning matching game
- Word scramble game
- Save the Day guessing game with animated scenes and sound effects
- Browser-based local storage for saved word lists
- Works offline after saving the HTML file locally

## Deploy on GitHub Pages

1. Create a new GitHub repository.
2. Upload the files in this package to the repository root:
   - `index.html`
   - `README.md`
   - `.nojekyll`
   - `LICENSE`
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose:
   - **Source:** Deploy from a branch
   - **Branch:** `main`
   - **Folder:** `/root`
5. Click **Save**.
6. Your app will be available at:

```text
https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPOSITORY-NAME/
```

## Embed in another website

After deploying the app, copy your GitHub Pages URL and use it inside an iframe:

```html
<iframe
  src="https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPOSITORY-NAME/"
  width="100%"
  height="800"
  style="border:0;"
  allow="clipboard-read; clipboard-write">
</iframe>
```

For a full-page embed:

```html
<iframe
  src="https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPOSITORY-NAME/"
  style="width:100%; height:100vh; border:0;"
  allow="clipboard-read; clipboard-write">
</iframe>
```

## Local use

You can also use the app without GitHub:

1. Open `index.html` directly in Chrome, Edge, Safari, or Firefox.
2. Import or create your vocabulary list.
3. Your word list will be saved in that browser's local storage.

For backup, use the app's **Export** button and save the JSON file.

## Notes

- Word lists are stored in the browser's local storage. They stay on the same device and browser unless exported.
- The app does not require a backend server.
- Audio starts only after the first click or keypress because most browsers block sound before user interaction.
