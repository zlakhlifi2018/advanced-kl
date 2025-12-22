# Advanced Keys & Locks LLC - Website

A modern, responsive website for Advanced Keys & Locks LLC, a professional locksmith company serving the Washington D.C., Maryland, and Virginia (DMV) metropolitan area.

## Live Site

Visit the live website: [https://zouhir-dahbi.github.io/advance-kl/](https://zouhir-dahbi.github.io/advance-kl/)

## Technologies Used

- **HTML5** - Semantic markup
- **Tailwind CSS** - Utility-first CSS framework (via CDN)
- **Alpine.js** - Lightweight JavaScript framework for interactivity (via CDN)
- **Google Fonts** - Bebas Neue (display) and Outfit (body)

## Project Structure

```
advance-kl/
├── index.html              # Home page
├── services.html           # Services page
├── service-areas.html      # Service areas listing
├── about.html              # About us page
├── contact.html            # Contact page with form
├── blog.html               # Blog listing page
├── blog/                   # Blog posts
│   └── 5-signs-you-need-to-rekey-your-locks.html
├── assets/
│   ├── css/
│   │   └── styles.css      # Custom styles
│   └── images/             # Logo and images
└── README.md
```

## Running Locally

Since this is a static website with no build step, you can run it locally using any simple HTTP server.

### Option 1: Python (recommended)

```bash
# Clone the repository
git clone git@github.com:zouhir-dahbi/advance-kl.git
cd advance-kl

# Start a local server (Python 3)
python3 -m http.server 8080

# Or with Python 2
python -m SimpleHTTPServer 8080
```

Then open [http://localhost:8080](http://localhost:8080) in your browser.

### Option 2: Node.js

```bash
# Install a simple server globally
npm install -g serve

# Run the server
serve .
```

### Option 3: VS Code Live Server

1. Install the "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

## Contributing

We welcome contributions to improve the website. Here's how to get started:

### Getting Started

1. **Fork the repository** on GitHub

2. **Clone your fork**
   ```bash
   git clone git@github.com:YOUR_USERNAME/advance-kl.git
   cd advance-kl
   ```

3. **Create a new branch** for your feature or fix
   ```bash
   git checkout -b feature/your-feature-name
   ```

4. **Start the local server** and make your changes
   ```bash
   python3 -m http.server 8080
   ```

5. **Test your changes** in the browser at [http://localhost:8080](http://localhost:8080)

### Making Changes

- **HTML files** - Edit the page content directly
- **Styles** - Modify `assets/css/styles.css` for custom styles, or use Tailwind utility classes inline
- **Images** - Add new images to `assets/images/`

### Code Style Guidelines

- Use semantic HTML5 elements
- Follow existing indentation (4 spaces)
- Use Tailwind CSS utility classes when possible
- Keep custom CSS minimal and well-documented
- Ensure all pages are mobile-responsive
- Test on multiple browsers before submitting

### Submitting Changes

1. **Commit your changes** with a descriptive message
   ```bash
   git add .
   git commit -m "Add feature: description of what you changed"
   ```

2. **Push to your fork**
   ```bash
   git push origin feature/your-feature-name
   ```

3. **Create a Pull Request** on GitHub
   - Go to the original repository
   - Click "New Pull Request"
   - Select your branch
   - Provide a clear description of your changes

### Pull Request Guidelines

- Provide a clear title and description
- Include screenshots for visual changes
- Reference any related issues
- Ensure the site works on mobile and desktop
- Test in Chrome, Firefox, and Safari if possible

## Adding Blog Posts

To add a new blog post:

1. Create a new HTML file in the `blog/` folder
2. Use `blog/5-signs-you-need-to-rekey-your-locks.html` as a template
3. Update the meta tags, title, and content
4. Add a link to the new post in `blog.html`

## License

Copyright 2024 Advanced Keys & Locks LLC. All rights reserved.

## Contact

- **Phone**: (826) 202-0852
- **Email**: advancekeys@outlook.com
- **Website**: [advancekeysandlocks.com](https://zouhir-dahbi.github.io/advance-kl/)

