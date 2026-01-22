# Stefan Drazic Fitness Coaching Website

A professional fitness coaching website built with TypeScript, HTML, and CSS.

## Project Structure

```
├── index.html                 # Home page
├── privacy-policy.html        # Privacy policy page
├── terms.html                 # Terms and conditions page
├── package.json               # Project configuration
├── tsconfig.json              # TypeScript configuration
├── src/
│   ├── main.ts               # Main TypeScript application
│   └── styles.css            # Global styles
└── dist/                      # Compiled output (generated)
```

## Features

- **Responsive Design**: Mobile-friendly layout that works on all devices
- **Navigation Menu**: Consistent navigation across all pages
- **Footer**: Standardized footer with contact information placeholders
- **CTA Button**: "Book a Free Call" button on home page
- **Professional Styling**: Modern, clean design with purple and green accent colors
- **Legal Pages**: Privacy Policy and Terms & Conditions included

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn package manager

### Installation

1. Install dependencies:
```bash
npm install
```

2. Build TypeScript:
```bash
npm run build
```

3. Watch for changes during development:
```bash
npm run dev
```

## Customization

### Footer Information

Edit the footer sections in each HTML file to add:
- Email address: Replace `[Your Email Here]`
- Business address: Replace `[Your Address Here]`

The footer is consistently included on:
- index.html (Home)
- privacy-policy.html
- terms.html

### Booking Integration

To integrate with a booking platform (Calendly, Acuity Scheduling, etc.):

1. Update the `bookCall()` function in `src/main.ts`
2. Replace the example link in the HTML files
3. Update the alert message in index.html

Example for Calendly:
```typescript
function bookCall(): void {
  window.location.href = 'https://calendly.com/your-username/30min';
}
```

### Content Updates

- **Home Page** (`index.html`): Add your coaching testimonials, pricing, or additional services
- **Privacy Policy** (`privacy-policy.html`): Review and customize based on your data practices
- **Terms & Conditions** (`terms.html`): Customize with your specific business terms

## Styling

Main color scheme:
- Primary Gradient: #667eea to #764ba2 (hero section)
- Accent Color: #4CAF50 (buttons, borders)
- Background: #1a1a1a (navigation/footer)
- Text: #333 on light backgrounds, #fff on dark backgrounds

Edit `src/styles.css` to customize colors, fonts, and layouts.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Author

Stefan Drazic LLC - Professional Fitness Coaching

## License

MIT License - See LICENSE file for details
