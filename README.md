### Coffee Cafe – Modern Coffee Shop Website

A responsive, modern coffee shop landing site built with React and Vite. It showcases hero messaging, featured services, an about/banner section, app store callouts, customer testimonials, and a themed footer. Animations are powered by AOS and the testimonial carousel uses react-slick.

### Features
- **Hero section**: Bold headline, CTA, and animated imagery
- **Services**: Espresso, Americano, Cappuccino cards with hover effects
- **About/Banner**: Premium blend description with icon highlights
- **App Store**: iOS/Android badges section
- **Testimonials**: Auto-playing, responsive carousel
- **Footer**: Quick links and social icons over a branded background

### Tech Stack
- **Frontend**: React 18, Vite
- **Styling**: Tailwind CSS
- **Animations**: AOS (Animate On Scroll)
- **Icons**: react-icons
- **Carousel**: react-slick + slick-carousel

### Getting Started
1. **Install dependencies**
   ```bash
   npm install
   ```
2. **Run the dev server**
   ```bash
   npm run dev
   ```
3. **Build for production**
   ```bash
   npm run build
   ```
4. **Preview the production build**
   ```bash
   npm run preview
   ```

### Project Structure
```text
coffe-shop/
  src/
    components/
      Navbar/      # Top navigation
      Hero/        # Landing hero section
      Services/    # Coffee offerings
      Banner/      # About/premium blend section
      AppStore/    # Store badges CTA
      Testimonials/# Customer reviews
      Footer/      # Footer with links & socials
    assets/        # Images and backgrounds
    App.jsx        # Composes all sections
    main.jsx       # App bootstrap
  tailwind.config.js
  postcss.config.js
  vite.config.js
```

### Customization Tips
- Update copy in `src/components/**` to reflect your shop name, address, and pricing.
- Replace images in `src/assets/**` with your brand visuals.
- Tailwind theme colors can be adjusted in `tailwind.config.js`.
