# Khadija Baaalla Palace - Hotel Feedback Website

A luxurious and responsive hotel feedback website with modern design and professional styling for Khadija Baaalla Palace.

## Features

### Design & Styling
- **Luxury Hotel Aesthetic**: Sophisticated color palette with gold and navy theme
- **Responsive Design**: Mobile-first approach that works on all devices
- **Modern Typography**: Elegant font combinations (Playfair Display + Open Sans)
- **Smooth Animations**: CSS transitions and keyframe animations
- **Professional Layout**: Clean, organized form structure with visual hierarchy

### User Experience
- **Interactive Star Rating**: Clickable star rating system with hover effects
- **Service Ratings**: Dropdown selections for different hotel services
- **Form Validation**: Built-in HTML5 validation with custom styling
- **Accessibility**: ARIA compliant, keyboard navigation, screen reader friendly
- **Loading Animations**: Smooth page load and interaction animations

### Technical Features
- **CSS Variables**: Centralized design system for easy customization
- **Flexbox & Grid**: Modern layout techniques for responsive design
- **Custom Form Controls**: Styled checkboxes, radio buttons, and form inputs
- **Cross-browser Compatibility**: Works on all modern browsers
- **Print Styles**: Optimized for printing feedback forms

## File Structure

```
hotel-feedback/
├── index.html                     # Main HTML file
├── styles.css                     # Special CSS styling
└── README.md                      # Project documentation
```

## Usage

1. **Open the Website**: Open `index.html` in any modern web browser
2. **Fill the Form**: Complete the guest feedback form with your details
3. **Rate Services**: Use the star rating and service dropdowns
4. **Submit Feedback**: Click the submit button to process the form

## Customization

### Colors
The color scheme can be easily modified by updating CSS variables in `styles.css`:

```css
:root {
    --primary-gold: #D4AF37;     /* Main accent color */
    --deep-gold: #B8941F;        /* Darker accent */
    --dark-navy: #1B2951;        /* Primary dark color */
    --cream: #F8F6F0;            /* Light background */
}
```

### Typography
Font families are defined as CSS variables:

```css
:root {
    --font-heading: 'Playfair Display', serif;
    --font-body: 'Open Sans', sans-serif;
}
```

### Spacing & Layout
Consistent spacing system using CSS variables:

```css
:root {
    --spacing-xs: 0.5rem;
    --spacing-sm: 1rem;
    --spacing-md: 1.5rem;
    --spacing-lg: 2rem;
    --spacing-xl: 3rem;
}
```

## Browser Support

- Chrome 70+
- Firefox 65+
- Safari 12+
- Edge 79+

## Responsive Breakpoints

- **Mobile**: 480px and below
- **Tablet**: 481px - 768px  
- **Desktop**: 769px and above

## Accessibility Features

- Semantic HTML structure
- ARIA labels and roles
- Keyboard navigation support
- High contrast mode support
- Screen reader optimization
- Focus indicators
- Reduced motion preferences

## Performance Features

- Optimized CSS with minimal dependencies
- Efficient animations using CSS transforms
- Compressed and organized stylesheets
- Web font preloading
- Minimal JavaScript for core functionality

## Development

### Local Development
1. Clone or download the project files
2. Open `index.html` in your preferred browser
3. Make changes to `styles.css` for styling modifications
4. Refresh the browser to see changes

### Adding New Features
- Form fields can be added by following the existing HTML structure
- New animations can be created using the established CSS patterns
- Additional pages can use the same styling framework

## Credits

- **Design**: Custom luxury hotel theme
- **Fonts**: Google Fonts (Playfair Display, Open Sans)
- **Icons**: Unicode symbols and custom CSS
- **Color Palette**: Inspired by luxury hospitality industry standards

## License

This project is open source and available under the [MIT License](LICENSE).

---

*Created with ❤️ for the hospitality industry*
