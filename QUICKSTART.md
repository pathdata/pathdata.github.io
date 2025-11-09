# Quick Start Guide: Deploy Your CV to GitHub Pages

## 🚀 Complete Step-by-Step Instructions

### STEP 1: Create GitHub Account
1. Visit https://github.com
2. Click "Sign up"
3. Enter your email, create password, choose username
4. Verify your email address

### STEP 2: Create Your GitHub Pages Repository
1. Log into GitHub
2. Click the **"+"** icon (top right corner)
3. Select **"New repository"**
4. Repository name: `yourusername.github.io` 
   ⚠️ Replace `yourusername` with YOUR actual GitHub username
5. Description: "My Professional CV Website"
6. Make it **Public** ✓
7. Check **"Add a README file"** ✓
8. Click **"Create repository"**

### STEP 3: Upload Your Website Files
1. You should now be on your repository page
2. Click **"Add file"** button
3. Select **"Upload files"**
4. Drag and drop these 2 files:
   - `index.html`
   - `styles.css`
5. Scroll down to "Commit changes" section
6. Add a commit message: "Add CV website files"
7. Click **"Commit changes"** button

### STEP 4: Enable GitHub Pages (if not automatic)
1. In your repository, click **"Settings"** tab
2. Scroll down and click **"Pages"** in the left sidebar
3. Under "Source", select:
   - Branch: **main** (or **master**)
   - Folder: **/ (root)**
4. Click **"Save"**

### STEP 5: Visit Your Website! 🎉
- Wait 2-3 minutes for deployment
- Visit: `https://yourusername.github.io`
- Your CV is now live!

---

## 📝 How to Update Your CV

### To Update Content:
1. Go to your repository on GitHub
2. Click on `index.html`
3. Click the pencil icon (✏️) to edit
4. Make your changes
5. Scroll down and click "Commit changes"
6. Your site will update in 1-2 minutes

### To Update Styling:
1. Follow same steps but edit `styles.css`
2. Change colors by finding and replacing hex codes:
   - `#667eea` (purple blue)
   - `#764ba2` (purple)

---

## 🎨 Customization Ideas

### Change Header Colors
In `styles.css`, line 19-20:
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```
Try these alternatives:
- Blue: `#4facfe 0%, #00f2fe 100%`
- Green: `#43e97b 0%, #38f9d7 100%`
- Orange: `#fa709a 0%, #fee140 100%`

### Add Your Photo
In `index.html`, add this after the `<h1>` tag:
```html
<img src="your-photo.jpg" alt="Your Name" style="border-radius: 50%; width: 150px; height: 150px; object-fit: cover; margin: 20px auto; display: block;">
```
Upload your photo to the repository first!

### Add a Publications Section
See the detailed instructions in README.md

---

## 🛠️ Troubleshooting

### Website not showing?
- ✓ Wait 5 minutes after uploading
- ✓ Check repository name matches your username exactly
- ✓ Make sure repository is Public
- ✓ Check Settings → Pages is enabled

### CSS not working?
- ✓ Make sure `styles.css` is in the root directory
- ✓ File names are case-sensitive
- ✓ Clear browser cache (Ctrl+F5 or Cmd+Shift+R)

### Want to test locally?
1. Download both files to a folder
2. Double-click `index.html`
3. Opens in your browser!

---

## 📱 Mobile Responsive

Your CV automatically adjusts for:
- Desktop computers
- Tablets
- Mobile phones

Test it by resizing your browser window!

---

## 🔗 Share Your CV

Once live, share this link:
`https://yourusername.github.io`

You can also:
- Add it to your email signature
- Put it on LinkedIn
- Include in job applications
- Share on social media

---

## 💡 Pro Tips

1. **Custom Domain**: Buy a domain (like yourname.com) and connect it in Settings → Pages
2. **Google Analytics**: Add tracking code to see who visits
3. **SEO**: Update the `<title>` and add meta descriptions
4. **PDF Version**: Use your browser's "Print to PDF" option
5. **Backup**: Clone the repository to your computer

---

## 📚 Next Steps

Want to add more features?
- Blog section
- Project portfolio
- Contact form
- Interactive elements
- Dark mode toggle

Check out GitHub Pages documentation:
https://docs.github.com/en/pages

---

## ✨ Your Files

You have 3 files to upload:
1. **index.html** - Your CV content
2. **styles.css** - The styling
3. **README.md** - Documentation (optional, for your reference)

Just upload the first 2 to get started!

---

**Need Help?** 
Visit: https://pages.github.com/ or search "GitHub Pages tutorial" on YouTube

**Ready?** Follow Steps 1-5 above and your CV will be live in minutes! 🚀
