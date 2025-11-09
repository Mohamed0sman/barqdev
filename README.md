# BARQ DEV - AI-Powered Development Platform

A modern, professional website with stunning animations and EmailJS integration.

## Features

✨ **Modern Design**
- Glassmorphism effects
- 3D card animations
- Particle.js background
- Smooth scroll animations with AOS
- Custom cursor effects
- Gradient animations

🎨 **Professional UI/UX**
- Responsive design for all devices
- Interactive hover effects
- Smooth transitions
- Loading animations
- Glitch text effects

📧 **Web3Forms Integration**
- Contact form with email notifications
- No backend required
- Instant setup
- Spam protection
- Form validation
- Loading states

## Setup Instructions

### 1. Web3Forms Configuration ✅

**Already Configured!** The form is ready to use with your Access Key:
- Access Key: `b807247d-c1fc-4272-8aba-ebd06f1ca287`

The contact form will send emails directly to your registered email address.

**To customize:**
1. Go to [Web3Forms Dashboard](https://web3forms.com/)
2. Login with your account
3. View submissions and configure settings
4. Optional: Add custom redirect URL or email templates

**Features included:**
- ✓ Spam protection (honeypot)
- ✓ Email notifications
- ✓ Form validation
- ✓ Custom subject line
- ✓ All form fields captured

### 2. File Structure

```
project/
│
├── index.html          # Home page
├── services.html       # Services page
├── about.html          # About page
├── contact.html        # Contact page with EmailJS form
├── styles.css          # All styles and animations
├── script.js           # JavaScript with animations & EmailJS
└── README.md           # This file
```

### 3. Running the Website

Simply open `index.html` in your browser or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve

# Using PHP
php -S localhost:8000
```

Then visit: `http://localhost:8000`

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Advanced animations and effects
- **JavaScript (ES6+)** - Interactive features
- **Web3Forms** - Email service integration (no backend needed)
- **AOS** - Animate On Scroll library
- **Particles.js** - Particle background effects
- **Font Awesome** - Icons

## Key Features Explained

### Animations
- **AOS (Animate On Scroll)**: Elements fade in as you scroll
- **3D Card Effects**: Cards tilt on mouse hover
- **Counter Animation**: Numbers count up when visible
- **Glitch Effect**: Cyberpunk-style text animation
- **Particle Background**: Interactive particle system
- **Custom Cursor**: Animated cursor for desktop

### Web3Forms Integration
The contact form sends emails directly without a backend server:
1. User fills the form
2. Web3Forms API processes the submission
3. Email sent to your registered address
4. Success/error message displays
5. Form resets on success

**Advantages:**
- No API keys in frontend (secure)
- Built-in spam protection
- Free tier: 250 submissions/month
- Easy to setup and use

### Responsive Design
- Mobile-first approach
- Breakpoints: 640px, 768px, 968px
- Touch-friendly navigation
- Optimized for all screen sizes

## Customization

### Colors
Edit CSS variables in `styles.css`:
```css
:root {
    --color-primary: #FFD700;
    --color-secondary: #001A4D;
    --color-accent: #00A8E8;
    /* ... */
}
```

### Content
- Update text in HTML files
- Replace placeholder images
- Modify service offerings
- Update contact information

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance

- Optimized animations
- Lazy loading ready
- Minimal dependencies
- Fast load times

## License

© 2024 BARQ DEV. All rights reserved.

## Support

For questions or support, contact:
- Email: info@barqdev.com
- Website: [Your Website]

---

Made with ❤️ by BARQ DEV
