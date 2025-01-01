# Personal Portfolio Website

A minimalist, markdown-driven portfolio website built with Hugo. This site focuses on content-first design with simple navigation through markdown links.

## Features

- Clean, minimalist design
- Content-driven navigation
- No automatic listings or menus
- Responsive layout
- Fast and lightweight

## Technology Stack

- [Hugo](https://gohugo.io/) - Static Site Generator
- Pure CSS for styling
- Markdown for content

## Project Structure

```
protyasha-roy/
├── content/         # Markdown content files
├── layouts/         # HTML templates
├── static/         
│   ├── css/        # Stylesheet
│   └── images/     # Image assets
└── hugo.toml       # Hugo configuration
```

## Local Development

1. Install Hugo (Extended Version)
2. Clone this repository
3. Run the development server:
   ```bash
   hugo server
   ```
4. Visit `http://localhost:1313` in your browser

## Adding Content

Create new pages by adding markdown files in the `content` directory. Link between pages using standard markdown syntax:

```markdown
[Link Text](/page-path)
```

## License

MIT License

## Author

Protyasha Roy
