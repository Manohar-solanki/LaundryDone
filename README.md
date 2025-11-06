# LaundryDone - Professional Laundry Service Website

A modern, responsive, and fully functional laundry service website built with HTML, CSS, and JavaScript. This website enables visitors to learn about laundry services and easily place orders via a simple booking form or by calling/messaging.

## Features

- ✅ **Fully Responsive Design** - Works seamlessly on mobile, tablet, and desktop
- ✅ **Modern UI/UX** - Clean, minimal design with a calming color palette
- ✅ **No User Accounts Required** - Simple lead generation form
- ✅ **Multiple Pages** - Home, Services, Pricing, How It Works, Booking, About, FAQ, Contact
- ✅ **Mobile-First Approach** - Optimized for mobile devices
- ✅ **Accessibility** - WCAG 2.1 AA compliant with proper semantic HTML
- ✅ **Fast Loading** - Optimized for performance
- ✅ **SEO Optimized** - Proper meta tags and semantic structure
- ✅ **WhatsApp Integration** - Direct WhatsApp chat button
- ✅ **Click-to-Call** - Easy phone number dialing on mobile
- ✅ **Cost Estimator** - Interactive pricing calculator
- ✅ **FAQ Accordion** - Expandable FAQ section
- ✅ **Form Validation** - Client-side form validation

## Pages

1. **Homepage** (`index.html`) - Hero section, services overview, testimonials, service area
2. **Services** (`services.html`) - Detailed service descriptions
3. **Pricing** (`pricing.html`) - Transparent pricing with cost estimator
4. **How It Works** (`how-it-works.html`) - 3-step process explanation
5. **Booking** (`booking.html`) - Service booking form
6. **About** (`about.html`) - Company story and values
7. **FAQ** (`faq.html`) - Frequently asked questions
8. **Contact** (`contact.html`) - Contact information and form

## Setup Instructions

### 1. Form Submission Setup

The website uses Formspree for form submissions. You need to:

1. Sign up for a free account at [Formspree.io](https://formspree.io)
2. Create a new form and get your form ID
3. Replace `YOUR_FORM_ID` in the following files:
   - `booking.html` (line with `action="https://formspree.io/f/YOUR_FORM_ID"`)
   - `contact.html` (line with `action="https://formspree.io/f/YOUR_FORM_ID"`)

Alternatively, you can use:
- Google Sheets with Google Apps Script
- Airtable
- Your own backend API
- Email service (requires server-side processing)

### 2. Update Contact Information

Update the following information throughout the website:

- **Phone Number**: Replace `+91 98765 43210` with your actual phone number
- **Email**: Replace `info@laundrydone.com` with your actual email
- **Location**: Update "Jaipur, Rajasthan" with your actual location
- **Service Areas**: Update the service areas list on the homepage
- **Google Maps**: Update the Google Maps embed URL in `contact.html` with your actual location

### 3. Customize Content

- Update company name "LaundryDone" if needed
- Modify service descriptions to match your offerings
- Update pricing to reflect your actual rates
- Add your own testimonials and customer reviews
- Update the "About Us" section with your story

### 4. Add Images (Optional)

Currently, the website uses emoji icons. You can replace them with actual images:

- Service icons
- Team photos
- Customer photos
- Laundry facility images

To add images:
1. Create an `images` folder
2. Add your images
3. Update the HTML to use `<img>` tags instead of emoji

### 5. Deploy

You can deploy this website to:

- **Netlify** (Recommended - Free)
  - Drag and drop the folder to Netlify
  - Or connect your Git repository
  
- **Vercel** (Free)
  - Connect your Git repository
  - Or use Vercel CLI

- **GitHub Pages** (Free)
  - Push to GitHub
  - Enable GitHub Pages in repository settings

- **Traditional Hosting**
  - Upload files via FTP
  - Works with any web hosting service

## File Structure

```
laundry/
├── index.html          # Homepage
├── services.html       # Services page
├── pricing.html        # Pricing page
├── how-it-works.html   # How it works page
├── booking.html        # Booking form
├── about.html          # About us page
├── faq.html            # FAQ page
├── contact.html        # Contact page
├── styles.css          # Main stylesheet
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Customization

### Colors

Edit CSS variables in `styles.css`:

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #10b981;
    --accent-color: #f59e0b;
    /* ... */
}
```

### Fonts

The website uses Google Fonts (Inter and Poppins). To change fonts:

1. Update the Google Fonts link in the `<head>` of each HTML file
2. Update the `--font-primary` and `--font-heading` variables in `styles.css`

## Features Explained

### Mobile Menu
- Hamburger menu for mobile devices
- Smooth toggle animation
- Closes when clicking outside or on a link

### FAQ Accordion
- Click to expand/collapse questions
- Only one question open at a time
- Smooth animations

### Form Validation
- Required field validation
- Service type selection validation
- Phone number pattern validation
- Email validation

### Cost Estimator
- Interactive calculator on pricing page
- Select service type and quantity
- Real-time price calculation

## Support

For questions or issues, please contact:
- Email: info@laundrydone.com
- Phone: +91 98765 43210

## License

This project is open source and available for personal and commercial use.

## Credits

- Fonts: Google Fonts (Inter, Poppins)
- Icons: Emoji (can be replaced with icon libraries like Font Awesome)
- Form Service: Formspree (or your preferred service)

---

**Note**: Remember to update all placeholder information (phone numbers, emails, addresses, form IDs) before going live!

