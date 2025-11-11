# Charles I. Ikyese - Portfolio Website

A professional, multi-page portfolio website showcasing my work as a Full Stack Developer. Built with HTML, TailwindCSS, and hosted on GitHub Pages.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Multi-Page Layout**: Home, Projects, and Contact pages
- **Working Contact Form**: Integrated with Formspree for free email forwarding
- **Modern UI**: Clean design with TailwindCSS and Font Awesome icons
- **Fast Loading**: No build process, pure HTML/CSS served via CDN
- **Free Hosting**: Deployed on GitHub Pages at no cost

## Pages

### Home Page (`index.html`)
- Professional introduction
- Skills and technologies showcase
- About me section
- Social media links

### Projects Page (`projects.html`)
- Portfolio of 6+ projects
- Technology tags for each project
- Live demo and GitHub links
- Project descriptions

### Contact Page (`contact.html`)
- Working contact form (Formspree)
- Contact information
- Social media connections
- Response time information

## Setup Instructions

### 1. Create GitHub Repository

1. Go to [GitHub](https://github.com) and create a new repository
2. **Important**: Name it exactly `CharyMeld.github.io` (replace `CharyMeld` with your GitHub username)
3. Make it public
4. Don't initialize with README (we already have one)

### 2. Upload Files to GitHub

**Option A: Using Git (Recommended)**

```bash
# Navigate to the portfolio folder
cd CharyMeld.github.io

# Initialize git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial portfolio commit"

# Add remote repository (replace CharyMeld with your username)
git remote add origin https://github.com/CharyMeld/CharyMeld.github.io.git

# Push to GitHub
git branch -M main
git push -u origin main
```

**Option B: Using GitHub Web Interface**

1. Go to your repository on GitHub
2. Click "uploading an existing file"
3. Drag and drop all files (`index.html`, `projects.html`, `contact.html`, `README.md`)
4. Commit changes

### 3. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on "Settings"
3. Scroll down to "Pages" in the left sidebar
4. Under "Source", select `main` branch
5. Click "Save"
6. Wait 2-3 minutes for deployment

Your site will be live at: `https://CharyMeld.github.io`

### 4. Set Up Formspree (Contact Form)

1. Go to [Formspree.io](https://formspree.io)
2. Sign up for a free account
3. Create a new form
4. Copy your form endpoint (looks like `https://formspree.io/f/xxxxxxxxxxx`)
5. Open `contact.html`
6. Replace `YOUR_FORM_ID` in line 68 with your actual form ID:
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```
   Change to:
   ```html
   <form action="https://formspree.io/f/xxxxxxxxxxx" method="POST">
   ```
7. Commit and push changes

### 5. Customize Your Portfolio

#### Update Personal Information

**In `index.html`:**
- Update social media links (GitHub, LinkedIn, Twitter, Email)
- Modify the About Me section
- Add/remove skills as needed

**In `projects.html`:**
- Replace placeholder projects with your actual projects
- Update project descriptions
- Add real demo links and GitHub repository links
- Change technology tags to match your projects

**In `contact.html`:**
- Update email address
- Modify location and availability
- Update social media links

#### Update Colors (Optional)

The site uses TailwindCSS with a blue/purple theme. To change colors:
- Replace `blue-600` with your preferred color (e.g., `green-600`, `red-600`)
- Replace `purple-600` with a complementary color
- Search and replace across all HTML files

## Technologies Used

- **HTML5**: Structure and content
- **TailwindCSS**: Styling framework (via CDN)
- **Font Awesome**: Icons (via CDN)
- **Formspree**: Contact form backend
- **GitHub Pages**: Free hosting

## Customization Tips

### Adding New Projects

1. Copy one of the project card divs in `projects.html`
2. Update the icon, title, description, and tags
3. Add your demo and GitHub links

### Changing the Color Scheme

Search for these color classes and replace them:
- `blue-600` → Your primary color
- `purple-600` → Your secondary color
- `blue-50` → Light background variant

### Adding More Pages

1. Create a new HTML file (e.g., `blog.html`)
2. Copy the navigation from any existing page
3. Add a link to the new page in all navigation menus

## Maintenance

### Updating Content
1. Edit the HTML files locally
2. Test by opening them in a browser
3. Commit and push changes to GitHub
4. Changes will be live in 1-2 minutes

### Monitoring Contact Form
- Log in to Formspree to see submitted messages
- Configure email notifications in Formspree settings

## Troubleshooting

**Site not showing up?**
- Wait 5-10 minutes after first deployment
- Check GitHub Pages settings
- Ensure repository name matches `username.github.io`

**Contact form not working?**
- Verify Formspree form ID is correct
- Check Formspree dashboard for submissions
- Ensure email is verified in Formspree

**Styling looks broken?**
- Check internet connection (TailwindCSS loads from CDN)
- Verify CDN links are correct
- Clear browser cache

## License

Free to use and modify for personal and commercial projects.

## Support

For issues or questions:
- Check [GitHub Pages Documentation](https://docs.github.com/pages)
- Visit [Formspree Documentation](https://help.formspree.io/)
- Review [TailwindCSS Documentation](https://tailwindcss.com/docs)

---

**Built by Charles I. Ikyese** | Full Stack Developer

Last Updated: January 2025
