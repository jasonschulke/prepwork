# Prep Work

A boutique consultancy website built with Tailwind CSS.

## About

Prep Work is an Austin, TX-based consultancy specializing in:
- Fractional Leadership
- Custom App Development
- Workflow Automation
- Technical Documentation

## Tech Stack

- **HTML** - Static site
- **Tailwind CSS v4** - Styling
- **GitHub Pages** - Hosting

## Development

### Prerequisites

- Node.js 18+
- npm

### Setup

```bash
npm install
```

### Build CSS

```bash
npm run build
```

### Watch for changes

```bash
npm run watch
```

### Local preview

```bash
python3 -m http.server 8080
```

Then open http://localhost:8080

## Deployment

The site automatically deploys to GitHub Pages when changes are pushed to the `main` branch.

## Project Structure

```
├── index.html          # Main site
├── src/
│   └── input.css       # Tailwind source styles
├── dist/
│   └── output.css      # Compiled CSS
├── assets/             # Images and logos
└── package.json        # Dependencies
```

## License

All rights reserved.
