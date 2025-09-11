# Mobile Optimization Template

## User Preferences for Website Development

**All websites should be optimized for mobile devices with the following requirements:**

### 📱 Mobile-First Design
- **Responsive breakpoints**: 768px (tablet/mobile) and 480px (small mobile)
- **Mobile navigation**: Hamburger menu instead of horizontal navigation
- **Touch-friendly**: Large, easy-to-tap buttons and links
- **Single-column layouts**: Content stacks vertically on mobile

### 🎨 Visual Improvements
- **Text sizing**: Responsive font sizes that scale with screen size
- **Button sizing**: Full-width buttons on mobile (max-width: 300px)
- **Spacing**: Reduced padding and margins for mobile screens
- **Content adaptation**: Automatic layout changes based on screen size

### 🔧 Technical Implementation
- **CSS Grid/Flexbox**: Use modern layout techniques with fallbacks
- **Viewport meta tag**: `<meta name="viewport" content="width=device-width, initial-scale=1.0">`
- **Safari compatibility**: Include `-webkit-` prefixes for CSS properties
- **Mobile JavaScript**: Touch-friendly navigation and interactions

### 📋 CSS Template Structure
```css
/* Mobile-first responsive design */
@media (max-width: 768px) {
    /* Tablet and mobile styles */
}

@media (max-width: 480px) {
    /* Small mobile styles */
}
```

### 🎯 Key Features to Include
1. **Hamburger navigation menu**
2. **Responsive typography**
3. **Touch-friendly buttons**
4. **Single-column layouts on mobile**
5. **Proper spacing and padding**
6. **Smooth transitions and animations**

### 📝 Notes
- Always test on actual mobile devices
- Use browser developer tools for responsive testing
- Consider both portrait and landscape orientations
- Ensure fast loading on mobile networks

---
**Created for**: GiftSmart Pro and future projects
**Last updated**: January 2025
