# Bento Grid Layout Project

## 🔗 Live Demo

[Click here to view the live site](https://aya1133.github.io/bento-grid1/)


## Overview
This project demonstrates a modern Bento grid layout for a social media management tool that highlights AI-powered features. The design uses CSS Grid to create an asymmetrical, visually interesting layout with various card components.

## Features
- Responsive grid layout
- Visually distinct card components
- Custom typography with Google Fonts
- Attractive color scheme
- Optimized for desktop viewing

## Technologies Used
- HTML5
- CSS3 (Grid, Flexbox)
- Google Fonts (DM Sans, Fraunces, Montserrat)

## Implementation Details
The layout uses CSS Grid with named template areas to create the distinctive Bento box pattern. Each card has unique styling and content focused on different features of the social media management platform.

## How to Use
Simply open the index.html file in a web browser to view the layout.
  
```
/
├── index.html          # Main HTML document
├── style.css           # CSS styling
└── assets/
    └── images/         # Contains all illustrations and icons
```

## CSS Grid Implementation

The layout uses CSS Grid with named grid areas for an organized card arrangement:

```css
grid-template-areas: "cardGroup card-1 card-1 card-4"
                     "cardGroup card-2 card-3 card-4"
                     "cardGroup card-6 card-5 card-5";
```

This creates a visually interesting arrangement with cards of different sizes and proportions.

## Card Components

Each card in the grid represents a different feature or benefit:

1. **Main Headline Card**: Social Media 10x Faster with AI
2. **Feature Cards**: Multiple smaller cards showcasing specific features
3. **Statistics Card**: Shows growth statistics
4. **Group Cards**: A set of related features grouped together

## Responsive Behavior

The layout is responsive and adjusts for different screen sizes:
- Desktop: Full grid layout
- Tablet: Simplified 2-column grid
- Mobile: Single column for easy scrolling on small screens

## Color Scheme

The project uses a vibrant color palette:
- Purple: `hsl(256, 67%, 59%)` - Primary color for key feature highlights
- Yellow: `hsl(39, 100%, 71%)` - Accent color for important elements
- Light Purple: `hsl(254, 88%, 90%)` - Secondary background
- Cream: `hsl(31, 66%, 93%)` - Subtle background
- White: `hsl(0, 0%, 100%)` - Card backgrounds
- Black: `hsl(0, 0%, 7%)` - Text color

## Browser Compatibility

The project is designed to work on modern browsers that support CSS Grid Layout including:
- Chrome, Firefox, Safari, Edge (latest versions)

## Future Improvements

Possible enhancements for the project:
- Add animation effects for card interactions
- Implement dark mode theme
- Add actual functionality for a working prototype
- Improve accessibility features
