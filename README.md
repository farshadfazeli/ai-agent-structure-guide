# AI Agent Structure Guide

An interactive, bilingual (Persian / English) learning hub for understanding how an AI Agent project is structured. It covers the role of each Markdown file in an Agent project, the difference between a Workflow and a Skill, and includes a 20-question quiz with instant feedback.

This repository is a personal rewrite and summary of concepts I learned from an AI Agent course. I built it to review the material properly and to have a clean reference I can go back to. It is not the official course content.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![RTL and LTR](https://img.shields.io/badge/RTL%20%26%20LTR-supported-3157d5)
![License](https://img.shields.io/badge/License-MIT-green)

---

## What this project does

- A single `index.html` acts as a hub with three cards. Clicking a card opens the related page inside an embedded iframe, so everything stays in one place.
- The whole interface supports Persian (right-to-left) and English (left-to-right). You can switch the language from the top of the page.
- The quiz page gives instant feedback, shows a final score, and explains every wrong answer.
- The comparison page walks through Workflow vs Skill with a daily-life analogy, a step-by-step example, and a direct comparison table.
- Everything is plain HTML, CSS, and JavaScript. No framework, no build step, no dependencies.

---

## Pages

| File | What it covers |
|------|----------------|
| `index.html` | The main hub. Three cards, each opens its content in an iframe. |
| `Difference Between a Workflow and a Skill.html` | A simple, practical explanation of Workflow vs Skill, with analogies and a comparison table. |
| `Agent Quiz.html` | A 20-question quiz about the role of `agent.md`, `rules.md`, `command.md`, `security.md`, `convention.md`, `skill.md`, and `verification.md`. |
| `File Structure Guide.html` | An overview of what each Markdown file in an Agent project is responsible for. |

If you rename any of these files, update the matching `data-src` attribute inside `index.html`. Otherwise the card will open an empty iframe.

---

## How to run it

Locally, just open `index.html` in a browser. There is nothing to install.

To publish it, go to the repository settings, open the Pages section, choose the `main` branch and the root folder, then save. GitHub will give you a public link.

---

## Who this is for

- Students learning about AI Agent architecture and how the `.md` files fit together.
- Anyone who wants a short reference for what each file does, without reading a long document.
- People preparing to teach or assist in an AI Agent course.
- Developers who prefer learning by clicking through an interface rather than reading walls of text.

---

## A note on the content

This repository is a personal rewrite and summary of concepts I learned from an AI Agent course. The examples, explanations, and quiz questions were re-created in my own words for practice and review. It is not the official course material, and no proprietary content is reproduced verbatim.

If you are the course author and have any concerns, please open an issue.

---

## Tech stack

Plain HTML5, CSS3, and vanilla JavaScript. The Vazirmatn font is loaded from Google Fonts. No frameworks, no bundlers, no dependencies.

---

## Contributing

Corrections, better explanations, and additional quiz questions are welcome. Open an issue or send a pull request.

---

## License

MIT. You are free to use, adapt, and share it.
