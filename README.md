# dipeshvpatel.github.io

### Installation
```bash
# Install dependencies
bundle install

# Run local server
bundle exec jekyll serve
```

Visit `http://localhost:4000` to view the site locally.

## Project Structure
```
.
├── _config.yml        # Jekyll configuration
├── _layouts/
│   └── default.html   # Default page layout
├── index.md           # Home page
├── README.md          # This file
└── .gitignore         # Git ignore rules
```

## Customization
1. **Edit `_config.yml`**: Update site title, author, and other metadata
2. **Edit `index.md`**: Modify homepage content
3. **Add pages**: Create `.md` files in the root directory
4. **Add posts**: Create files in `_posts/` folder (optional)
5. **Edit `_layouts/default.html`**: Customize the page template and styling

## Deployment
Push to the `main` or `master` branch on GitHub. GitHub Pages will automatically build and deploy your site.

## Learn More
- [Jekyll Documentation](https://jekyllrb.com)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)