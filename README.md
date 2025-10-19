# SimpleUSM - Book Promotion Website

A static website built with Jekyll and Bootstrap to promote the SimpleUSM book. Deployed using GitHub Pages.

## Features

- **Responsive Design**: Built with Bootstrap 5 for mobile-first responsiveness
- **Modern Layout**: Clean, professional design optimized for book promotion
- **SEO Optimized**: Jekyll SEO plugin for better search engine visibility
- **Easy to Customize**: Simple configuration through `_config.yml`
- **GitHub Pages Ready**: Automated deployment via GitHub Actions

## Pages

- **Home** (`/`) - Hero section, features, testimonials, and CTA
- **About the Book** (`/about/`) - Detailed book information and benefits
- **About the Author** (`/author/`) - Author biography and credentials
- **Contact** (`/contact/`) - Contact form and FAQ

## Local Development

### Prerequisites

- Ruby 2.7 or higher
- Bundler gem
- Git

### Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/simpleusm.com.git
   cd simpleusm.com
   ```

2. Install dependencies:
   ```bash
   bundle install
   ```

3. Run the development server:
   ```bash
   bundle exec jekyll serve
   ```

4. Open your browser to `http://localhost:4000`

### Live Reload

For development with live reload:
```bash
bundle exec jekyll serve --livereload
```

## Customization

### Site Configuration

Edit `_config.yml` to customize:
- Site title and description
- Book information (title, subtitle, author)
- Social media links
- Contact email

### Content

- **Home page**: Edit `index.html`
- **About page**: Edit `about.md`
- **Author page**: Edit `author.md`
- **Contact page**: Edit `contact.md`

### Images

Add your images to `assets/images/`:
- `book-cover.png` - Book cover image (400x600px recommended)
- `author.jpg` - Author photo (400x500px recommended)
- `favicon.png` - Site favicon (32x32px)

### Styling

Custom CSS is in `assets/css/style.css`. Bootstrap 5 variables can be overridden there.

### Contact Form

The contact form uses Formspree. To enable it:
1. Sign up at [Formspree.io](https://formspree.io)
2. Create a new form
3. Replace `YOUR_FORM_ID` in `contact.md` with your actual form ID

## Deployment to GitHub Pages

### First-Time Setup

1. Push this repository to GitHub
2. Go to repository Settings → Pages
3. Under "Build and deployment", select "GitHub Actions" as the source
4. The site will automatically build and deploy on every push to `main`

### Custom Domain

To use a custom domain (like simpleusm.com):

1. Update the `CNAME` file with your domain
2. In GitHub Settings → Pages, add your custom domain
3. Configure your DNS:
   - Add an A record pointing to GitHub Pages IPs:
     - 185.199.108.153
     - 185.199.109.153
     - 185.199.110.153
     - 185.199.111.153
   - Or add a CNAME record pointing to `yourusername.github.io`

### Configuration for GitHub Pages

The `_config.yml` is already configured for GitHub Pages. If your repository name is different from your domain, update:
- `baseurl: "/your-repo-name"`
- `url: "https://yourusername.github.io"`

## Project Structure

```
.
├── _config.yml           # Jekyll configuration
├── _includes/            # Reusable components
│   ├── header.html       # Navigation header
│   └── footer.html       # Site footer
├── _layouts/             # Page layouts
│   ├── default.html      # Main layout with Bootstrap
│   └── page.html         # Simple page layout
├── assets/               # Static assets
│   ├── css/
│   │   └── style.css     # Custom styles
│   ├── js/
│   │   └── main.js       # Custom JavaScript
│   └── images/           # Images
├── .github/
│   └── workflows/
│       └── jekyll.yml    # GitHub Actions workflow
├── index.html            # Home page
├── about.md              # About the book page
├── author.md             # Author page
├── contact.md            # Contact page
├── Gemfile               # Ruby dependencies
└── README.md             # This file
```

## Technologies Used

- **Jekyll**: Static site generator
- **Bootstrap 5**: CSS framework
- **Bootstrap Icons**: Icon library
- **GitHub Pages**: Hosting and deployment
- **GitHub Actions**: CI/CD pipeline

## License

© 2024 SimpleUSM. All rights reserved.

## Support

For issues or questions about the website, please open an issue on GitHub.

For questions about the book, visit the [contact page](https://simpleusm.com/contact/).
