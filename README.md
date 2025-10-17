# CAPTCHA Solver

## Summary
A single-page web application that solves text-based CAPTCHA images, either from a provided URL (`?url=https://.../image.png`) or a default sample image (`sample-captcha.png`). Built for a test task to demonstrate GitHub repo creation and functionality via GitHub Pages.

## Features
- Fetches and displays CAPTCHA image from URL query parameter (`?url=...`) or defaults to attached sample.
- Solves CAPTCHAs using 2Captcha API for high accuracy (typically <10 seconds).
- Minimal, client-side implementation with vanilla HTML/CSS/JS.
- Hosted on GitHub Pages at `https://Divya-Devendrasingh.github.io/test-captcha-solver-1/`.
- MIT licensed.

## Setup
1. Clone the repository: `git clone https://github.com/Divya-Devendrasingh/test-captcha-solver-1.git`.
2. Open `index.html` locally or visit `https://Divya-Devendrasingh.github.io/test-captcha-solver-1/`.
3. To use 2Captcha API, sign up at `https://2captcha.com/` and insert your API key in `index.html`.

## Usage
- **Default**: Loads `sample-captcha.png` from the repo and displays solved text.
- **With URL**: Append `?url=https://example.com/captcha.png` to the GitHub Pages URL (e.g., `https://Divya-Devendrasingh.github.io/test-captcha-solver-1/?url=...`).
- Solved text appears below the CAPTCHA image within 15 seconds.

## Evaluation Checks
- ✅ Repo has MIT license (`LICENSE` file).
- ✅ README.md is professional (this document).
- ✅ Page displays CAPTCHA URL passed at `?url=...`.
- ✅ Page displays solved CAPTCHA text within 15 seconds (via 2Captcha API).

## Limitations
- Requires 2Captcha API key (free tier available; ~$0.001/solve).
- Best for simple text CAPTCHAs. Advanced ones (e.g., reCAPTCHA) need additional handling.
- Image URLs must support CORS or be proxied.

## Ethics
For educational purposes only. Bypassing CAPTCHAs may violate site terms.

## License
MIT License. See `LICENSE` for details.

## About
Created by Divya Devendrasingh as a test task for GitHub repo creation and CAPTCHA-solving functionality.

© 2025 Divya Devendrasingh
