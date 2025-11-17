# TruePrimeWeb

## Introduction

TruePrimeWeb is the official full-stack website for True Prime Digital LLC. This project represents a comprehensive web development solution that integrates full-stack web development, full-stack application development, and digital marketing services.

The project architecture consists of:

- **Frontend**: HTML5, CSS3, and Vanilla JavaScript
- **Backend**: Node.js + Express API (maintained in separate repository)
- **Database**: MongoDB Atlas (managed at API level)
- **Marketing Tools**: Google Analytics 4 (GA4), Google Tag Manager (GTM)
- **Business Service Landing Pages**: Comprehensive service pages for digital marketing and development services

This repository contains the frontend codebase, which is a production-ready, SEO-optimized static website that connects to external backend APIs for dynamic functionality such as contact form submissions.

## Pages

The website consists of the following HTML pages:

### Core Pages

- **index.html** - Homepage featuring company overview, services, and primary call-to-action sections
- **about.html** - Company information, mission, and team details
- **contact.html** - Contact page with form connected to backend API for submission handling
- **services.html** - Main services overview page listing all available services

### Service Landing Pages

- **full-stack-app-development.html** - Full-stack application development services
- **web-development.html** - Web development and design services
- **seo-optimization.html** - Search engine optimization services
- **local-seo.html** - Local SEO services for businesses
- **ppc-ads.html** - Pay-per-click advertising and Google Ads management
- **social-media-marketing.html** - Social media marketing and management services
- **email-marketing-automation.html** - Email marketing and automation solutions
- **digital-marketing-consulting.html** - Digital marketing consulting services
- **conversion-rate-optimization-cro.html** - Conversion rate optimization services
- **analytics-data-tracking.html** - Analytics and data tracking services
- **data-systems-automation.html** - Data systems automation and CRM integration services

### Legal and Policy Pages

- **privacy.html** - Privacy policy and data handling information
- **terms-of-service.html** - Terms of service and usage agreements
- **cookie-policy.html** - Cookie policy and tracking information
- **copyright-notice.html** - Copyright notice and intellectual property information

### Technical Files

- **sitemap.xml** - XML sitemap for search engine indexing
- **.htaccess** - Apache server configuration for URL redirects and hosting rules

## Tech Stack

### Frontend

- **HTML5** - Semantic markup and structure
- **CSS3** - Modern styling with custom properties, flexbox, and grid layouts
- **JavaScript (Vanilla JS)** - Client-side interactivity without framework dependencies

### Backend (External Repositories)

- **Node.js** - JavaScript runtime environment
- **Express.js** - Web application framework for API endpoints
- **MongoDB Atlas** - Cloud-hosted NoSQL database

### Tools and Integrations

- **Google Analytics 4 (GA4)** - Web analytics and user behavior tracking
- **Google Tag Manager (GTM)** - Tag management and marketing tool integration
- **SEO Metadata** - Comprehensive meta tags, Open Graph, and Twitter Card support
- **Alt Tags** - Accessibility-focused image descriptions
- **.htaccess** - Apache server rules for URL redirects and hosting configuration

## Features

- **Fully Responsive Design** - Mobile-first approach ensuring optimal display across all devices
- **Complete Service Landing Pages** - Dedicated pages for each service offering with detailed information
- **SEO-Optimized Structure** - Semantic HTML, meta tags, structured data, and XML sitemap
- **Production-Ready Sitemap** - Comprehensive sitemap.xml including all pages with appropriate priorities
- **GA4 + GTM Tracking** - Integrated analytics and tag management for marketing insights
- **Backend-Connected Contact Page** - Contact form integrated with Node.js/Express API
- **Full-Stack Architecture** - Separation of concerns with frontend and backend in distinct repositories
- **Performance Optimized** - Optimized assets, efficient CSS, and minimal JavaScript dependencies

## Folder Structure

```
TruePrimeWeb/
├── docs/                          # Documentation and screenshots
├── images/                        # Image assets
│   ├── founder-mory-trueprime.jpg
│   └── hero.png
├── .htaccess                      # Apache server configuration
├── .gitignore                     # Git ignore rules
├── LICENSE                        # MIT License
├── README.md                      # Project documentation
├── sitemap.xml                    # XML sitemap for SEO
├── apple-touch-icon.png           # Apple touch icon
├── favicon.ico                    # Favicon
├── favicon-32x32.png             # 32x32 favicon
├── favicon-192x192.png           # 192x192 favicon
├── index.html                     # Homepage
├── about.html                     # About page
├── contact.html                   # Contact page
├── services.html                  # Services overview
├── full-stack-app-development.html
├── web-development.html
├── seo-optimization.html
├── local-seo.html
├── ppc-ads.html
├── social-media-marketing.html
├── email-marketing-automation.html
├── digital-marketing-consulting.html
├── conversion-rate-optimization-cro.html
├── analytics-data-tracking.html
├── data-systems-automation.html
├── privacy.html
├── terms-of-service.html
├── cookie-policy.html
└── copyright-notice.html
```

## Installation

### Prerequisites

- A web browser (Chrome, Firefox, Safari, Edge)
- A local web server (optional, for development)

### Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/TruePrimeWeb.git
   cd TruePrimeWeb
   ```

2. Open the project:
   - For local development, open `index.html` directly in a web browser
   - For production-like testing, use a local web server:
     ```bash
     # Using Python 3
     python3 -m http.server 8000
     
     # Using Node.js http-server
     npx http-server
     
     # Using PHP
     php -S localhost:8000
     ```

3. Access the website:
   - Direct file: `file:///path/to/TruePrimeWeb/index.html`
   - Local server: `http://localhost:8000`

## Deployment

### GitHub Pages

1. Push the repository to GitHub
2. Navigate to repository Settings > Pages
3. Select the main branch as the source
4. The site will be available at `https://yourusername.github.io/TruePrimeWeb/`

### Cloudways

1. Connect your repository to Cloudways via Git
2. Configure the web root to point to the repository root
3. Ensure `.htaccess` rules are properly configured
4. Deploy and verify URL redirects are working

### Other Static Hosts

This project can be deployed to any static hosting service:

- **Netlify**: Connect repository, set build command to empty, publish directory to root
- **Vercel**: Connect repository, framework preset to "Other", output directory to root
- **AWS S3 + CloudFront**: Upload files to S3 bucket, configure CloudFront distribution
- **Apache/Nginx**: Upload files to web root, ensure `.htaccess` is respected (Apache) or configure equivalent rules (Nginx)

### Important Notes

- Ensure `.htaccess` file is included in deployment (required for URL redirects)
- Verify all image paths are correct after deployment
- Test contact form API endpoints are accessible from production domain
- Update CORS settings in backend API if deploying to a new domain

## About the Developer

The developer is a self-taught full-stack web developer with expertise in:

- Full-stack web development
- Full-stack application development
- React Native mobile app development
- Node.js + Express backend development
- MongoDB database design and cloud hosting
- Modern frontend technologies and best practices

## Related Repositories

- **TruePrimeApp** - React Native mobile application repository
  - Repository: [TruePrimeApp](https://github.com/yourusername/TruePrimeApp)

- **TruePrimeBackend** - Node.js + Express API backend repository
  - Repository: [TruePrimeBackend](https://github.com/yourusername/TruePrimeBackend)

## Official Website

- **Live Site**: [https://trueprimedigital.com](https://trueprimedigital.com)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Copyright (c) 2025 True Prime Digital LLC

