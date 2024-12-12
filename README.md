# Firefox Custom Theme
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 400 300">
  <!-- Background -->
  <rect width="400" height="300" fill="#f4f4f4"/>
  
  <!-- Firefox Browser Window Outline -->
  <rect x="50" y="50" width="300" height="200" rx="10" ry="10" fill="white" stroke="#2f95da" stroke-width="3"/>
  
  <!-- Address Bar -->
  <rect x="60" y="60" width="280" height="30" rx="5" ry="5" fill="#e0e0e0"/>
  
  <!-- Tabs -->
  <rect x="65" y="95" width="70" height="20" rx="3" ry="3" fill="#2ecc71"/>
  <rect x="140" y="95" width="70" height="20" rx="3" ry="3" fill="#9b59b6"/>
  <rect x="215" y="95" width="70" height="20" rx="3" ry="3" fill="#2f95da"/>
  
  <!-- Content Area -->
  <rect x="60" y="120" width="280" height="120" fill="#ffffff" stroke="#333" stroke-width="1" stroke-dasharray="5,5"/>
  
  <!-- Folder Structure Illustration -->
  <g transform="translate(50,230) scale(0.6)">
    <rect x="0" y="0" width="40" height="40" fill="#2f95da" rx="5" ry="5"/>
    <text x="20" y="25" text-anchor="middle" fill="white" font-size="12">📁</text>
  </g>
  
  <g transform="translate(100,230) scale(0.6)">
    <rect x="0" y="0" width="40" height="40" fill="#2ecc71" rx="5" ry="5"/>
    <text x="20" y="25" text-anchor="middle" fill="white" font-size="12">📄</text>
  </g>
  
  <!-- Text Labels -->
  <text x="200" y="280" text-anchor="middle" font-size="10" fill="#333">userChrome.css Installation</text>
</svg>

## Installation Instructions

### Method 1: userChrome.css (Recommended)

1. Enable Custom CSS:
   - Open Firefox
   - Go to `about:config`
   - Search for `toolkit.legacyUserProfileCustomizations.stylesheets`
   - Set this setting to `true`

2. Locate Your Profile Folder:
   - Go to `about:support`
   - Find "Profile Folder" and click "Open Folder"

3. Create Folders and Files:
   ```
   [Mozilla FireFox Profile Folder]
                                 └── chrome/
                                     └── userChrome.css
   ```

4. Copy the contents of `userChrome.css` into this file

### Method 2: Firefox Add-on Theme

1. Install the "Theme" Firefox extension
2. Create a new theme using the provided CSS variables

## Customization

### Color Variables
You can easily customize the theme by modifying the root variables:

```css
:root {
    --primary-color: #2f95da8c;    /* Main theme color */
    --secondary-color: #2ecc71;    /* Accent color */
    --background-color: #f4f4f4;   /* Background color */
    --text-color: #333;            /* Primary text color */
    --accent-color: #9b59b6;       /* Highlight/focus color */
}
```

## Features
- Responsive design
- Smooth transitions
- Hover effects
- Dark mode support
- Customizable color scheme

## Compatibility
- Tested on Firefox Latest Version
- Requires Firefox 69+

## License
MIT License
