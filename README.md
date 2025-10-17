# Hello Space

A tiny, single-file HTML web application that greets the cosmos: "Hello Space". Built with Tailwind CSS (CDN) and designed to be beautiful, fully responsive, accessible, and production-ready — all in one file.

## Features

- Single-file HTML app (index.html) — no build tools required
- Uses Tailwind CSS via CDN for modern styling
- Responsive, mobile-first design
- Accessible controls and keyboard shortcuts
- Light/Dark theme toggle with persistence (localStorage)
- Subtle animated starfield background (respects reduced-motion preference)
- Share support (Web Share API) with a clipboard fallback
- Copy greeting button and small toast notifications
- Clean, modern UI suitable as a tiny landing or demo page

## Usage

1. Clone or download the project files.
2. Open `index.html` in any modern browser.

The page is fully static — you can host it on any static hosting provider (GitHub Pages, Netlify, Vercel, etc.).

### Controls & Shortcuts

- Click "Copy Greeting" to copy "Hello Space" to your clipboard.
- Click the theme button (sun/moon) or press `T` to toggle between light and dark themes.
- Press `C` to copy the greeting using your keyboard.
- Click "Share" to open the native share dialog on supported devices; falls back to copying the URL.

### Accessibility

- Keyboard accessible controls
- Focus outlines visible for keyboard users
- Animations respect `prefers-reduced-motion`
- Semantic markup and ARIA attributes for assistive tech

## Files

- `index.html` — the complete single-file app
- `README.md` — this document
- `LICENSE` — MIT license

## Customization

You can easily customize colors or copy text by editing `index.html`. Tailwind's CDN config is embedded at the top of the file to make small theming changes without a build step.

## License

This project is released under the MIT License. See the LICENSE file for details.
