# 3N Engineering & Digital Solutions Website

Professional website for 3N Engineering & Digital Solutions - a team of engineers specializing in Network, Software, and Industrial Engineering.

## Features

- **Hero Section** - Eye-catching introduction with tagline
- **Who We Are** - Overview of the three engineering disciplines
- **What We Do** - Comprehensive service offerings
- **Our Approach** - 4-step methodology for project delivery
- **Case Examples** - Portfolio of completed projects
- **Team Section** - Meet the three team leads
- **Contact Section** - Contact form and information
- **Professional Design** - Clean, modern, and engineering-focused aesthetic

## Tech Stack

- **Framework**: Nuxt.js 3
- **Styling**: Tailwind CSS
- **Language**: TypeScript
- **Icons**: Inline SVG icons

## Setup

### Prerequisites

- Node.js 18+ 
- npm or yarn

### Installation

1. Navigate to the project directory:
```bash
cd /Users/dev_nack/Desktop/3n
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:3000`

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run generate` - Generate static site

## Project Structure

```
3n/
├── app.vue                 # Main app component
├── components/             # Vue components
│   ├── Header.vue
│   ├── HeroSection.vue
│   ├── WhoWeAre.vue
│   ├── WhatWeDo.vue
│   ├── OurApproach.vue
│   ├── CaseExamples.vue
│   ├── TeamSection.vue
│   ├── ContactSection.vue
│   └── Footer.vue
├── assets/
│   └── css/
│       └── main.css        # Tailwind CSS configuration
├── nuxt.config.ts          # Nuxt configuration
├── tailwind.config.ts      # Tailwind configuration
└── package.json            # Dependencies
```

## Customization

### Colors
Edit the color scheme in `tailwind.config.ts` under the `theme.extend.colors` section.

### Contact Information
Update contact details in `components/ContactSection.vue`:
- Email: `info@3nengineering.com`
- Phone: `+66 (0) XX-XXX-XXXX`
- Address: `Bangkok, Thailand`

### Team Information
Modify team member details in `components/TeamSection.vue`

### Services
Update service descriptions in `components/WhatWeDo.vue`

## Deployment

### Deploy to Netlify

1. Push your code to a Git repository (GitHub, GitLab, etc.)
2. Connect your repository to Netlify
3. Set build command: `npm run build`
4. Set publish directory: `.output/public`

### Deploy to Vercel

1. Push your code to GitHub
2. Import project in Vercel dashboard
3. Vercel will auto-detect Nuxt and configure build settings

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

All rights reserved © 2024 3N Engineering & Digital Solutions

## Support

For questions or issues, contact: info@3nengineering.com
# 3n
