# GitHub Pages  Website

This repository contains professional CV and track record hosted on GitHub Pages.

## Files Included

1. **index.html** - The main HTML file with your CV content
2. **styles.css** - The stylesheet for your website
3. **README.md** - This file with instructions

## Deployment Instructions

### Method 1: Upload via GitHub Website (Easiest)

1. Go to your repository: `https://github.com/yourusername/yourusername.github.io`
2. Click "Add file" → "Upload files"
3. Drag and drop both `index.html` and `styles.css` files
4. Scroll down and click "Commit changes"
5. Wait 1-2 minutes, then visit: `https://yourusername.github.io`

## Customization Tips

### Update Your Information

Open `index.html` and modify:
- Contact information in the header
- About section content
- Research interests
- Experience details
- Education information
- Skills lists
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

## Features

✓ Responsive design (works on all devices)
✓ Smooth navigation
✓ Professional color scheme
✓ Print-friendly (for PDF generation)
✓ Accessible markup
✓ Fast loading

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

## Troubleshooting

**Site not showing up?**
- Wait 2-5 minutes after pushing changes
- Check repository settings → Pages → ensure "Deploy from a branch" is selected
- Make sure the repository name is exactly `yourusername.github.io`

**Styling not working?**
- Ensure both files are in the root directory
- Check that file names are exactly: `index.html` and `styles.css`
- Clear your browser cache

**Want to use a custom domain?**
- Go to repository Settings → Pages
- Add your custom domain in the "Custom domain" field
- Follow GitHub's instructions for DNS configuration

## Support

For more information about GitHub Pages:
- https://pages.github.com/
- https://docs.github.com/en/pages

## License

Feel free to modify and use this template for your own CV!
