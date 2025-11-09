# GitHub Pages  Website

This repository contains professional CV and track record hosted on GitHub Pages.

## Files Included

1. **index.html** - The main HTML file with your CV content
2. **styles.css** - The stylesheet for your website
3. **README.md** - This file with instructions

## Deployment Instructions

### GitHub Website 
https://pathdata.github.io/

## Customization Tips

### Update Information

- Publication
- Supervision section

### Change Colors

Open `styles.css` and modify the color schemes:
- Primary gradient: Lines 19-20 (purple gradient)
- Accent colors: Search for `#667eea` and `#764ba2`
- Background: Line 11 (`#f5f5f5`)

### Add More Sections

To add a new section:
1. Add a navigation link in the `<nav>` section of index.html
2. Create a new `<section>` in the main content area
3. Style it similar to existing sections

## Adding Publications

If you want to add a publications section, add this code before the footer in index.html:

```html
<section id="publications">
    <h2>Selected Publications</h2>
    <div class="publication-item">
        <p><strong>Title of Paper</strong></p>
        <p>Authors: Your Name, Co-author, etc.</p>
        <p>Journal Name, Year. DOI: <a href="#">link</a></p>
    </div>
    <!-- Add more publications -->
</section>
```

And add corresponding CSS in styles.css:

```css
.publication-item {
    margin-bottom: 20px;
    padding: 15px;
    background-color: #f8f9fa;
    border-radius: 8px;
    border-left: 4px solid #667eea;
}
```

## Support

For more information about GitHub Pages:
- https://pages.github.com/
- https://docs.github.com/en/pages

