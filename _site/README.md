# Personal Website

This is the source code for my personal website, built with Jekyll.

## Prerequisites

Before you begin, ensure you have the following installed:
- Ruby
- Bundler

## Getting Started

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/yashm8/yashm8.github.io.git
    cd yashm8.github.io
    ```

2.  **Install dependencies:**
    This will install Jekyll and other necessary gems as specified in the `Gemfile`.
    ```bash
    bundle install
    ```

## Usage

### Running the site locally

To start the Jekyll development server, run:
```bash
bundle exec jekyll serve
```
This will start a local server, usually at `http://127.0.0.1:4000/`. The site will automatically regenerate when you make changes to the source files.

### Building the site for production

To generate the static site files, run:
```bash
bundle exec jekyll build
```
The static files will be placed in the `_site` directory. This is the directory that should be deployed to a web server. For GitHub Pages, this step is handled automatically.

## Content Editing

The main content of the website is in the `index.md` file. You can edit this file using Markdown to update the content of the homepage.
