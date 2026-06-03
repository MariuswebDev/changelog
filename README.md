# Changelog Component

https://roadmap.sh/projects/changelog-component
A responsive timeline-based changelog component that displays product updates and announcements in a clean, vertical timeline format.

## Features

- **Vertical Timeline**: Displays changelog entries in a chronological vertical timeline with connecting line and dots
- **Hero Section**: Eye-catching header with title and description
- **Responsive Design**: Adapts to mobile and desktop screens with optimized layout
- **Clean Styling**: Dark theme with smooth spacing and typography
- **Call-to-Action Button**: "Visit Complete Changelog" button for additional details

## Files

- `changelog.html` - HTML markup with semantic structure and sample data
- `changelog.css` - Complete styling with responsive breakpoints

## Getting Started

1. Open `changelog.html` in a web browser
2. View the timeline of changelog entries
3. The component is fully responsive and will adapt to different screen sizes

## Customization

### Adding Timeline Items

Edit the `changelog.html` file and add new timeline items:

```html
<div class="timeline-item">
  <div class="date">Date here</div>
  <div class="dot"></div>
  <div class="content">Description of the update</div>
</div>
```

### Styling

Modify colors and spacing in `changelog.css`:

- Timeline color: `.timeline { border-color: #333 }`
- Dot color: `.dot { background: #222 }`
- Text color: `.content { color: #222 }`

## Browser Support

Works on all modern browsers including:

- Chrome
- Firefox
- Safari
- Edge

## Mobile Responsiveness

The component includes a mobile-friendly breakpoint at 768px that:

- Rearranges the timeline layout
- Adjusts date alignment
- Maintains readability on smaller screens
