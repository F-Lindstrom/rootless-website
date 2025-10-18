# Rootless Capital - Static Website

A professional static website for Rootless Capital, a venture capital firm focused on technology startups and scaleups, especially in the financial industry.

## Features

- **Modern, Professional Design**: Clean and sophisticated layout suitable for a VC firm
- **Responsive**: Fully responsive design that works on all devices
- **Contact Form**: Functional contact form with validation
- **Smooth Animations**: Subtle animations and transitions for enhanced UX
- **SEO Optimized**: Proper meta tags and semantic HTML

## Technology Stack

- HTML5
- TailwindCSS (via CDN)
- Vanilla JavaScript
- Google Fonts (Inter)

## Font Selection

The website uses **Inter** - a professional, modern sans-serif font that is:
- Highly legible at all sizes
- Professional and clean appearance
- Widely used in fintech and enterprise applications
- Free and open-source
- Excellent for both headings and body text

**Alternative Professional Fonts** (if you want to change):
1. **Poppins** - Modern, geometric sans-serif
2. **Roboto** - Clean, neutral, professional
3. **Montserrat** - Elegant, professional, great for headings
4. **Work Sans** - Professional, slightly condensed
5. **IBM Plex Sans** - Corporate, technical feel

To change the font, update the Google Fonts link in `index.html`:
```html
<link href="https://fonts.googleapis.com/css2?family=YOUR_FONT:wght@300;400;500;600;700&display=swap" rel="stylesheet">
```

## Free Stock Photo Resources

### Recommended Sources for Professional VC/Fintech Images:

1. **Unsplash** (https://unsplash.com)
   - Free to use, no attribution required
   - High-quality professional photos
   - Search terms: "office", "business", "technology", "cityscape", "finance"
   - Current hero image is from Unsplash

2. **Pexels** (https://pexels.com)
   - Free to use, no attribution required
   - Great for business and technology imagery
   - Search terms: "corporate", "startup", "modern office", "financial district"

3. **Pixabay** (https://pixabay.com)
   - Free to use, no attribution required
   - Good selection of business images

4. **Burst by Shopify** (https://burst.shopify.com)
   - Free high-resolution photos
   - Business-focused collection

### Recommended Image Searches for Your Hero Background:

**Professional & Modern:**
- Modern office buildings/skyscrapers
- City skyline at dusk/night
- Modern architecture
- Technology/data visualization
- Professional workspace

**Specific Unsplash URLs to Try:**
1. Modern cityscape: `https://images.unsplash.com/photo-1486406146926-c627a92ad1ab`
2. Business district: `https://images.unsplash.com/photo-1449824913935-59a10b8d2000`
3. Modern office: `https://images.unsplash.com/photo-1497366216548-37526070297c`
4. Technology: `https://images.unsplash.com/photo-1451187580459-43490279c0fa`
5. Financial district: `https://images.unsplash.com/photo-1454165804606-c3d57bc86b40`

### How to Change the Background Image:

In `index.html`, find the hero section and update the `background-image` URL:

```html
<div class="absolute inset-0 bg-cover bg-center bg-no-repeat" 
     style="background-image: url('YOUR_IMAGE_URL_HERE');"></div>
```

**Tips for Choosing Images:**
- Use high-resolution images (at least 1920x1080)
- Choose images with darker areas or good contrast for text overlay
- Ensure the image aligns with your brand (professional, modern, trustworthy)
- Test on mobile devices to ensure the image scales well

## Setup Instructions

1. Simply open `index.html` in a web browser
2. No build process or dependencies required
3. All assets are loaded via CDN

## Customization

### Colors
The website uses a professional blue color scheme. To change colors, update the Tailwind classes in `index.html`:
- Primary blue: `blue-600`, `blue-500`
- Accent purple: `purple-600`
- Accent green: `green-600`

### Content
Update the following sections in `index.html`:
- Company statistics (portfolio companies, AUM, etc.)
- Investment focus areas
- Contact information in footer
- Meta description for SEO

### Contact Form
Currently, the form logs data to the console. To make it functional:
1. Set up a backend API endpoint
2. Update the form submission handler in `script.js`
3. Or use a service like Formspree, Netlify Forms, or EmailJS

**Example with Formspree:**
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

## Deployment

This static website can be deployed to:
- **Netlify**: Drag and drop the folder
- **Vercel**: Connect to GitHub repo
- **GitHub Pages**: Push to gh-pages branch
- **AWS S3**: Upload files to S3 bucket with static hosting
- Any web server: Upload files via FTP

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## License

This website template is provided as-is for Rootless Capital.

## Contact Form Integration Options

### Option 1: Formspree (Easiest)
1. Sign up at https://formspree.io
2. Create a new form
3. Update the form action in `index.html`

### Option 2: Netlify Forms
1. Deploy to Netlify
2. Add `netlify` attribute to form
3. Forms automatically work

### Option 3: Custom Backend
Implement your own API endpoint and update the fetch call in `script.js`

## Support

For questions or modifications, refer to the inline comments in the code.
