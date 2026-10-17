# StoryCast — Research and Design Documentation

## 1. Project Purpose

StoryCast is an accessible media feature microsite designed to showcase audio and video storytelling. The design emphasizes clear navigation, responsive presentation, semantic HTML, and alternatives for users who cannot access media through sound or visuals alone.

## 2. Information Architecture

### Sitemap

```text
StoryCast Home
│
├── Featured Stories
│   └── Story Detail
│       ├── Audio Player
│       ├── Video Player
│       ├── Transcript
│       └── Related Stories
│
└── About & Access
    ├── Mission
    ├── Accessibility Features
    └── Discover Stories
```

### Navigation Strategy

The primary navigation provides access to Home, Stories, About, and Access. Story cards lead to the story detail page, while calls to action guide visitors toward featured content.

## 3. Target Audience

StoryCast is designed for people who enjoy personal stories, interviews, documentaries, and other forms of digital storytelling. It also considers people who use keyboards, screen readers, captions, or transcripts to access online content.

## 4. Wireframes

Add the link to your low-fidelity wireframes here:

**Wireframe link:** [Insert your Figma wireframe URL]

The wireframes should show the header, hero section, featured stories, accessibility information, and footer. Include mobile and desktop layouts.

## 5. High-Fidelity Mockups

Add the link to your finished Figma designs here:

**High-fidelity mockup link:** [Insert your Figma design URL]

The final designs should reflect the dark charcoal interface, vivid orange accents, consistent typography, story imagery, responsive cards, and accessible navigation.

## 6. Visual Design Rationale

The charcoal background creates a cinematic atmosphere suitable for media storytelling. Orange accents draw attention to calls to action and important interface elements. Clear typography, spacing, and consistent cards help users scan content.

## 7. Technical Approach

- Semantic HTML5 provides page structure and meaning.
- Sass partials organize colors, typography, spacing, layout, components, and accessibility styles.
- CSS Grid and Flexbox support responsive layouts.
- CSS container queries adapt individual story cards to the available width.
- Native HTML media elements provide standard playback controls.
- Transcripts and caption tracks support alternative ways of accessing media.

## 8. Accessibility Considerations

The implementation includes skip navigation, visible keyboard focus, descriptive image alternatives, responsive layouts, and reduced-motion support. Native media controls, captions, and transcripts are included in the design.

The final website must still be tested for color contrast, keyboard operation, caption accuracy, transcript accuracy, and screen-reader compatibility before claiming WCAG 2.1 AA conformance.

## 9. Evaluation

Evaluate the website at mobile and desktop widths. Check that navigation works, story cards remain readable, media alternatives are available, and focus states are visible. Test the deployed website as well as the local version.

## 10. Conclusion

StoryCast combines storytelling and inclusive design in a lightweight microsite built with HTML, Sass, and vanilla JavaScript. Its information architecture and responsive interface aim to make stories easier to discover and experience.
