## Overview
A Firefox extension that adds PIN protection to specific websites. Similar to iOS Face ID for apps, but using a PIN code instead.

## Core Functionality
### PIN Authentication
- When opening a protected page, shows a modal requesting PIN entry
- PIN remains valid until:
    - Computer is locked
    - Page is closed
    - User clicks on lock icon to manually block the page

### Settings
- List of protected URLs
- Option to add/remove URLs
- Option to set a PIN for each URL

### Lock Button
- Locks the page immediately when clicked
- Can add the current page to protected list if not already added

## Future Enhancements
- Multiple PIN support:
    - Global PIN option for all sites
    - Custom PINs for specific sites

## Technical Implementation Considerations
- Browser storage for PIN and URL settings
- Event listeners for page load, tab close, and system lock
- Modal implementation with proper focus handling
- Security considerations for PIN storage

---
#PROJECT #EXTENSION #FIREFOX 