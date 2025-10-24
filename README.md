# REM Detailing - Business Website

A modern, responsive static website for REM Detailing auto services business.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Contact Form**: Functional contact form with validation
- **Image Gallery**: Interactive lightbox gallery for showcasing work
- **Service Showcase**: Detailed service cards with pricing
- **SEO Optimized**: Proper meta tags and semantic HTML

## Sections

1. **Hero Section**: Eye-catching introduction with call-to-action buttons
2. **Services**: Three main service packages with features and pricing
3. **About**: Company information with statistics and team photo
4. **Gallery**: Image showcase of completed work
5. **Contact**: Contact information and functional contact form

## Customization

### Update Business Information
Edit the following in `index.html`:
- Company name and branding
- Contact information (phone, email, address)
- Business hours
- Service descriptions and pricing
- Social media links

### Add Your Images
Replace placeholder images in the `images/` folder:
- `hero-car.jpg` - Main hero section image
- `about-team.jpg` - Team or business photo
- `gallery-1.jpg` to `gallery-6.jpg` - Work showcase images

### Styling
All styles are in `styles.css`. Key customization areas:
- Color scheme (search for color variables)
- Fonts (currently using Inter from Google Fonts)
- Layout spacing and sizing

## Technologies Used

- HTML5
- CSS3 (Flexbox, Grid, Animations)
- Vanilla JavaScript
- Font Awesome Icons
- Google Fonts

## Browser Support

- Chrome/Safari/Edge: Latest 2 versions
- Firefox: Latest 2 versions
- Mobile browsers: iOS Safari, Chrome Mobile

## Deployment

This is a static website that can be deployed to:
- Netlify
- Vercel
- GitHub Pages
- Any static hosting service

Simply upload all files to your hosting provider.

## Local Development

1. Open `index.html` in a web browser
2. For live reloading, use a local server:
   ```bash
   python -m http.server 8000
   # or
   npx live-server
   ```

## Contact Form

The contact form includes client-side validation. For production use, you'll need to:
1. Set up a backend service to handle form submissions
2. Configure email sending (using services like EmailJS, Netlify Forms, or custom backend)
3. Update the form action in `script.js`

## License

This template is free to use for personal and commercial projects.
