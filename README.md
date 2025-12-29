# Shenzhou Qigong Tuina Massage Services

A professional static website for massage and wellness services, hosted on GitHub Pages.

## Features

- **Responsive Design**: Mobile-friendly layout that works on all devices
- **Service Showcase**: Display your massage services and offerings
- **Gallery**: Space for professional massage therapy images
- **Pricing Table**: Clear pricing structure for different services
- **Contact Information**: Phone number, email, address, and contact form
- **Professional Styling**: Modern gradient design with smooth animations

## Getting Started

### Local Development

1. Clone this repository
2. Open `index.html` in your web browser
3. Edit the content to match your business information

### Customization

- **Contact Information**: Update phone number, email, and address in `index.html`
- **Pricing**: Modify the price table in the pricing section
- **Images**: Add your massage images to an `images/` folder:
  - `images/massage-1.jpg`
  - `images/massage-2.jpg`
  - `images/massage-3.jpg`
  - `images/massage-4.jpg`
- **Colors**: Modify the color scheme in `styles.css` (change `#667eea` and `#764ba2`)

## Hosting on GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [github.com](https://github.com) and sign in
2. Click "New repository"
3. Name your repository: `shenzhouqigongtuina` (or any name)
4. Choose "Public" (required for free GitHub Pages)
5. Click "Create repository"

### Step 2: Push Your Files to GitHub

1. In your terminal, navigate to your project folder:
   ```bash
   cd /Users/jiaweiqian/Desktop/shenzhouqigongtuina_site
   ```

2. Initialize Git and push your files:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: massage website"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/shenzhouqigongtuina.git
   git push -u origin main
   ```
   Replace `YOUR-USERNAME` with your actual GitHub username.

### Step 3: Enable GitHub Pages

1. Go to your GitHub repository
2. Click "Settings" (gear icon)
3. Scroll down to "Pages" section
4. Under "Build and deployment":
   - Source: Select "Deploy from a branch"
   - Branch: Select "main" and "/(root)"
5. Click "Save"

Your website will be live at: `https://YOUR-USERNAME.github.io/shenzhouqigongtuina/`

## Project Structure

```
shenzhouqigongtuina_site/
├── index.html          # Main HTML file
├── styles.css          # CSS styling
├── images/             # Folder for your massage images
│   ├── massage-1.jpg
│   ├── massage-2.jpg
│   ├── massage-3.jpg
│   └── massage-4.jpg
└── README.md           # This file
```

## Adding Images

1. Create an `images/` folder in your project
2. Add your massage photos (JPG or PNG format)
3. Update the image filenames in `index.html` to match your actual files

## Tips for Success

- Use high-quality, professional-looking massage/wellness images
- Keep contact information current
- Test the contact form - basic form validation is included
- Use descriptive alt text for all images (already included)
- Mobile test your website before sharing the link

## License

This project is available for personal and commercial use.

## Support

For more information about GitHub Pages, visit: https://pages.github.com/
