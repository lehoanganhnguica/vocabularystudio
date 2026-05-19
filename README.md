# Vocab Studio

**Vocab Studio** is a lightweight browser-based vocabulary teaching tool for classroom use. It helps teachers import vocabulary lists and turn them into interactive teaching activities, including flashcards, quizzes, matching tasks, word scramble, and a “Save the Day” spelling game.

The app is free to use. You are welcome to open it online, share it with students or colleagues, embed it into your own website, or save it as an HTML file for local classroom use. Because it is built as a single HTML file, it can run directly in the browser without installation.

## Features

- Vocabulary library with word, IPA, simple meaning, Vietnamese cue, and example sentence
- Import from a Markdown vocabulary table
- Built-in prompt to generate vocabulary tables with ChatGPT or another AI assistant
- Flashcard mode for teacher-led vocabulary presentation
- Quiz mode for meaning, IPA, and sentence-context practice
- Matching game
- Word scramble game
- “Save the Day” spelling game
- Sound effects with an on/off toggle
- Browser-based local storage
- Works offline after saving the HTML file locally

## How to use locally

1. Download or copy `index.html`.
2. Double-click the file to open it in a browser.
3. Use **Library → Import / Paste** to add your vocabulary table.

Your vocabulary list is saved in the browser’s local storage. It stays on the same device and browser unless the browser data is cleared.

## How to deploy on GitHub Pages

1. Create a new GitHub repository, for example `vocab-studio`.
2. Upload these files to the root of the repository:
   - `index.html`
   - `README.md`
   - `.nojekyll`
   - `LICENSE`
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/root**
5. Save the settings.
6. Open the GitHub Pages link once deployment is complete.

Your public URL will usually look like this:

```text
https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPOSITORY-NAME/
```

Example:

```text
https://lehoanganhnguica.github.io/vocab-studio/
```

## Embed in another website

Paste this into an HTML/embed/custom-code block:

```html
<iframe
  src="https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPOSITORY-NAME/"
  width="100%"
  height="750"
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

## Notes

- This app does not require a server or database.
- Data is stored locally in each user’s browser.
- To back up vocabulary data, use the app’s export feature.
- To use the app offline, save `index.html` to your computer and open it in a browser.
