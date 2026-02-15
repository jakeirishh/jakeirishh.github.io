# Jake Irish De Guzman - Creative Online Resume

This is a modern, creative HTML resume with an integrated profile photo that can be hosted on GitHub Pages.

## Features

✨ **Modern Design**
- Two-column layout with sidebar
- Purple gradient theme
- Professional profile photo
- Smooth animations and hover effects
- Fully responsive (works on all devices)

🎨 **Creative Elements**
- Custom Google Fonts (Poppins)
- Gradient backgrounds
- Interactive skill cards
- Professional color scheme
- Clean, organized sections

## Files Needed

You'll need to upload **2 files** to GitHub:
1. `index.html` - Your resume webpage
2. `profile-photo.jpg` - Your profile picture

## How to Connect to GitHub

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in to your account
2. Click the "+" icon in the top right corner and select "New repository"
3. Name your repository: `your-username.github.io` 
   - Example: If your username is `jakeirish`, name it `jakeirish.github.io`
   - ⚠️ **Important**: This exact naming format is required for GitHub Pages to work!
4. Make sure the repository is set to **Public**
5. Click "Create repository"

### Step 2: Upload Your Files

**Option A: Using GitHub Web Interface (Easiest)**

1. In your new repository, click "uploading an existing file"
2. Drag and drop **both files**:
   - `index.html`
   - `profile-photo.jpg`
3. Add a commit message like "Add resume and profile photo"
4. Click "Commit changes"

**Option B: Using Git Command Line**

1. Open your terminal/command prompt
2. Navigate to the folder containing your resume files
3. Run these commands:

```bash
git init
git add index.html profile-photo.jpg README.md
git commit -m "Initial commit: Add creative resume"
git branch -M main
git remote add origin https://github.com/your-username/your-username.github.io.git
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on "Settings" tab
3. In the left sidebar, click "Pages"
4. Under "Source", select "Deploy from a branch"
5. Under "Branch", select "main" and "/root"
6. Click "Save"

### Step 4: Access Your Resume

After a few minutes (usually 1-5 minutes), your resume will be live at:

```
https://your-username.github.io
```

For example: `https://jakeirish.github.io`

## Customization Tips

### Changing Colors

The resume uses a purple gradient theme. To change colors, edit these values in the `<style>` section:

- **Main gradient**: Look for `#667eea` and `#764ba2`
- **Sidebar background**: Look for `#2c3e50` and `#34495e`
- **Accent color**: Look for `#3498db` (blue)

### Updating Content

All content is in the HTML. Simply find the text you want to change and edit it directly.

### Changing the Photo

To use a different photo:
1. Rename your new photo to `profile-photo.jpg`
2. Upload it to your repository (replacing the old one)

Photo tips:
- Use a professional headshot
- Square format works best (1:1 ratio)
- Recommended size: 400x400 pixels or larger
- File formats: .jpg, .jpeg, or .png

## Troubleshooting

**Resume not showing after 5 minutes?**
- Check that your repository is named correctly: `username.github.io`
- Make sure the file is named exactly `index.html` (lowercase)
- Verify GitHub Pages is enabled in Settings > Pages

**Profile photo not appearing?**
- Check that the image file is named exactly `profile-photo.jpg`
- Make sure the image is in the same folder as `index.html`
- Check the image file uploaded successfully

**Layout looks broken?**
- Make sure you copied the entire HTML file
- Check that the `<style>` section is complete
- Try clearing your browser cache (Ctrl+F5 or Cmd+Shift+R)

## Updating Your Resume

To make changes:
1. Edit the `index.html` file on GitHub (click the file, then click the pencil icon)
2. Make your changes
3. Scroll down and click "Commit changes"
4. Wait 1-2 minutes for the changes to appear on your live site

## Mobile Responsive

This resume automatically adapts to different screen sizes:
- Desktop: Two-column layout with sidebar
- Tablet: Adjusted spacing and sizing
- Mobile: Single-column layout, stacked sections

## Print Friendly

The resume includes print-optimized CSS. To print:
- Press `Ctrl+P` (Windows) or `Cmd+P` (Mac)
- The colors and layout will automatically adjust for printing

## License

This creative resume template is free to use and modify for personal use.

---

**Need Help?**
If you run into issues, check:
1. [GitHub Pages Documentation](https://docs.github.com/en/pages)
2. Make sure both files are uploaded
3. Verify your repository is public
4. Wait at least 5 minutes after enabling GitHub Pages

Good luck with your resume! 🚀
