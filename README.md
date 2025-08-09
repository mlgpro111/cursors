# Shy Days - Modern Portfolio Website

A fully responsive, modern portfolio website recreated from your Framer design with extensive mobile and tablet optimizations.

## 🌟 Features

### 📱 **Mobile-First Design**
- **Optimized for all screen sizes**: From 320px to 1920px+
- **Touch-friendly navigation**: Swipe gestures and improved touch targets
- **Mobile-specific layouts**: Stacked layouts on mobile, grid on larger screens
- **Viewport height fixes**: Handles mobile browser navigation bars properly

### 🎨 **Modern Design Elements**
- **Gradient backgrounds**: Beautiful gradient overlays and button effects
- **Smooth animations**: Subtle parallax effects and scroll animations
- **Card-based layout**: Modern project cards with hover effects
- **Typography**: Inter font family for clean, readable text

### 🎯 **Responsive Breakpoints**
- **Mobile Small**: 320px - 480px
- **Mobile Large**: 481px - 767px  
- **Tablet**: 768px - 1024px
- **Desktop**: 1024px+
- **Landscape Mobile**: Special optimizations for landscape orientation

### ⚡ **Performance Optimized**
- **Lightweight**: Minimal CSS and JavaScript
- **Fast loading**: Optimized images and efficient code
- **Smooth scrolling**: Hardware-accelerated transitions
- **Accessible**: WCAG compliant with proper focus states

## 📋 **Sections Included**

1. **Hero Section**: Eye-catching introduction with call-to-action buttons
2. **About Section**: Personal introduction and skills overview
3. **Projects Section**: Portfolio showcase with project cards
4. **Contact Section**: Contact form and social links
5. **Navigation**: Fixed header with mobile hamburger menu

## 🛠 **Mobile Optimizations**

### Navigation
- **Hamburger menu**: Smooth slide-in navigation on mobile
- **Swipe gestures**: Swipe right from left edge to open menu, swipe left to close
- **Outside click**: Tap outside menu to close
- **Body scroll lock**: Prevents background scrolling when menu is open

### Typography & Spacing
- **Scalable text**: Font sizes adapt perfectly to screen size
- **Improved readability**: Optimized line heights and spacing
- **Touch targets**: Buttons and links meet 44px minimum touch target size

### Forms
- **Mobile-friendly inputs**: Proper input types and sizes
- **Zoom prevention**: Font-size optimizations to prevent iOS zoom
- **Focus handling**: Smooth scrolling to focused inputs on mobile

### Performance
- **Reduced animations**: Simplified effects on mobile for better performance
- **Touch feedback**: Visual feedback for touch interactions
- **Orientation support**: Adapts to portrait/landscape changes

## 🎨 **Customization Options**

### Colors
The website uses CSS custom properties. Main colors can be changed by modifying:
```css
:root {
  --primary-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  --background-light: #f5f7fa;
  --text-primary: #333;
  --text-secondary: #666;
}
```

### Content
Update the following in `index.html`:
- **Hero title**: Change "Creative Designer & Developer"
- **About text**: Update personal information
- **Projects**: Replace project cards with your own work
- **Contact info**: Update email and social links

### Images
Replace placeholder images by:
1. Adding your images to an `images/` folder
2. Updating the `.placeholder-image` divs with `<img>` tags
3. Or replace the gradient backgrounds with your images

## 🌙 **Built-in Features**

### Dark Mode Support
- Automatically adapts to system dark mode preference
- Can be customized with additional toggle if needed

### Accessibility
- **Keyboard navigation**: Full keyboard support
- **Screen reader friendly**: Semantic HTML structure
- **Focus indicators**: Clear focus states for all interactive elements
- **Reduced motion**: Respects user motion preferences

### Browser Support
- **Modern browsers**: Chrome, Firefox, Safari, Edge
- **Mobile browsers**: iOS Safari, Chrome Mobile, Samsung Internet
- **Graceful degradation**: Works on older browsers with fallbacks

## 📁 **File Structure**
```
shy-days-website/
├── index.html          # Main HTML structure
├── styles.css          # Complete CSS with responsive design
├── script.js           # JavaScript for interactions
└── README.md           # Documentation
```

## 🚀 **Getting Started**

1. **Open the website**: Simply open `index.html` in any modern web browser
2. **Customize content**: Edit the HTML to match your personal information
3. **Add your images**: Replace placeholder images with your own
4. **Deploy**: Upload files to any web hosting service

## 📱 **Testing Mobile Experience**

### Browser Dev Tools
1. Open Chrome/Firefox Dev Tools (F12)
2. Click the device toggle button
3. Test different device sizes:
   - iPhone SE (375x667)
   - iPhone 12 Pro (390x844)
   - iPad (768x1024)
   - iPad Pro (1024x1366)

### Real Device Testing
- Test on actual mobile devices for best results
- Check touch interactions and swipe gestures
- Verify form functionality on mobile browsers

## 🎯 **Tablet-Specific Features**

Since you requested tablet optimization, special attention was paid to:
- **Tablet grid layouts**: 2-column layouts on tablets vs single column on mobile
- **Touch-friendly spacing**: Adequate spacing between interactive elements
- **Readable typography**: Font sizes optimized for tablet reading distance
- **Efficient use of space**: Makes use of larger tablet screens effectively

## 💡 **Pro Tips**

1. **Images**: For best results, use high-quality images (2x resolution for retina displays)
2. **Performance**: Optimize images before adding them (WebP format recommended)
3. **SEO**: Add meta descriptions and optimize content for search engines
4. **Analytics**: Add Google Analytics or similar tracking if needed

The website is now fully optimized for both tablet and mobile viewing, with smooth interactions and professional design that maintains the aesthetic of your original Framer site while being completely responsive and fast-loading as a static HTML website.