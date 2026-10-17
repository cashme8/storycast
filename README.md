# StoryCast — An Accessible Media Feature Microsite

## Project Overview

StoryCast is a responsive storytelling microsite that presents audio and video stories through a modern, dark interface with vivid orange accents. The project focuses on semantic HTML, accessible media, responsive layouts, and maintainable Sass architecture.

## Pages

- **Home (`index.html`):** Introduces StoryCast and showcases featured stories.
- **Story Detail (`story/index.html`):** Presents a featured story with audio and video player examples, a written transcript, and related stories.
- **About & Access (`about.html`):** Explains the mission of StoryCast and its accessibility goals.

## Project Structure

```text
storycast/
├── index.html
├── about.html
├── story/
│   └── index.html
├── sass/
│   ├── main.scss
│   ├── _colors.scss
│   ├── _typography.scss
│   ├── _spacing.scss
│   ├── _base.scss
│   ├── _layout.scss
│   ├── _components.scss
│   └── _accessibility.scss
├── css/
│   └── main.css
├── assets/
│   ├── images/
│   ├── audio/
│   ├── video/
│   ├── captions/
│   └── transcripts/
└── docs/
    └── storycast-research.pdf
```

## Technologies

- HTML5 for semantic page structure
- Sass/SCSS for maintainable styling
- CSS Grid and Flexbox for responsive layouts
- CSS container queries for adaptive story cards
- Vanilla JavaScript for small enhancements

No frontend frameworks are used.

## Running Locally

1. Install Node.js and npm.
2. Open the project directory in VS Code.
3. Install Sass:

   `npm install --save-dev sass`

4. Start the Sass compiler:

   `npm run sass`

5. Use the VS Code Live Server extension to open `index.html`.

Keep the Sass compiler running while editing styles.

## Accessibility Checklist

- [x] Semantic HTML landmarks and logical heading structure
- [x] Skip link to main content
- [x] Descriptive image alternatives
- [x] Visible keyboard focus indicators
- [x] Responsive layouts
- [x] Reduced-motion preference support
- [x] Native audio and video controls in the story page
- [x] Transcript section provided as a text alternative example
- [x] Caption track element provided for video
- [ ] Verify that final audio and video files exist and play
- [ ] Add and verify captions synchronized with the final video
- [ ] Verify the transcript against the actual media
- [ ] Test keyboard navigation, contrast, and screen-reader behavior
- [ ] Complete WCAG 2.1 AA checks before claiming full conformance

## Design Decisions

The dark charcoal background and orange accent color create a consistent visual identity. Clear headings, readable text, visible focus indicators, responsive story cards, and text alternatives support an inclusive experience across screen sizes.

## Research and Documentation

The research PDF includes the information architecture, sitemap, wireframes, high-fidelity mockup links, and design rationale.

## Project Status

This project is developed for an academic assignment. Media placeholders and accessibility features must be tested with the final content before deployment.
