# Adding GyroGear Logo and Device Images

## To complete the investment deck with actual visuals from gyrogear.co:

### 1. Extract Logo from Website
Visit [gyrogear.co](https://gyrogear.co/) and save the GyroGear logo:
- Right-click on the logo and "Save image as..."
- Save as `gyrogear-logo.png` or `gyrogear-logo.svg`
- Place in the same folder as the HTML file

### 2. Extract Device Images from Website
From [gyrogear.co](https://gyrogear.co/), save high-quality images of the GyroGlove device:
- Look for the main product hero image
- Save additional device images showing the product in use
- Save as `gyrogear-device-1.jpg`, `gyrogear-device-2.jpg`, etc.
- Place in the same folder as the HTML file

### 3. Update the HTML File

#### Replace Logo Placeholder:
Find this section in the HTML:
```html
<div class="logo-container">
    <!-- Replace with actual GyroGear logo from website -->
    <!-- <img src="path/to/gyrogear-logo.png" alt="GyroGear Logo" class="gyrogear-logo"> -->
    <div class="logo-placeholder">GG</div>
</div>
```

Replace with:
```html
<div class="logo-container">
    <img src="gyrogear-logo.png" alt="GyroGear Logo" class="gyrogear-logo">
</div>
```

#### Add Device Images:
Add device images throughout the presentation. For example, in Slide 2, add:
```html
<div class="section">
    <h2>The GyroGlove™ Technology</h2>
    <img src="gyrogear-device-1.jpg" alt="GyroGlove Device" class="device-image">
    <!-- rest of content -->
</div>
```

### 4. Website Color Scheme Analysis
Based on gyrogear.co, the actual color scheme uses:
- **Primary**: Black (#000000) and white (#ffffff)
- **Accent**: Blue (#007bff)
- **Background**: Clean white with subtle grays
- **Typography**: Clean, modern sans-serif

The deck has been updated to match this minimal, professional aesthetic.

### 5. Additional Improvements
Consider adding:
- Customer testimonial photos from the website
- Screenshots of the device interface
- Before/after tremor reduction visuals
- Partnership logos (if available on the website)

### 6. File Structure
Your final folder should look like:
```
gyrogear-investment-deck.html
gyrogear-logo.png
gyrogear-device-1.jpg
gyrogear-device-2.jpg
LOGO_AND_IMAGES_INSTRUCTIONS.md
README.md
```

All images will automatically style correctly with the CSS classes already included in the deck.
