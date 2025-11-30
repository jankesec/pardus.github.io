# Pardus Linux Website

This repository contains the source code for the Pardus Linux website, built with [MkDocs](https://www.mkdocs.org/) and [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/).

## Getting Started

Follow these instructions to set up the project locally on your machine.

### Prerequisites

- Python 3.x
- Git

### Installation

1. **Clone the repository**

   ```bash
   git clone git@github.com:pardus/pardus.github.io.git
   cd pardus.github.io
   ```

2. **Create a virtual environment**

   ```bash
   python3 -m venv venv
   ```

3. **Activate the virtual environment**

   ```bash
   source venv/bin/activate
   ```

4. **Install dependencies**

   ```bash
   pip install mkdocs-material mkdocs-material-extensions
   ```

## Usage

To start the development server with live reload:

```bash
mkdocs serve --livereload
```

Open your browser and navigate to `http://127.0.0.1:8000/`. The site will automatically update as you modify the files.

## Deployment

This project is configured to automatically deploy to GitHub Pages using GitHub Actions when changes are pushed to the `main` branch.
