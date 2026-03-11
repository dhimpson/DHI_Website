# 8500 Hugo Demo

A minimal static website example built with [Hugo](https://gohugo.io/).

## Prerequisites

- [Hugo](https://gohugo.io/installation/) installed

## Commands

```bash
# Preview site locally (http://localhost:1313)
hugo server

# Build static files to public/
hugo
```

## Structure

```
8500-hugo-demo/
├── content/          # Markdown content
│   ├── _index.md     # Homepage
│   └── about.md      # About page
├── layouts/          # HTML templates
│   └── _default/
├── static/           # Static assets (images, CSS, etc.)
│   └── css/
│       └── style.css
├── hugo.toml         # Site configuration
└── README.md
```
