# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a minimal static HTML project (test repository). Currently contains a single `index.html` file.

## Development

To serve the static files locally:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (if installed)
npx serve
```

Then open http://localhost:8000 in a browser.

## Project Structure

```
├── index.html    # Main entry point
└── .gitignore    # Git ignore patterns
```

## Notes

- No build system or package manager is configured
- No testing framework is set up
- This repository is connected to GitHub remote: `git@github.com:seobakin/gitrepositoriodepruebas.git`
