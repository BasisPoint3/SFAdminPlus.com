# SF Admin Tools Website

A mobile-friendly website for Salesforce Admin Chrome extensions, built with FlowBite and optimized for SEO.

## Features

- Mobile-responsive design using FlowBite (Tailwind CSS)
- SEO-optimized with meta tags and structured data
- Blog section for Salesforce admin guides
- Fast loading with CDN resources
- Ready for GitHub Pages hosting

## Structure

```
/
├── index.html              # Homepage
├── blog.html               # Blog listing page
├── about.html              # About page
├── blog/                   # Blog posts directory
│   └── *.html             # Individual blog posts
├── assets/                 # Static assets
│   ├── css/               # Custom styles
│   ├── js/                # JavaScript files
│   └── images/            # Image assets
├── sitemap.xml            # XML sitemap for SEO
└── robots.txt             # Search engine directives
```

## Hosting on GitHub Pages

1. Create a new GitHub repository
2. Upload all files to the repository
3. Go to Settings → Pages
4. Select source: "Deploy from a branch"
5. Select branch: "main" (or "master")
6. Select folder: "/ (root)"
7. Click Save
8. Your site will be available at: `https://[username].github.io/[repository-name]/`

## Customization

Before deploying, update the following:

1. Replace `yourdomain.com` with your actual domain in:
   - All HTML files (meta tags, structured data)
   - sitemap.xml
   - robots.txt

2. Update Chrome extension links in index.html

3. Add your Google Analytics or other tracking codes

4. Update contact email in about.html

## Adding Blog Posts

1. Create a new HTML file in the `/blog/` directory
2. Use the existing blog post as a template
3. Update meta tags, structured data, and content
4. Add the post to blog.html listing
5. Update sitemap.xml with the new URL

## SEO Checklist

- [x] Meta descriptions on all pages
- [x] Open Graph tags for social sharing
- [x] Structured data (JSON-LD) for blog posts
- [x] XML sitemap
- [x] Robots.txt
- [x] Mobile-responsive design
- [x] Fast loading with CDN resources
- [x] Semantic HTML structure
- [x] Proper heading hierarchy

## Technologies Used

- FlowBite (Tailwind CSS components)
- Tailwind CSS
- Vanilla JavaScript
- HTML5 semantic markup

## License

© 2024 SF Admin Tools. All Rights Reserved.