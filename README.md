# Firefox Custom Theme

<img src="https://drive.google.com/file/d/1k1HGJSeVjKVJEDi3rk2q-j9PkfJDNPVH/view?usp=drive_link"><br>

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
