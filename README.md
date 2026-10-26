# Neil Phillips — Portfolio

A small, static personal site for sharing my background, public projects and technical
experiments. It is built without a framework runtime or build pipeline: GitHub Pages
serves the HTML and CSS directly from this repository.

**[Visit the live site](https://nphillips-dev.github.io/)**

## What is here

- A text-led homepage introducing my approach to technology and engineering
- A biography covering my path from science into software and technology leadership
- A growing portfolio of personal projects and experiments
- Responsive layouts for mobile and desktop
- An Ocean colour theme with accessible reduced-motion behaviour
- No package installation, build step or client-side JavaScript

## Built with

- Semantic HTML
- Modern CSS
- [Unholy CSS](https://github.com/nphillips-dev/Unholy), vendored in `css/unholy-core.css`
- GitHub Pages

Site-specific styles live in `css/custom.css`. Theme variables, including the Dark,
Light and Ocean presets, live in `css/core/unholy-variables.css`.

## Getting started

### Prerequisites

Only a modern web browser is required. Git is needed if you want to clone the
repository rather than download it from GitHub.

### Installing

Clone the repository:

```sh
git clone https://github.com/nphillips-dev/nphillips-dev.github.io.git
cd nphillips-dev.github.io
```

There are no dependencies to install. Open `index.html` directly in a browser or serve
the directory with any static file server.

## Project structure

```text
.
├── index.html                  # Homepage
├── bio.html                    # Biography
├── portfolio.html              # Public projects and external profiles
├── css/
│   ├── core/
│   │   └── unholy-variables.css
│   ├── unholy-core.css         # Vendored Unholy framework styles
│   └── custom.css              # Portfolio-specific presentation
└── images/
    └── me.jpg
```

## Testing

The site does not currently have an automated test suite. Before deployment, check the
three pages at mobile and desktop widths and verify that:

- Navigation works between every page
- Project and profile links open their intended destinations
- The Ocean theme remains readable and consistent
- Motion is disabled when the operating system requests reduced motion
- No local image or stylesheet requests return an error

## Deployment

The repository is a GitHub Pages user site and requires no compilation. The checked-in
HTML, CSS and image assets are the deployable application.

Production: **[nphillips-dev.github.io](https://nphillips-dev.github.io/)**

## Author

Neil Phillips — [GitHub](https://github.com/nphillips-dev) ·
[LinkedIn](https://www.linkedin.com/in/neil-phillips/)

## License

This repository does not currently include a licence.
