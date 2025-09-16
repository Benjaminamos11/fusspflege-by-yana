# Fusspflege by Yana - Modern Homepage

A elegant, responsive homepage for a professional foot care and manicure studio, built with Astro and Tailwind CSS.

## 🌟 Features

- **Modern Design**: Clean, minimalist spa-like aesthetics with warm gold accents
- **Responsive Layout**: Fully optimized for desktop, tablet, and mobile devices
- **German Content**: All content localized for German-speaking audience
- **Interactive Elements**: 
  - Smooth scrolling navigation
  - Testimonials carousel
  - Hover effects and animations
  - Professional contact form
- **Performance**: Built with Astro for optimal loading speeds
- **SEO Ready**: Proper meta tags and semantic HTML structure

## 🎨 Design System

- **Primary Color**: Elegant Gold (#D4AF37)
- **Background**: Off-white (#F5F5F5) 
- **Text**: Dark Grey (#333333)
- **Typography**: 
  - Headers: Montserrat (300-700 weights)
  - Body: Lato (300-700 weights)

## 📋 Sections

1. **Hero Section**: Full-screen with video background placeholder and prominent CTA
2. **Services**: Fusspflege and Maniküre service cards with descriptions
3. **About**: Professional introduction to Yana with portrait placeholder
4. **Testimonials**: Interactive carousel with customer reviews
5. **Studio Gallery**: Showcase of studio environment with hover effects
6. **Contact & Booking**: Contact information, form, and map placeholder

## 🚀 Getting Started

### Prerequisites
- Node.js (v18 or higher)
- npm or yarn

### Installation & Development

1. **Install dependencies:**
   ```bash
   npm install
   ```

2. **Start development server:**
   ```bash
   npm run dev
   ```

3. **Open your browser:**
   Navigate to `http://localhost:4321`

### Build for Production

```bash
npm run build
```

The built files will be in the `dist/` folder, ready for deployment to any static hosting service.

## 📁 Project Structure

```
/
├── public/
│   └── favicon.svg          # Custom favicon with foot care theme
├── src/
│   ├── layouts/
│   │   └── Layout.astro     # Main layout with fonts, SEO, and animations
│   └── pages/
│       └── index.astro      # Homepage with all sections
├── astro.config.mjs         # Astro configuration
├── tailwind.config.mjs      # Tailwind CSS configuration
├── tsconfig.json            # TypeScript configuration
└── package.json             # Dependencies and scripts
```

## 🎯 Customization

### Content Updates
- Edit German text content in `/src/pages/index.astro`
- Replace placeholder contact information with real details
- Update testimonials with actual customer reviews

### Images & Media
- Replace emoji placeholders with professional photos
- Add background video to hero section
- Include high-quality studio and service images
- Add Google Maps embed for location

### Styling
- Modify colors in `tailwind.config.mjs`
- Adjust animations and transitions in the Layout component
- Customize typography and spacing as needed

### Functionality
- Connect contact form to email service (e.g., Netlify Forms, Formspree)
- Integrate booking system or calendar
- Add social media links
- Implement analytics tracking

## 🌐 Browser Support

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## 📱 Responsive Breakpoints

- **Mobile**: < 640px
- **Tablet**: 640px - 1024px  
- **Desktop**: 1024px+
- **Large Desktop**: 1280px+

## 💡 Development Notes

- The project uses TypeScript for better development experience
- All animations are optimized for performance
- Images are loaded with proper aspect ratios to prevent layout shift
- Smooth scrolling is implemented for better user experience
- The design follows modern web accessibility guidelines

## 🚀 Deployment

This project can be deployed to:
- **Netlify**: Connect your Git repository for automatic deployments
- **Vercel**: Push to GitHub and connect with Vercel
- **GitHub Pages**: Enable in repository settings
- **Any Static Host**: Upload the `dist/` folder after running `npm run build`

## 📞 Support

For questions about implementation or customization, refer to:
- [Astro Documentation](https://docs.astro.build/)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)

---

*Built with ❤️ using Astro and Tailwind CSS*
