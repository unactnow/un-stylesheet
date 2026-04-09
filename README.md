# UN Peace and Security Stylesheet

Optimized CSS stylesheet for the UN Peace and Security website.

## Files

- `styles.css` — full stylesheet (source of truth for CDN usage)

## Usage

Reference the raw GitHub file in your HTML:

```html
<link rel="stylesheet" href="https://raw.githubusercontent.com/unactnow/un-stylesheet/main/styles.css">
```

Or use jsDelivr CDN for better performance:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/unactnow/un-stylesheet@main/styles.css">
```

## Optimizations Applied

- Extracted all embedded CSS from 124 HTML pages
- Deduplicated 45 unique CSS variations into single file
- Removed unnecessary `!important` declarations (reduced from 6,000+ to 4)
- Increased selector specificity where needed
- Preserved all original functionality
