# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview
This is a simple static website for CMISP Diplomatico, consisting of a single HTML page (cmisp.html) styled with CSS (style.css) and featuring two images: a logo (gavel.jpg) and a favicon (cmispdiplomatico.jpg).

## File Structure
- `cmisp.html` - Main HTML document
- `style.css` - Stylesheet for layout and appearance
- `gavel.jpg` - Background image displayed below the header
- `cmispdiplomatico.jpg` - Logo image displayed in the header and favicon/icon for the site

## Development Commands
As a static site, there are no build steps, linting, or test suites. To view changes:
1. Open `cmisp.html` in any web browser.
2. Refresh the page after editing HTML or CSS.
3. For CSS changes, ensure the browser cache is bypassed (Ctrl+F5) if styles don't update.

## Common Tasks
- **Editing content**: Modify `cmisp.html` to update text, links, or structure.
- **Styling changes**: Edit `style.css` to adjust layout, colors, fonts, or responsiveness.
- **Image updates**: Replace `gavel.jpg` or `cmispdiplomatico.jpg` with new images of the same name, or update the references in HTML.

## Notes
- The site features a fixed header with the logo on the left and navigation links on the right.
- The header has a white background with 90% opacity for a clean, modern look.
- Below the header, the gavel image is displayed as a background container, limited to 1920px width and scaling proportionally.
- A scroll indicator (down arrow and "scroll for more" text) appears at the bottom of the gavel image on screens wider than 1024px to encourage users to scroll down.
- Horizontal scrolling is disabled via `overflow-x: hidden` on the body.
- No JavaScript or frameworks are used; the site is purely HTML/CSS.