# Voices of Change - Homepage

An interactive homepage for Voices of Change, built with plain HTML, CSS, and JavaScript.

## Features

- **Navigation Menu**: Links to Profile, Gallery, and Contact sections
- **Newsletter Subscription**: Email form with validation and accessibility features
- **Media Gallery**: Image, audio, and video elements with proper semantic markup
- **External Links**: Connection to partner organizations
- **Accessibility**: ARIA roles, keyboard navigation, high contrast support
- **Responsive Design**: Mobile-friendly layout using CSS Grid

## Project Structure

```
voices-of-change/
├── index.html          # Main HTML file
├── styles.css          # External stylesheet
├── script.js           # JavaScript functionality
├── images/             # Image assets
├── audio/              # Audio files
├── video/              # Video files
└── README.md           # This file
```

## Setup Instructions

1. Open the project folder in VS Code
2. Add your media files to the respective directories:
   - `images/activism.jpg` - Main hero image
   - `images/video-poster.jpg` - Video thumbnail
   - `audio/testimonial.mp3` - Audio testimonial (MP3 format)
   - `audio/testimonial.ogg` - Audio testimonial (OGG format)
   - `video/movement.mp4` - Video documentary (MP4 format)
   - `video/movement.webm` - Video documentary (WebM format)

3. Open `index.html` in your web browser or use a local server

## Accessibility Features

- Semantic HTML structure with proper heading hierarchy (H1-H4)
- ARIA roles and labels for screen readers
- Keyboard navigation support with arrow keys for navigation
- High color contrast ratios (WCAG AA compliant)
- Focus indicators for interactive elements
- Skip link for screen reader users
- Reduced motion support for users with vestibular disorders

## Browser Support

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Responsive design works on mobile and desktop
- Graceful degradation for older browsers

## Customization

- Colors can be modified in `styles.css`
- Content can be updated in `index.html`
- JavaScript functionality can be extended in `script.js`

## Development

To run the project locally:
1. Navigate to the project directory
2. Open `index.html` in your browser
3. For a better development experience, use a local server (e.g., `python -m http.server` or VS Code Live Server extension)
