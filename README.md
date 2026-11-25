<h1 align="center">Why Mathematics Is the Foundation of Everything</h1>

<p align="center">
  <em>A long-form bilingual (English / فارسی) essay on how mathematics underpins computer science and artificial intelligence.</em>
</p>

<p align="center">
  <a href="https://aghorbani84.github.io/Mathematics/"><img src="https://img.shields.io/badge/Read_online-GitHub_Pages-222222?logo=githubpages&logoColor=white" alt="Read online on GitHub Pages" /></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License: MIT" /></a>
  <img src="https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/Languages-EN%20%2F%20FA-0D9488" alt="English / Persian" />
</p>

<p align="center">
  <a href="https://aghorbani84.github.io/Mathematics/"><strong>📖 Read the article →</strong></a>
</p>

---

## Overview

This repository holds a single self-contained web page: a research-style article that walks from the philosophy of mathematics to the math behind modern software and AI, with short Python examples along the way. The full text is available in both English and Persian, with a language switch on the page.

## Contents

| # | Section |
|---|---|
| 01 | The Philosophy of Mathematics |
| 02 | Mathematics in Computer Science — discrete math & logic, graph theory & networks, cryptography & cybersecurity, algorithmic complexity & Big-O |
| 03 | Mathematics in Artificial Intelligence — linear algebra, calculus & backpropagation, probability & statistics |
| 04 | The Future — Quantum Computing & AGI |
| ∎ | Conclusion — Read the Source Code |
| ⌘ | References & Further Reading |

Code examples in the article (Python): a toy RSA implementation, complexity comparison, matrix multiplication, and gradient descent.

## Features

- **Bilingual**: full English and Persian versions with RTL support and a language toggle
- **Dark / light theme** toggle
- **Table of contents** sidebar and reading-progress indicator
- **Copy buttons** on code blocks
- **Scroll-reveal animations** that respect `prefers-reduced-motion`
- **Single file, no build step** — just `index.html`

## Tech Stack

- HTML5, CSS, vanilla JavaScript (all inline in `index.html`)
- Fonts via jsDelivr: Inter, Vazirmatn, JetBrains Mono, STIX Two Text
- Hosted on GitHub Pages

## Getting Started

Read it online at **https://aghorbani84.github.io/Mathematics/**, or run it locally:

```bash
git clone https://github.com/aghorbani84/Mathematics.git
cd Mathematics
# open index.html in your browser, or serve it:
python3 -m http.server 8000   # then visit http://localhost:8000
```

## Project Structure

```
.
├── index.html   # The complete article (markup, styles, scripts)
├── LICENSE      # MIT
└── README.md
```

## License

Released under the [MIT License](LICENSE).

## Author

Written by **Abolfazl Ghorbani** — [@aghorbani84](https://github.com/aghorbani84)
