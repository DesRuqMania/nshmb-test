# Nasarawa State Hospitals Management Board - Static HTML Site

This is a complete static HTML export of the Nasarawa State Hospitals Management Board (NSHMB) website.

## Overview

The website showcases the NSHMB's mission, vision, management staff, and healthcare services. It is built as a responsive, single-page application that works entirely in the browser without requiring a backend server.

## Contents

- **index.html** - Main website file (all content is embedded)
- **assets/** - CSS and JavaScript files for styling and interactivity
- **__manus__/** - Analytics tracking files

## How to Use

### Option 1: Direct Browser Access
Simply open `index.html` in any modern web browser. The site will load completely with all styling and functionality.

### Option 2: Local Web Server
For better performance and to avoid CORS issues, serve the files using a local web server:

```bash
# Using Python 3
python3 -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js (http-server)
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit: `http://localhost:8000`

### Option 3: Deploy to Web Hosting
Upload all files to your web hosting provider:
1. Upload the entire directory to your hosting account
2. Ensure the web server is configured to serve `index.html` as the default document
3. Access your domain in a browser

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Professional Layout**: Clean, modern interface with green color scheme (NSHMB branding)
- **Navigation**: Easy access to sections: About, Management, Services, and Contact
- **Management Directory**: Complete listing of NSHMB management staff with titles
- **Contact Information**: Address, email, and website details
- **No Dependencies**: Completely self-contained; no external API calls required

## Sections

1. **Navigation Bar** - Quick access to all major sections
2. **Hero Section** - Welcome message and call-to-action
3. **Vision & Mission** - NSHMB's strategic statements
4. **Services** - Overview of healthcare services offered
5. **Management Staff** - Directory of key personnel
6. **Contact Section** - Location and contact details
7. **Footer** - Copyright information

## Technical Details

- **Framework**: React 19 with Tailwind CSS 4
- **Styling**: Tailwind CSS with custom green color scheme
- **Typography**: Poppins font family
- **Build Tool**: Vite
- **Browser Support**: All modern browsers (Chrome, Firefox, Safari, Edge)

## Customization

To modify the site:

1. **Content**: Edit the text directly in the HTML file using a text editor
2. **Colors**: Look for `text-green-700`, `bg-green-700`, etc. in the HTML and change to desired colors
3. **Contact Info**: Update the contact section with current information
4. **Staff Directory**: Modify the management staff list in the HTML

## File Structure

```
nshmb_static_export/
├── index.html              # Main website (all content embedded)
├── assets/
│   ├── index-*.css         # Compiled CSS styles
│   └── index-*.js          # Compiled JavaScript
├── __manus__/              # Analytics files
└── README.md               # This file
```

## Performance

- **Page Size**: ~360 KB (fully self-contained)
- **Load Time**: Typically < 2 seconds on standard connections
- **Caching**: Browser caching is enabled for optimal repeat visits

## Support & Maintenance

For updates or modifications to the website:
- Contact: contact@hmb.na.gov.ng
- Website: https://hmb.na.gov.ng

## License

© 2026 Nasarawa State Hospitals Management Board. All Rights Reserved.

---

**Generated**: March 4, 2026
**Format**: Static HTML/CSS/JavaScript
**Version**: 1.0
