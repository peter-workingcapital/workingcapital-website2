# WorkingCapital HR Consulting Website

A high-converting website for WorkingCapital, an HR consulting firm targeting venture-backed startup founders. Built with Next.js, TypeScript, Tailwind CSS, and Framer Motion.

## Features

- **High-Converting Design**: Optimized for consultation bookings within 30 seconds
- **Mobile-First**: Responsive design with touch-friendly interactions
- **Performance Optimized**: Target <2s load time with lazy loading and optimized assets
- **Interactive Elements**: Animated counters, scroll-triggered effects, and smooth transitions
- **SEO Optimized**: Meta tags, structured data, and fast loading

## Tech Stack

- **Framework**: Next.js 14 with App Router
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Animations**: Framer Motion
- **Forms**: React Hook Form
- **Icons**: Lucide React

## Getting Started

### Prerequisites

- Node.js 18+ 
- npm or yarn

### Installation

1. Install dependencies:
```bash
npm install
```

2. Run the development server:
```bash
npm run dev
```

3. Open [http://localhost:3000](http://localhost:3000) in your browser.

### Build for Production

```bash
npm run build
npm start
```

## Project Structure

```
src/
├── app/
│   ├── globals.css          # Global styles and Tailwind imports
│   ├── layout.tsx           # Root layout with metadata
│   └── page.tsx             # Main page component
├── components/
│   ├── Header.tsx           # Navigation header
│   ├── Hero.tsx             # Hero section with main CTA
│   ├── ProblemSection.tsx   # Problem agitation section
│   ├── SolutionSection.tsx  # Solution overview
│   ├── ResultsDashboard.tsx # Interactive metrics
│   ├── ServiceTiers.tsx     # Service packages
│   ├── SocialProof.tsx      # Testimonials and case studies
│   ├── TeamSection.tsx      # Team member profiles
│   ├── ContactSection.tsx   # Contact form and CTA
│   └── Footer.tsx           # Footer with links and lead magnet
└── lib/                     # Utility functions
```

## Key Sections

### 1. Hero Section
- Compelling headline: "Stop Losing 15 Hours Per Week to HR Chaos"
- Primary CTA: "Get Your Free HR Assessment"
- Trust indicators and key benefits

### 2. Problem Section
- Pain point identification with cost calculator
- Interactive elements showing $2.4M+ annual cost of DIY HR

### 3. Solution Section
- Clear differentiation from competitors
- Before/after transformation scenarios

### 4. Results Dashboard
- Animated metrics: 40% faster hiring, $250K value, 90% risk reduction
- Interactive ROI calculator

### 5. Service Tiers
- Three growth-stage focused packages
- Clear pricing and deliverables

### 6. Social Proof
- Client testimonials with carousel
- Case studies and success metrics

### 7. Team Section
- Leadership profiles with credentials
- Contact information for Peter van Kersen

### 8. Contact Section
- Comprehensive contact form
- Free assessment booking
- What to expect section

## Design System

### Colors
- Primary Blue: #2563eb
- Secondary Blue: #1d4ed8
- Text Primary: #1f2937
- Text Secondary: #6b7280
- Accent: #f59e0b

### Typography
- Font: Inter (Google Fonts)
- Headings: 600, 700, 800 weights
- Body: 400, 500 weights

### Components
- Buttons: Rounded corners, hover effects, consistent sizing
- Cards: Clean borders, hover lift effects
- Forms: Focus states, validation styling
- Icons: Lucide React, consistent sizing

## Performance Optimizations

- Lazy loading for images below fold
- Optimized image formats (WebP with fallbacks)
- Minimal JavaScript bundles
- Critical CSS inlined
- Fast Google Fonts loading

## SEO Features

- Meta tags for startup HR consulting
- Structured data for local business
- Open Graph tags for social sharing
- Fast loading and mobile-friendly
- Semantic HTML structure

## Conversion Optimization

- Multiple CTAs throughout the page
- Trust signals and social proof
- Clear value proposition
- Risk-free offers (free assessment)
- Mobile-optimized forms

## Contact Information

- **Phone**: +34 627 71 7137
- **Email**: peter@workingcapitalou.com
- **Website**: workingcapitalou.com

## License

Private project for WorkingCapital HR Consulting.
