# Systems Learning Notes

A collection of self-contained interactive lessons, published with GitHub Pages.

- [Learning index](https://kvcash95.github.io/pages/)
- [Memory access inside a microVM](https://kvcash95.github.io/pages/microvm-memory/)

## Add a lesson

1. Create a folder with a descriptive lowercase, hyphenated name, e.g. `continuous-batching/`.
2. Put the lesson in that folder as `index.html`. Keep any assets inside the same folder and use relative URLs.
3. Add a link and description to the root `index.html`.
4. Commit and push to `main`.

Each lesson has its own stable URL. The root `index.html` is the collection's landing page.

## Publishing

In repository **Settings → Pages**, set **Source** to **Deploy from a branch**, then choose **main** and **/(root)**. An empty `.nojekyll` file tells Pages to serve these static files without Jekyll processing.

Open any lesson's `index.html` directly in a browser for offline use.
