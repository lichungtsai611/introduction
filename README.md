# Micron Data Scientist Portfolio Website

A professional portfolio website built with Angular 17, designed to showcase my skills and experience as a Data Scientist for job applications.

## Project Overview

This website demonstrates my professional skills, work experience, educational background, and relevant projects, with a special focus on data science and analytics capabilities. The site features a modern design, mobile responsiveness, and integration of various frontend technologies.

## Technology Stack

- **Frontend Framework**: Angular 17.3.0
- **UI Components**: Angular Material, Bootstrap 5
- **Styling**: SCSS
- **Icons**: Font Awesome
- **Routing**: Angular Router

## Development Process

The website was developed through the following phases:

1. **Planning & Design**
   - Defined content structure and navigation logic
   - Selected appropriate technology stack
   - Planned user experience and interaction design

2. **Project Setup**
   - Initialized Angular project with CLI: `ng new micron-portfolio`
   - Installed necessary packages: Bootstrap, Font Awesome
   - Configured routing and project structure

3. **Component Architecture**
   - Created page-level components (Home, Projects, About, Education, etc.)
   - Designed shared components (Navigation, Footer)
   - Implemented responsive layouts

4. **Styling & Interaction**
   - Designed and implemented SCSS styling system
   - Created animations and transition effects
   - Integrated Bootstrap components

5. **Responsive Design**
   - Used Bootstrap's grid system
   - Implemented custom media queries
   - Created adaptive layouts for all screen sizes

6. **Performance Optimization**
   - Minified CSS and JavaScript
   - Optimized image sizes and formats
   - Reduced DOM manipulations for better performance

7. **Testing & Deployment**
   - Conducted cross-browser testing
   - Verified responsive behavior
   - Built production version and deployed

## Project Structure

```
micron-portfolio/
├── src/
│   ├── app/
│   │   ├── components/              # Shared components
│   │   ├── pages/                   # Page components
│   │   │   ├── home/                # Home page
│   │   │   ├── about/               # About website page
│   │   │   ├── education/           # Education background
│   │   │   ├── experience/          # Work experience
│   │   │   ├── micron/              # Micron specific page
│   │   │   ├── projects/            # Projects showcase
│   │   │   └── skills/              # Skills showcase
│   │   ├── shared/                  # Shared resources
│   │   ├── app.routes.ts            # Application routing
│   │   └── app.config.ts            # Application config
│   ├── assets/                      # Static resources
│   └── styles.scss                  # Global styles
└── angular.json                     # Angular configuration
```

## Special Features

- **Angular Standalone Components**: Built using Angular 17's standalone architecture
- **Responsive Design**: Works on all devices from mobile to desktop
- **Smooth Animation Effects**: CSS animations enhance user experience
- **SEO Optimization**: Proper meta tags and semantic HTML structure
- **Performance Optimization**: Fast loading and smooth interactions

## Local Development

```bash
# Install dependencies
npm install

# Start development server
npm start
```

Visit `http://localhost:4200/` to view the application

## Build Project

```bash
npm run build
```

Build files will be stored in the `dist/` directory

## Contact Information

For more information or questions, please contact:

- Email: [lichungtsai611@gmail.com](mailto:lichungtsai611@gmail.com)
- GitHub: [lichungtsai611](https://github.com/lichungtsai611)

---

© 2024 Li-Chung Tsai. All rights reserved.