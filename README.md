
# Personal Website using "Academic Pages" template

![pages-build-deployment](https://github.com/academicpages/academicpages.github.io/actions/workflows/pages/pages-build-deployment/badge.svg)


**[rbarritault.github.io/](https://rbarritault.github.io/)**

Academic Pages is a Github Pages template for academic websites.

# Personal reminder
- Some tips for Markdown: See this [page](https://github.com/academicpages/academicpages.github.io/blob/master/_pages/markdown.md). 
- Basic info on the sidebar: [config.yml](_config.yml)
- Homepage : [pages/about](_pages/about.md)
- CV : [pages/CV](_pages/cv.md)
- Talks : [pages/talks](_pages/talks.md)
- Teaching : [pages/teaching](_pages/teaching.md)
- Publications : [pages/publications](_pages/publications.md)
  * Copy one publication
  * Modify the id in : "visib('tannaka2024')" and "<div id="tannaka2024""
  * Change links for ArXiv and HAL
  * Change Abstract
  
# Getting Started

1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Click the "Use this template" button in the top right.
1. On the "New repository" page, enter your repository name as "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and add your content.
1. Upload any files (like PDFs, .zip files, etc.) to the `files/` directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section
1. (Optional) Use the Jupyter notebooks or python scripts in the `markdown_generator` folder to generate markdown files for publications and talks from a TSV file.

See more info at https://academicpages.github.io/

## Running Locally

When you are initially working your website, it is very useful to be able to preview the changes locally before pushing them to GitHub. To work locally you will need to:

1. Clone the repository and made updates as detailed above.
1. Make sure you have ruby-dev, bundler, and nodejs installed: `sudo apt install ruby-dev ruby-bundler nodejs`
1. Run `bundle install` to install ruby dependencies. If you get errors, delete Gemfile.lock and try again.
1. Run `jekyll serve -l -H localhost` to generate the HTML and serve it from `localhost:4000` the local server will automatically rebuild and refresh the pages on change.