
## Features

### 1. **Responsive Design**
- Mobile-first approach
- Works on all screen sizes (mobile, tablet, desktop)
- Flexible grid layouts with CSS Grid and Flexbox

### 2. **Interactive Elements**
- **Project Slider**: Interactive carousel showcasing featured projects
- **Form Validation**: Contact form with real-time validation
- **Smooth Animations**: CSS animations on scroll and hover
- **Mobile Menu**: Hamburger menu for mobile devices

### 3. **JavaScript Functionality**
- **Slider Controls**: Next/previous buttons, dot indicators, keyboard navigation
- **Form Handling**: Client-side validation with error messages
- **Scroll Animations**: Elements animate when they come into view
- **Auto-sliding**: Projects slider automatically rotates every 5 seconds

### 4. **CSS Features**
- CSS Variables for consistent theming
- Gradient backgrounds and modern UI elements
- Custom animations and transitions
- Responsive typography

## How to Use

### 1. **Navigation**
- Use the navigation bar to switch between pages
- Mobile: Click hamburger menu to open navigation
- Active page is highlighted in the navigation

### 2. **Project Slider** (projects.html)
- Click next/previous buttons to navigate
- Click dot indicators to jump to specific slide
- Use keyboard arrows (left/right) for navigation
- Auto-rotates every 5 seconds (pauses on hover)

### 3. **Contact Form** (contact.html)
- All required fields are marked with *
- Real-time validation provides immediate feedback
- Success message appears on successful submission
- Form can be connected to backend service (see JavaScript comments)

### 4. **Adding Your Content**

#### Update Personal Information:
1. **index.html**: Update hero section text
2. **about.html**: Update experience, education, skills
3. **contact.html**: Update contact information
4. **projects.html**: Update project details

#### Add Images:
1. Place images in the `images/` folder
2. Update image paths in HTML files
3. Recommended: Optimize images for web

## Browser Compatibility
1. **Chrome** (latest): ✅ Fully supported
2. **Firefox** (latest): ✅ Fully supported
3. **Safari** (latest): ✅ Fully supported
4. **Edge** (latest): ✅ Fully supported
5. **Mobile Browsers**: ✅ Fully responsive

## Dependencies
- **Font Awesome 6**: For icons
- **Google Fonts**: Poppins font family
- **No external frameworks**: Pure HTML, CSS, JavaScript

## Customization

### Colors
Modify CSS variables in `style.css`:
```css
:root {
    --primary: #2563eb;
    --secondary: #7c3aed;
    --dark: #1e293b;
    --light: #f8fafc;
}