# ndcms-docs
Documentation for the CMS Tier3 at Notre Dame

# How to use this documentation repository

## 1. Set Up Local Development Environment

First, you'll need to install Python and pip (Python package manager). Then install MkDocs and a theme:

```bash:mkdocs.yml
# Install MkDocs and the Material theme
pip install mkdocs mkdocs-git-revision-date-localized-plugin

# Create a new MkDocs project
mkdocs new ndcms-docs
cd ndcms-docs
```

## 2. Configure MkDocs

Modify the `mkdocs.yml` configuration file according to any new pages you might have.

## 3. Current documentation structure

The initial and current document structure is:

```bash:directory-structure
.
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── index.md
│   ├── research/
│   │   ├── projects.md
│   │   └── publications.md
│   └── resources/
│       ├── computing.md
│       └── data.md
└── mkdocs.yml
```

## 4. GitHub actions

GitHub actions have been defined for automatic build and deployment into GitHub Pages

## 5. Test your updates locally

```bash
# Serve documentation locally
mkdocs serve

# Build documentation
mkdocs build
```

Visit `http://localhost:8000` to preview your documentation.

## 6. Deploy your documentation to GitHub Pages

Your documentation will be available at `https://YOUR-USERNAME.github.io/ndcms-docs/`
