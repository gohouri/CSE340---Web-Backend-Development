# CSE Motors - Car Dealership Website

## Overview
This is a web application for CSE Motors, a fictitious car dealership. The application is built using Node.js, Express, and EJS templating engine.

## Features
- Responsive design that works on both mobile and desktop devices
- Mobile-first CSS approach with media queries for larger screens
- EJS partials for modular code structure
- Professional color scheme with accessibility considerations
- Semantic HTML5 structure

## Project Structure
```
CSE340---Web-Backend-Development/
├── app.js                 # Main Express application
├── package.json           # Node.js dependencies
├── views/                 # EJS template files
│   ├── index.ejs         # Main page template
│   └── partials/         # Reusable template parts
│       ├── head.ejs      # Head section
│       ├── header.ejs    # Site header
│       ├── navigation.ejs # Navigation menu
│       └── footer.ejs    # Site footer
├── public/                # Static assets
│   ├── css/              # Stylesheets
│   │   └── styles.css    # Main CSS file
│   └── images/           # Image assets
│       ├── delorean.svg  # Main car image
│       ├── flux-capacitor.svg
│       ├── flame-decals.svg
│       ├── bumper-stickers.svg
│       └── hub-caps.svg
└── README.md             # This file
```

## Installation and Setup

### Prerequisites
- Node.js (version 14 or higher)
- npm (comes with Node.js)

### Installation Steps
1. Clone or download this repository
2. Navigate to the project directory
3. Install dependencies:
   ```bash
   npm install
   ```

### Running the Application

#### Development Mode
```bash
npm run dev
```
This will start the server with nodemon for automatic restarts during development.

#### Production Mode
```bash
npm start
```
This will start the server normally.

The application will be available at `http://localhost:3000`

## Technical Details

### Frontend Technologies
- **HTML5**: Semantic markup with proper accessibility attributes
- **CSS3**: Mobile-first responsive design with media queries
- **EJS**: Server-side templating with partials

### Responsive Design
- **Mobile-first approach**: Base styles are for mobile devices
- **Media queries**: Two breakpoints at 768px and 1024px
- **Flexbox and Grid**: Modern CSS layout techniques
- **No horizontal scrolling**: Content adapts to screen size

### Accessibility Features
- Semantic HTML structure
- Proper alt text for images
- High contrast color scheme
- Keyboard navigation support
- Screen reader friendly markup

### Color Scheme
- Primary: Blue (#3b82f6, #1e3a8a)
- Background: White (#ffffff) and light gray (#f8fafc)
- Text: Dark gray (#1f2937, #333)
- Accents: Blue variations for interactive elements

## Browser Support
- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile browsers (iOS Safari, Chrome Mobile)
- Responsive design ensures compatibility across devices

## Deployment
This application is designed to be deployed to platforms like:
- Render.com
- Heroku
- Vercel
- Any Node.js hosting platform

## Assignment Requirements Met
✅ HTML5 semantic structure with EJS partials  
✅ Mobile-first CSS with media queries  
✅ Responsive design without horizontal scrolling  
✅ Professional color scheme and typography  
✅ Accessibility considerations  
✅ External CSS file with media="screen" attribute  
✅ Valid HTML5 and CSS3 code  

## License
MIT License - This is an educational project for CSE 340 Web Backend Development.