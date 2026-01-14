# Studio Lokal

A modern, professional website for Studio Lokal - a marketing and consulting agency.

## Overview

Studio Lokal is a marketing and consulting agency dedicated to helping local businesses thrive through strategic marketing solutions, brand development, and business consulting services.

## Features

- **Responsive Design**: Fully responsive layout that works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations and transitions
- **Single Page Application**: Smooth scrolling navigation between sections
- **Contact Form**: Interactive contact form for client inquiries
- **Service Showcase**: Detailed presentation of agency services
- **Mobile Navigation**: Hamburger menu for mobile devices

## Structure

- `index.html` - Main HTML structure
- `styles.css` - All styling and responsive design
- `script.js` - Interactive functionality and form handling

## Getting Started

### Local Development

Simply open `index.html` in your web browser:

```bash
# Option 1: Direct open
open index.html

# Option 2: Using Python's built-in server
python3 -m http.server 8000

# Option 3: Using Node.js http-server
npx http-server
```

Then navigate to `http://localhost:8000` in your browser.

## Sections

1. **Home/Hero**: Eye-catching introduction with call-to-action
2. **About**: Overview of Studio Lokal's mission and approach
3. **Services**: Six core service offerings
4. **Contact**: Contact form for inquiries
5. **Footer**: Copyright and social media links

## Customization

### Colors

Edit CSS variables in `styles.css`:

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #1e40af;
    --text-color: #1f2937;
    /* ... more variables */
}
```

### Content

Update text content directly in `index.html` in the respective sections.

### Services

Modify the services grid in the `#services` section of `index.html`.

## Future Enhancements

- Add backend integration for contact form
- Implement portfolio/case studies section
- Add team member profiles
- Integrate blog/news section
- Add client testimonials
- Implement analytics tracking
- Add multi-language support

## License

© 2026 Studio Lokal. All rights reserved.