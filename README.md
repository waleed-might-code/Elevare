# Elevare - Community Landing Page

**Grow. Connect. Elevate.**

Elevare is a community platform designed for young founders, builders, and students who want to stop grinding alone and start shipping together. This landing page serves as the entry point to join our WhatsApp community where members get access to opportunities, resources, and a network of like-minded individuals.

## 🌟 Features

### Hero Section
- **Animated 3D Ring Background**: Interactive spinning ring effect powered by UnicornStudio that responds to scroll and mouse movements
- **AI Text Reveal Animation**: Smooth character-by-character and word-by-word text animations with blur effects
- **Parallax Effects**: Depth and movement as you scroll through the page
- **Grid Lines Overlay**: Subtle vertical grid lines for a modern, technical aesthetic
- **Responsive Design**: Fully optimized for desktop, tablet, and mobile devices

### Sections

1. **Hero Section**: Main call-to-action with email signup and community introduction
2. **Why This Exists**: Problem statement and value proposition
3. **What You Unlock**: Grid of 6 key benefits (Freelance Gigs, Global Access, Network, Startup Culture, Resources, Culture)
4. **How to Level Up**: Timeline showing the 3-step onboarding process
5. **Choose Your Character**: Four tracks (Freelance, Global, Startup, Network)
6. **Social Proof**: Statistics about the community
7. **FAQ**: Accordion-style frequently asked questions
8. **Final CTA**: Call-to-action to join WhatsApp

### Interactive Features

- **Dark/Light Mode Toggle**: Seamless theme switching with localStorage persistence
- **Smooth Animations**: Fade-in, slide-up, and blur effects throughout
- **Accordion FAQ**: Expandable/collapsible FAQ items with smooth transitions
- **Hover Effects**: Interactive elements respond to user interaction
- **Scroll Animations**: Elements animate into view as you scroll

## 🎨 Color Palette

The website uses a carefully curated blue color scheme:

- **Deep Navy**: `#203858` - Primary dark backgrounds
- **Mid Blue**: `#5880B0` - Accents and secondary elements
- **Light Sky**: `#A0D8F8` - CTAs, highlights, and primary actions
- **Teal-Gray**: `#386068` - Borders, subtle accents
- **Soft Gray**: `#B8B8B8` - Secondary text
- **Light Background**: `#F7FAFF` - Light mode background
- **Dark Background**: `#070B14` - Dark mode background

## 🛠️ Technical Stack

- **HTML5**: Semantic markup
- **Tailwind CSS**: Utility-first CSS framework (via CDN)
- **Lucide Icons**: Modern icon library
- **UnicornStudio**: 3D background animation library
- **Vanilla JavaScript**: No framework dependencies

### Fonts
- **Space Grotesk**: Headings
- **Inter**: Body text

## 📁 File Structure

```
elevare/
├── t.html          # Main landing page
├── logo.png        # Elevare logo
└── README.md       # This file
```

## 🚀 Getting Started

1. **Open the HTML file**: Simply open `t.html` in a modern web browser
2. **No build process required**: All dependencies are loaded via CDN
3. **Local development**: Use a local server for best results (e.g., `python -m http.server` or `npx serve`)

## 🎯 Key Functionality

### Theme Toggle
- Click the sun/moon icon in the navigation to switch between dark and light modes
- Preference is saved in localStorage
- All colors and effects adapt automatically

### WhatsApp Integration
- All CTAs link to: `https://chat.whatsapp.com/Hi6V8PWTe7M669sIKI7XcL`
- Mobile users get a sticky bottom bar for easy access

### Animations
- **Text Reveal**: Text animates in with blur and translateY effects
- **Parallax**: Elements move at different speeds on scroll
- **Fade Up Blocks**: Content fades in as it enters viewport
- **Float Animation**: Subtle floating effect on badges and icons

## 📱 Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## 🎨 Customization

### Updating Colors
Colors are defined in two places:
1. Tailwind config (lines 24-32 in `t.html`)
2. CSS custom properties in the `<style>` section

### Changing WhatsApp Link
Search and replace all instances of:
```
https://chat.whatsapp.com/Hi6V8PWTe7M669sIKI7XcL
```

### Modifying Content
All content is in semantic HTML sections. Simply edit the text within each section.

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📝 Notes

- The 3D ring effect requires an internet connection (loads UnicornStudio from CDN)
- All icons are loaded from Lucide CDN
- Tailwind CSS is loaded from CDN for easy updates
- No build step required - pure HTML/CSS/JS

## 🎯 Community Tracks

1. **Freelance Track**: For designers, developers, and writers
2. **Global Track**: For students aiming for top universities or studying abroad
3. **Startup Track**: For visionaries building MVPs or raising pre-seed
4. **Network Track**: For people who want to connect with everyone

## 📞 Contact

Join our WhatsApp community to get started:
[WhatsApp Group Link](https://chat.whatsapp.com/Hi6V8PWTe7M669sIKI7XcL)

---

**Built with ❤️ for the Elevare Community**

*Grow. Connect. Elevate.*

