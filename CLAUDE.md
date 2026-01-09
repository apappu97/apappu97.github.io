# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static personal website (aneeshpappu.com) hosted on GitHub Pages. There is no build system, package manager, or test suite.

## Development

To preview locally, open `index.html` in a browser or use any static file server:
```bash
python3 -m http.server 8000
```

To deploy, push to the `master` branch. GitHub Pages automatically serves the site.

## Architecture

- `index.html` - Single-page site with About, News, and Publications sections
- `css/style.css` - Custom stylesheet (Cormorant Garamond + Work Sans fonts, warm earth tones)
- `img/headshot.png` - Professional headshot
- `CNAME` - Custom domain configuration (aneeshpappu.com)

## Site Sections

1. **Header** - Name, tagline ("AI Research & Policy"), navigation
2. **About** - Bio with headshot, social links (LinkedIn, Twitter, Google Scholar)
3. **News** - Timestamped updates
4. **Publications** - Technical and Policy subsections
5. **Footer** - Social icons, copyright
