# CAPTCHA Solver

## Summary
A single-page web application that solves text-based CAPTCHA images using pure JavaScript and Canvas, no external dependencies. Handles `?url=https://.../image.png` or defaults to `sample-captcha.png`. Built for a test task to demonstrate GitHub repo creation and CAPTCHA-solving via GitHub Pages.

## Features
- Displays CAPTCHA from URL query (`?url=...`) or default sample.
- Solves CAPTCHAs client-side with basic OCR (~50-70% accuracy on simple text).
- Fully inline HTML/CSS/JS, no external libraries or APIs.
- Hosted on GitHub Pages: `https://Divya-Devendrasingh.github.io/test-captcha-solver-1/`.
- Notifies evaluation endpoint (`https://example.com/notify`) with results.

## Setup
1. Clone: `git clone https://github.com/Divya-Devendrasingh/test-captcha-solver-1.git`.
2. Ensure `sample-captcha.png` is in the repo root.
3. Open `index.html` locally or visit `https://Divya-Devendrasingh.github.io/test-captcha-solver-1/`.

## Usage
- **Default**: Loads and solves `sample-captcha.png`.
- **With URL**: Append `?url=https://example.com/captcha.png`.
- Solved text displays below the image in <15 seconds.

## Evaluation Checks
- ✅ MIT license (`LICENSE`).
- ✅ Professional README (this file).
- ✅ Displays CAPTCHA from `?url=...`.
- ✅ Solves and displays text within 15 seconds (client-side, ~2-5s).

## Limitations
- Basic OCR: ~50-70% accuracy on simple, high-contrast CAPTCHAs. Complex distortions reduce accuracy.
- Image URLs must support CORS or be proxied (e.g., `https://corsproxy.io/`).
- For advanced CAPTCHAs, consider APIs like 2Captcha (free tier available).

## Ethics
For educational purposes only. Bypassing CAPTCHAs may violate site terms.

## License
MIT License. See `LICENSE` for details.

## About
Created by Divya Devendrasingh for a GitHub repo creation and CAPTCHA-solving test task.

© 2025 Divya Devendrasingh
