---
description: Regenerate index.html (Document Center) from the .html/.md/.pdf files in this folder
allowed-tools: Bash(node build-index.mjs)
---

Run `node build-index.mjs` in the project root to regenerate `index.html`.

Then report only: the file list and order the script printed, and any file that has no `<meta name="description">` / first paragraph (its card will have no description). Do not commit.
