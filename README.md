# The Golden Spoon Restaurant Website

A beautiful, responsive single-page website for a restaurant featuring menu, hours, and contact form with modern design principles.

## Features

- **Responsive Design**: Works perfectly on mobile, tablet, and desktop devices
- **Accessibility**: ARIA labels, keyboard navigation, sufficient color contrast
- **SEO Optimized**: Proper meta tags and JSON-LD structured data
- **Modern UI**: Clean, elegant design with smooth animations
- **Form Validation**: Client-side validation for contact form
- **Smooth Scrolling**: Anchor links with smooth scrolling behavior

## File Structure

```
restaurant-website/
├── index.html          # Main HTML file
├── css/
│   └── styles.css      # Stylesheet with design tokens and responsive design
├── js/
│   └── script.js       # JavaScript for form validation and interactivity
└── README.md           # This file
```

## Design Tokens

### Color Palette
- **Primary**: #8B4513 (Saddle Brown)
- **Secondary**: #D2691E (Chocolate)
- **Background**: #F8F4E3 (Antique White)
- **Text**: #333333 (Dark Gray)
- **Light Text**: #FFFFFF (White)

### Typography
- **Headings**: Playfair Display (serif)
- **Body**: Open Sans (sans-serif)

### Spacing System
- xs: 0.5rem
- sm: 1rem
- md: 1.5rem
- lg: 2rem
- xl: 3rem

## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/abhinavpadige4/restaurant-website.git
   ```

2. **Open the website**:
   Simply open `index.html` in your web browser, or
   
3. **Deploy to GitHub Pages**:
   - Push to GitHub
   - Go to repository Settings > Pages
   - Select main branch as source
   - Your site will be published at https://abhinavpadige4.github.io/restaurant-website/

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Accessibility Features

- ARIA labels on navigation and form elements
- Keyboard navigable interface
- Sufficient color contrast (WCAG AA compliant)
- Visible focus outlines
- Semantic HTML5 structure
- Alt text for images (where applicable)

## SEO Features

- Proper title tag and meta description
- Viewport meta tag for mobile optimization
- JSON-LD structured data for LocalBusiness schema
- Semantic HTML5 elements
- Descriptive heading structure

## Form Validation

The contact form includes client-side validation for:
- Required fields (name, email, message)
- Email format validation
- Visual feedback for errors and success states

## Customization

To customize this website for your own restaurant:

1. **Update the restaurant name**: Replace "The Golden Spoon" in index.html
2. **Update menu items**: Modify the menu section in index.html
3. **Update hours**: Change the opening hours in the hours section
4. **Update contact information**: Modify the contact details in the contact section
5. **Update colors**: Modify the CSS variables in css/styles.css
6. **Update fonts**: Change the Google Fonts link in index.html

## Credits

- Fonts: Google Fonts (Playfair Display, Open Sans)
- Icons: Would typically use Font Awesome or similar (placeholder text links used)
- Images: Would use Unsplash or similar service for food photography

## License

This project is open source and available under the MIT License.