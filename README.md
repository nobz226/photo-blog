# Through My Lens - Urban Photography Blog

https://nobz226.github.io/photo-blog/

A modern, responsive photography blog showcasing urban street photography from Vancouver, Canada. Built with semantic HTML5, CSS3 Grid, and smooth animations to create an engaging visual experience.

## About

"Through My Lens" is a personal photography blog featuring raw urban photography that captures the soul of Vancouver's city streets. The site presents a curated collection of street photography, architectural shots, and urban landscapes through an elegant, minimalist design.

## Design Features

### **Typography**
- **Primary Font**: Cal Sans - Used for headings and prominent text
- **Secondary Font**: Funnel Sans - Used for body text and descriptions
- **Font Weights**: 300-800 range with italic support
- **Responsive sizing**: Scales appropriately across all devices

### **Color Palette**
- **Primary Purple**: `#d04bd8` - Brand color for accents and interactive elements
- **Dark Gray**: `#36352c` - Main text color
- **Bright Yellow**: `#ffe43b` - Accent color for highlights
- **Azure Background**: Light blue background for clean contrast

### **Layout System**
- **CSS Grid**: 12-column responsive grid system
- **Grid Template Areas**: Used for gallery layout with named grid areas
- **Flexbox**: For navigation, buttons, and component alignment
- **Container**: Max-width 80rem with responsive padding

## Animations

### **FadeInUp Animation**
- **Duration**: 3 seconds for elegant, slow reveals
- **Staggered Timing**: Elements appear in sequence with incremental delays
- **Easing**: CSS ease function for natural movement
- **Implementation**: Applied to all major content sections

### **Hover Effects**
- **Image Scaling**: `transform: scale(1.05)` on image hover
- **Container Lift**: `translateY(-2px)` with enhanced shadows
- **Opacity Changes**: Subtle transparency shifts for interactivity
- **Purple Text Overlay**: "Click to open in new window" appears on image hover

### **Transitions**
- **Duration**: 0.3s for smooth, responsive interactions
- **Properties**: Transform, opacity, box-shadow
- **Timing**: CSS ease for natural feel

## Interactive Elements

### **Clickable Images**
- All gallery and blog post images open full-size in new windows
- Purple hover text indicates clickability
- Smooth scaling and shadow effects

### **Navigation**
- Fixed header with logo and menu
- Responsive hamburger menu (CSS-only)
- Active state styling

### **Buttons**
- Consistent styling across all pages
- Hover effects with color transitions
- Accessible focus states

## Performance Features

- **Optimized Images**: Proper aspect ratios and object-fit
- **Efficient CSS**: No unused styles, optimized selectors
- **Font Loading**: Preconnect to Google Fonts for faster loading
- **Minimal Dependencies**: No external JavaScript libraries

## Customization

### **Colors**
Update CSS custom properties in `:root`:
```css
:root {
    --purple: #d04bd8;
    --dark: #36352c;
    --yellow: #ffe43b;
}
```

### **Typography**
Change font families in CSS variables:
```css
:root {
    --primary: "Cal Sans", sans-serif;
    --secondary: "Funnel", sans-serif;
}
```

### **Layout**
Adjust grid columns and breakpoints in media queries for different layouts.

## Responsive Design

### **Mobile First Approach**
- **Mobile (≤600px)**: Single column layout, touch-friendly interactions
- **Tablet (768px+)**: Two-column grid, enhanced spacing
- **Desktop (1200px+)**: Three-column grid, optimal viewing experience

### **Breakpoints**
```css
/* Mobile */
@media screen and (max-width: 600px)

/* Tablet */
@media screen and (min-width: 768px)

/* Desktop */
@media screen and (min-width: 1200px)
```

## Technical Implementation

### **Structure**
```
photo-blog/
├── index.html          # Homepage with hero and post previews
├── gallery.html        # Photo gallery with overlay text
├── posts.html          # Individual blog post page
├── about.html          # About page with timeline
├── css/
│   ├── reset.css       # CSS reset for consistency
│   └── styles.css      # Main stylesheet
└── images/             # Photography assets
```

### **Key Technologies**
- **HTML5**: Semantic markup with proper accessibility
- **CSS3**: Grid, Flexbox, Custom Properties, Animations
- **CSS Custom Properties**: For consistent theming
- **No JavaScript**: Pure CSS animations and interactions

### **CSS Architecture**
- **Component-based**: Modular CSS with clear naming conventions
- **BEM-inspired**: Block__Element--Modifier naming pattern
- **Mobile-first**: Progressive enhancement for larger screens
- **Animation System**: Consistent timing and easing across components

## Pages & Features

### **Homepage (`index.html`)**
- Hero banner with animated text overlay
- Personal introduction section
- Blog post previews with hover effects
- Smooth scroll animations

### **Gallery (`gallery.html`)**
- Grid-based photo layout using CSS Grid Template Areas
- Click-to-expand functionality (opens images in new window)
- Overlay text with photo titles and locations
- Staggered reveal animations

### **Blog Post (`posts.html`)**
- Featured image with clickable functionality
- Inline images with consistent hover effects
- Photo gallery at bottom
- Professional typography and spacing

### **About (`about.html`)**
- Personal story and photography approach
- Timeline layout for experience
- Contact information cards
- Call-to-action buttons

## How to Run

### **Local Development**
1. Clone or download the project files from:
https://github.com/nobz226/photo-blog.git
2. Open `index.html` in your web browser
3. No build process required - pure HTML/CSS

### **Live Server (Recommended)**
If using VS Code with Live Server extension:
1. Right-click on `index.html`
2. Select "Open with Live Server"
3. View at `http://127.0.0.1:5500`


**Built with ❤️ for a BCIT Assignment**