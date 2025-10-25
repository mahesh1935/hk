# Static Site for GitHub Pages

This project is a static website designed to be deployed using GitHub Pages. It includes various HTML files, CSS styles, and JavaScript functionality to create a simple yet effective web presence.

## Project Structure

```
static-site-github-pages
├── index.html          # Main landing page of the website
├── about.html          # Information about the website or project
├── 404.html            # Custom 404 error page
├── assets              # Directory for assets
│   ├── css            # Directory for CSS files
│   │   └── style.css  # Main stylesheet for the website
│   └── js             # Directory for JavaScript files
│       └── main.js    # Main JavaScript file for interactivity
├── docs               # Directory for documentation
│   ├── index.html     # Main page for documentation
│   ├── 404.html       # Custom 404 error page for documentation
│   └── assets         # Directory for documentation assets
│       ├── css       # Directory for documentation CSS files
│       │   └── style.css  # Stylesheet for documentation
│       └── js        # Directory for documentation JavaScript files
│           └── main.js    # JavaScript file for documentation interactivity
├── .github            # GitHub workflows directory
│   └── workflows
│       └── deploy-gh-pages.yml  # GitHub Actions workflow for deployment
├── CNAME              # Custom domain for GitHub Pages
├── README.md          # Project documentation
└── LICENSE            # Licensing terms for the project
```

## Setup Instructions

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Open `index.html` in your browser to view the main page.
4. Customize the content as needed.
5. To deploy the site, push your changes to the `main` branch of the repository. The GitHub Actions workflow will automatically deploy the site to GitHub Pages.

## Usage

- Visit the main page at `index.html`.
- Access the about page at `about.html`.
- If you encounter a non-existent page, you will be redirected to the custom 404 page.
- For documentation, navigate to the `docs` directory.

## License

This project is licensed under the terms specified in the `LICENSE` file.