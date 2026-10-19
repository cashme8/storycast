# StoryCast – Accessible Media Stories

## About the Project

StoryCast is a small media website built to share stories through video, images, and written content. The idea is to make stories easy to explore while keeping the website accessible to different users.

For this project, I focused on a story about Rwanda's journey towards Formula 1 and how motorsport connects with the country's future.

## Features

- A homepage introducing the featured story.
- A video embedded from YouTube.
- A slideshow that displays images from the project’s assets folder.
- Additional story sections with images and descriptions.
- An accessibility page with information about the website's design.
- Responsive layouts for different screen sizes.
- Accessibility features such as semantic HTML, keyboard focus styles, and reduced-motion support.

## Technologies Used

- HTML5
- Sass (SCSS)
- CSS Grid and Flexbox
- JavaScript
- YouTube embedded video

## Project Structure

```text
StoryCast/
├── index.html
├── about.html
├── story/
│   └── index.html
├── sass/
│   ├── main.scss
│   ├── _base.scss
│   ├── _layout.scss
│   ├── _components.scss
    ├── _accessibility.scss
    ├── _typography.scss
    ├── _colors.scss
    └── _spacing.scss
├── css/
│   └── main.css
└── assets/
    └── images/
```

## Running the Website

1. Download or clone the repository.
2. Open the project folder in VS Code.
3. Open `index.html` in a browser, or use the Live Server extension.
4. Make sure the Sass files are compiled whenever changes are made to the styles.

## Accessibility

Accessibility was considered throughout the design. The project uses semantic HTML, visible keyboard focus styles, and reduced-motion support. The media content is also supported by written information where available.

## What I Learned

Working on StoryCast helped me practise structuring a multi-page website, organising Sass files, embedding media, and making layouts responsive. It also helped me understand why accessibility needs to be considered during development, rather than added at the end.

## Project Status

This project was developed as part of a web design assignment.
