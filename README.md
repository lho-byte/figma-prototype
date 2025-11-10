# Figma Prototype

iOS 26 Liquid Glass Segmented Control built with HTML and Tailwind CSS.

## Features

- ✅ iOS 26 Liquid Glass Effect on selected state
- ✅ Frosted backdrop blur with 30px blur and 200% saturation
- ✅ Smooth transitions and animations
- ✅ Interactive toggle functionality
- ✅ Fully responsive design
- ✅ Built with Tailwind CSS via CDN (no build step required)

## Design Details

The segmented control features:
- **Glass morphism effect** - Premium frosted glass appearance on active segments
- **Layered shadows** - Multiple inset and outer shadows for depth
- **Gradient overlays** - Subtle lighting effects
- **High contrast** - Clear distinction between selected and unselected states
- **Text opacity** - 100% opacity for selected, 60% for unselected segments

## How to Use

1. Simply open `index.html` in your web browser
2. Or use a local server for better development experience:
   ```bash
   # Using Python 3
   python3 -m http.server 8000
   
   # Using PHP
   php -S localhost:8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   ```
3. Then visit `http://localhost:8000` in your browser

## Customization

You can customize the design by:

1. **Colors**: Edit the glass effect styles in the `<style>` section
2. **Blur intensity**: Adjust `backdrop-filter: blur()` values
3. **Segments**: Add more button elements within the container
4. **Animation**: Modify the `transition-all duration-300` classes

## Browser Support

Works on all modern browsers that support backdrop-filter and CSS Grid/Flexbox.
