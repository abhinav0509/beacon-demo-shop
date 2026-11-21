# Fern and Clay — Beacon demo shop

A small static site for demonstrating [Beacon](https://github.com/abhinav0509/agentic-design-auditor),
an accessibility agent that proposes verified fixes as pull requests.

It has three accessibility issues on purpose:

- `index.html` does not declare its language.
- `about.html` has a photo without alt text.
- `contact.html` has a form field without a label.

Beacon scans the live GitHub Pages site, proposes a fix for each, verifies it, and opens a PR once
a person approves it. Nothing here is a real shop.
