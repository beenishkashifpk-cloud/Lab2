# My Profile Page

A semantic HTML5 profile page built for **CIT331 Lab 2**. It features a
multi-field accessible contact form and a localStorage feature that
remembers the visitor's name and topic between visits.

**Author:** Beenish Kashif

## What I Did in This Lab

1. **Planned the content.** Filled in a planning table and wrote my real
   About Me text, skills, timeline milestones, and a fun fact before
   writing any HTML.
2. **Built the semantic skeleton.** Created the document shell, then added
   `<header>`, `<nav>`, `<main>`, `<article>`, `<section>`, `<aside>`, and
   `<footer>`, and checked the landmarks in DevTools.
3. **Added a skip link.** A "Skip to main content" link at the top of the
   page for keyboard users, pointing to `id="main-content"`.
4. **Added rich content.**
   - About Me with a photo (`<figure>`, meaningful `alt` text) and a `<blockquote>`
   - Skills as an unordered list (`<ul>`)
   - Timeline as an ordered list (`<ol>`)
   - Fun Fact in an `<aside>`
5. **Embedded multimedia.** A `<video controls>` element with two sources
   (`.webm` and `.mp4`), fallback text, and a text transcript summary for
   accessibility.
6. **Built an accessible contact form** with eight input types, each with a
   correctly linked `<label>`:
   text, email, select, radio buttons, checkbox, date, range, and textarea.
   Validation uses `required`, `type="email"`, and `minlength="10"`, and I
   tested each rule by deliberately breaking it.
7. **Added a localStorage feature** in `script.js`:
   - Saves the visitor's name and topic when the form is submitted
   - Restores both values when the page loads
   - A "Clear Saved Data" button removes both values and resets the form
8. **Validated and tested.** Ran the page through the W3C validator, went
   through an accessibility checklist, and tested the page with keyboard-only
   navigation.
9. **Published to GitHub** with a README and a `.gitignore`.

## Project Structure

```
lab2-semantic-page/
├── index.html      # Page structure and content
├── script.js       # localStorage save, restore, and clear
├── README.md       # This file
├── .gitignore      # Ignores .DS_Store and Thumbs.db
├── images/         # Profile photo
├── intro.mp4       # Video clip (MP4)
└── intro.webm      # Video clip (WebM)
```

## How to Run

1. Clone or download this repository.
2. Open the folder in VS Code.
3. Right-click `index.html` and choose **Open with Live Server**
   (or simply open `index.html` in a browser).

## Technologies

- HTML5 (semantic elements, forms, multimedia)
- JavaScript (Web Storage API: `localStorage`)
- Git and GitHub
