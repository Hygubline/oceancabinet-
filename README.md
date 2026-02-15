# Ocean Cabinet & Countertops Website

A modern, conversion-focused website for Ocean Cabinet and Countertops, a family-owned kitchen cabinet retailer and installer in Lindenwold, NJ.

## Pages

| Page | File | Description |
|------|------|-------------|
| Home | `index.html` | Main landing page with hero, process steps, gallery preview, and contact form |
| Gallery | `gallery.html` | 3D carousel + grid gallery showcasing completed projects |
| Booking | `booking.html` | Appointment scheduling system with calendar and time slots |
| Service Area | `service-area.html` | Coverage map and showroom information |
| Thank You | `thank-you.html` | Form submission confirmation page |

## Features

### 3D Carousel Gallery
- Pure geometric cylinder rotation
- Drag-to-rotate interaction with inertia
- Click-to-focus navigation
- Lightbox for full-size viewing
- Responsive design

### Booking System
- 4-step booking flow (Service > Date/Time > Info > Confirm)
- Interactive calendar with date selection
- Time slot availability display
- Form validation
- Service options: In-Home Measurement, Showroom Visit, Design Consultation

### Service Area Map
- Real Google Maps coverage visualization
- Showroom hours and contact info
- List of towns served
- Trust badges

### Responsive Design
- Mobile-first approach
- Collapsible navigation
- Touch-friendly interactions
- Optimized for all screen sizes

## File Structure

```
website/
├── index.html          # Homepage
├── gallery.html        # Project gallery with 3D carousel
├── booking.html        # Appointment booking system
├── service-area.html   # Service coverage & map
├── thank-you.html      # Form confirmation
├── README.md           # This file
└── ocean/              # Assets folder
    ├── logo.png        # Company logo
    ├── map.png         # Service area map
    ├── kitchen*.png    # Project photos (PNG)
    ├── kitchen*.jpg    # Project photos (JPG)
    └── *.png           # Brand logos (Fabuwood, Cambria, etc.)
```

## Tech Stack

- **HTML5** - Semantic markup
- **CSS3** - Custom properties, Grid, Flexbox, animations
- **Vanilla JavaScript** - No frameworks required
- **Google Fonts** - Cormorant Garamond (serif), Inter (sans-serif)
- **Formspree** - Contact form handling

## Brand Colors

| Color | Hex | Usage |
|-------|-----|-------|
| Background | `#FAF9F7` | Page background |
| Heading | `#2A2A2A` | Headlines, footer |
| Body | `#4A4A4A` | Body text |
| Accent | `#B8977E` | Buttons, highlights |
| Accent Dark | `#9A7D66` | Hover states |

## Contact Information

- **Address:** 555 Blackwood-Clementon Road, Lindenwold, NJ 08021
- **Phone:** (856) 553-3899
- **Email:** oceancabinets888@gmail.com

## Hours

- Monday - Friday: 9:00 AM - 6:00 PM
- Saturday: 10:00 AM - 4:00 PM
- Sunday: Closed

## Deployment

This is a static website. Simply upload all files to any web hosting service:

1. Upload all HTML files to root directory
2. Upload `ocean/` folder with all assets
3. Configure domain (optional)

Compatible with: GitHub Pages, Netlify, Vercel, traditional web hosting

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome for Android)

## Credits

- Design & Development: Claude Code
- Photography: Ocean Cabinet project portfolio
- Fonts: Google Fonts
- Form Processing: Formspree

---

*Ocean Cabinet and Countertops - Kitchen renovation, simplified.*
