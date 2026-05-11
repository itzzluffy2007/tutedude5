# tutedude5
# Task 5 - Navbar Layout Using `display`

## Overview
This task builds a simple navigation bar using only CSS `display` properties to arrange elements horizontally.

The page includes:
- a logo image
- a horizontal navigation menu with `Home`, `Services`, `About Us`, and `Contact Us`
- a username link aligned to the right
- a hero section with text and an image below the navbar

## Files
- `index.html` - HTML structure for the navigation and page content
- `style.css` - CSS styles that use `display` rules such as `inline-block` and `inline`

## Notes
- The `ul` list is styled with `display: inline-block` and list bullets are removed.
- Each `li` item is also `inline-block` so the menu appears in a row.
- The username link is kept inline and the username block is positioned to the right.
- The navbar background color is set with `.nav`.

## How to view
Open `index.html` in a browser to see the navbar and page layout.

## Tips
- Use `display: inline-block` for inline layout while preserving width and height controls.
- Set `list-style: none`, `padding: 0`, and `margin: 0` on the list to remove default spacing.
- Combine inline layout with fixed or relative positioning to align items precisely.
