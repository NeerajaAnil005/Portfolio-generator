# 🚀 Developer Portfolio Generator
A lightweight, front-end web application that transforms standard Markdown resumes into professional, styled portfolio websites instantly.

## 📌 Overview
Many developers spend more time tweaking CSS than actually building projects. This tool simplifies that process. By leveraging Marked.js, this generator allows users to focus on content (Markdown) while the application handles the visual presentation.

Key Features:
Instant Preview: See changes in real-time as you type your Markdown.

Theming System: Toggle between elegant Light and Dark modes.

Modern UI: Built with a "pastel-modern" aesthetic featuring smooth hover animations and responsive layouts.

No Backend Required: Runs entirely in the browser for maximum speed and privacy.

## 🛠️ Tech Stack
HTML5: Semantic structure for the editor and preview panes.

CSS3: Custom styling, Flexbox/Grid layouts, and CSS variables for theming.

JavaScript (ES6+): Logic for DOM manipulation and event handling.

Marked.js: A high-speed Markdown parser and compiler.

## 🏗️ Project Structure
Plaintext
portfolio-generator/
│
├── index.html    # Main application structure
├── style.css     # Theming and layout styling
├── script.js    # Markdown parsing & theme logic
└── README.md     # Documentation
## 🚀 How It Works
The application follows a simple Input → Parse → Render flow:

Input: The user types or pastes Markdown text into a <textarea>.

Parse: JavaScript captures the input and passes it through the Marked.js library.

Render: The resulting HTML is injected into a "Preview" <div> using innerHTML.


## 🎨 Usage
Enter your professional details (Bio, Projects, Experience) in the left panel using Markdown syntax.

Select your preferred theme using the toggle switch.

Observe the live-rendered portfolio on the right.

Copy the generated layout or use it as a base for your hosted site!

## ✅ Future Enhancements
[ ] Export to PDF: Allow users to download their styled resume.

[ ] Multiple Templates: Add a selection of different layout styles (Minimal, Bold, Creative).

[ ] Local Storage: Automatically save the user's progress so content isn't lost on refresh.
