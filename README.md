# Bob IDE Setup Guide

A comprehensive step-by-step guide for setting up and accessing the Bob IDE (Integrated Development Environment). This guide is designed to help users quickly get started with Bob IDE, covering installation, configuration, and initial setup.

## 📋 Overview

This setup guide covers:

- **Bob IDE Installation** - Complete installation process for your operating system
- **Initial Configuration** - Setting up your development environment
- **Access and Authentication** - Connecting to Bob IDE and managing credentials
- **Workspace Setup** - Configuring your first project workspace
- **Troubleshooting** - Common issues and their solutions
- **Best Practices** - Tips for optimal Bob IDE usage

## 🚀 Quick Start

### Viewing the Guide Locally

1. **Clone this repository:**
   ```bash
   git clone https://github.com/[your-username]/[repository-name].git
   cd [repository-name]
   ```

2. **Open the guide:**
   - Simply open `index.html` in your web browser
   - Or use a local server (optional):
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Python 2
     python -m SimpleHTTPServer 8000
     
     # Using Node.js (with http-server)
     npx http-server
     ```
   - Then navigate to `http://localhost:8000` in your browser

### Viewing the Published Guide

Once deployed, the guide will be available at:
```
https://[your-username].github.io/[repository-name]/
```

## 🌐 Deploying to GitHub Pages

### Step 1: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on **Settings** (gear icon)
3. Scroll down to the **Pages** section in the left sidebar
4. Under **Source**, select the branch you want to deploy (typically `main`)
5. Select the root folder (`/`) as the source directory
6. Click **Save**

### Step 2: Wait for Deployment

- GitHub will automatically build and deploy your site
- This usually takes 1-2 minutes
- You'll see a green checkmark when deployment is complete
- A link to your live site will appear at the top of the Pages settings

### Step 3: Access Your Site

Your guide will be available at:
```
https://[your-username].github.io/[repository-name]/
```

### Custom Domain (Optional)

If you want to use a custom domain:

1. Add a `CNAME` file to the repository root with your domain name
2. Configure your domain's DNS settings to point to GitHub Pages
3. Update the custom domain in GitHub Pages settings

## 📁 Project Structure

```
.
├── index.html              # Main HTML page with the setup guide
├── images/                 # Directory containing all guide images
│   ├── image1.png         # Screenshot/diagram 1
│   ├── image2.png         # Screenshot/diagram 2
│   └── ...                # Additional images
├── README.md              # This file
├── _config.yml            # Jekyll configuration for GitHub Pages
└── .gitignore             # Git ignore rules
```

## 🎨 Design System

This guide is built using the **IBM Carbon Design System**, which provides:

- Consistent, professional UI components
- Responsive design that works on all devices
- Accessible components following WCAG guidelines
- Modern, clean aesthetic

### Key Features:

- **Responsive Layout** - Adapts to desktop, tablet, and mobile screens
- **Accessible** - Built with accessibility best practices
- **Fast Loading** - Optimized for quick page loads

## 🔗 Navigation Structure

The guide uses a structured navigation system:

1. **Main Sections** - Major topics in the setup process
2. **Subsections** - Detailed steps within each topic
3. **Smooth Scrolling** - Click navigation items to jump to sections

## 🛠️ Local Development

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, or Edge)
- Git (for cloning the repository)
- Optional: A local web server for testing

### Making Changes

1. Edit `index.html` to update content
2. Add new images to the `images/` directory
3. Test locally by opening `index.html` in a browser
4. Commit and push changes to GitHub
5. GitHub Pages will automatically redeploy

### Image Guidelines

- Place all images in the `images/` directory
- Use descriptive filenames (e.g., `installation-step-1.png`)
- Optimize images for web (compress to reduce file size)
- Use PNG for screenshots, JPG for photos
- Include alt text in HTML for accessibility

## 📝 Content Updates

To update the guide content:

1. Open `index.html` in your preferred text editor
2. Locate the section you want to modify
3. Update the HTML content
4. Save the file
5. Test locally to ensure changes look correct
6. Commit and push to GitHub

## 🐛 Troubleshooting

### Common Issues

**Issue: Page not loading after deployment**
- Solution: Wait 1-2 minutes for GitHub Pages to build
- Check the Actions tab for build status
- Ensure GitHub Pages is enabled in settings

**Issue: Images not displaying**
- Solution: Verify image paths are relative (e.g., `images/image1.png`)
- Check that images exist in the `images/` directory
- Ensure image filenames match exactly (case-sensitive)

**Issue: Styles not applying**
- Solution: Check that Carbon CSS CDN links are working
- Clear browser cache and reload
- Verify internet connection for CDN resources

**Issue: Custom domain not working**
- Solution: Check DNS settings (may take 24-48 hours to propagate)
- Verify CNAME file contains correct domain
- Ensure domain is configured in GitHub Pages settings

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Make your changes
4. Test thoroughly
5. Commit your changes (`git commit -m 'Add some improvement'`)
6. Push to the branch (`git push origin feature/improvement`)
7. Open a Pull Request

## 🙏 Credits

- **Design System**: [IBM Carbon Design System](https://carbondesignsystem.com/)
- **Icons**: Carbon Design System Icons
- **Hosting**: GitHub Pages

## 📧 Support

For questions or issues:

- Open an issue in this repository
- Contact the Bob IDE support team
- Check the official Bob IDE documentation

---

**Last Updated**: April 2026

**Version**: 1.0.0