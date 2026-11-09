# Vaibhav Giridhar - Portfolio Website

A modern, responsive portfolio website built with React.js and GSAP animations, showcasing the work and skills of Vaibhav Giridhar, a Full Stack Developer.

## 🚀 Features

- **Modern Design**: Clean, professional design with glassmorphism effects
- **Dark/Light Mode**: Toggle between dark and light themes with smooth transitions
- **Profile Photo**: Animated profile photo with fallback placeholder
- **Smooth Animations**: GSAP-powered animations and scroll triggers
- **Responsive Layout**: Fully responsive design that works on all devices
- **Interactive Elements**: Hover effects, smooth scrolling, and animated components
- **Contact Form**: Functional contact form for inquiries
- **Performance Optimized**: Fast loading and smooth performance
- **Theme Persistence**: Remembers user's theme preference

## 🛠️ Technologies Used

- **React.js** - Frontend framework
- **GSAP** - Animation library
- **CSS3** - Styling with modern features and CSS variables
- **React Icons** - Icon library
- **Context API** - Theme management
- **Local Storage** - Theme persistence
- **Responsive Design** - Mobile-first approach

## 📋 Sections

1. **Hero Section** - Introduction with animated profile photo, text and social links
2. **About** - Personal information and statistics
3. **Skills** - Technical skills with animated progress bars
4. **Experience** - Work experience and education
5. **Projects** - Featured projects with detailed descriptions
6. **Contact** - Contact form and information
7. **Footer** - Additional links and information

## 🎨 Theme Features

### Dark Mode (Default)
- Dark backgrounds with blue gradients
- White/light gray text
- Glassmorphism effects with dark overlays

### Light Mode
- Light backgrounds with subtle gradients
- Dark text for better readability
- Glassmorphism effects with light overlays

### Theme Toggle
- Sun/Moon icon in the navbar
- Smooth transitions between themes
- Automatic theme persistence using localStorage

## 🖼️ Profile Photo Setup

1. Add your profile photo to the `public` folder as `profile-photo.jpg`
2. The component includes automatic fallback to initials if photo fails to load
3. Photo is automatically cropped to circular shape with gradient border
4. Includes floating animation for visual appeal

## 🚀 Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn package manager

### Installation

1. Clone the repository:
```bash
git clone https://github.com/giridharvaibhav042000/portfolio.git
cd portfolio
```

2. Install dependencies:
```bash
npm install
```

3. Add your profile photo:
   - Place your profile photo in the `public` folder
   - Name it `profile-photo.jpg`
   - Recommended size: 400x400px or larger (square aspect ratio)

4. Start the development server:
```bash
npm start
```

5. Open your browser and visit `http://localhost:3000`

### Building for Production

```bash
npm run build
```

This creates a `build` folder with optimized production files.

## 📱 Responsive Design

The portfolio is fully responsive and optimized for:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (320px - 767px)

## 🎨 Customization

### Colors
The theme system uses CSS variables for easy customization:

**Dark Theme:**
- Primary: `#4a90e2` (Blue)
- Secondary: `#7b68ee` (Purple)
- Background: `#0a0a0a` (Dark)
- Text: `#ffffff` (White)

**Light Theme:**
- Primary: `#4a90e2` (Blue)
- Secondary: `#7b68ee` (Purple)
- Background: `#ffffff` (White)
- Text: `#212529` (Dark)

### Animations
GSAP animations are configured in each component with:
- Scroll triggers for section reveals
- Staggered animations for lists
- Hover effects for interactive elements
- Profile photo entrance animation

### Theme Customization
Edit CSS variables in `src/index.css`:
```css
:root {
  --accent-primary: #your-color;
  --accent-secondary: #your-color;
  /* ... other variables */
}
```

## 📧 Contact

- **Email**: giridharvaibhav04@gmail.com
- **Phone**: +91 9764294317
- **LinkedIn**: [vaibhavgiridhar04](https://www.linkedin.com/in/vaibhavgiridhar04/)
- **Location**: Vasco, Goa, India

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/giridharvaibhav042000/portfolio/issues).

---

Made with ❤️ by Vaibhav Giridhar