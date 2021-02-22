# psychnerdjae.github.io

Site accessible at [https://psychnerdjae.github.io/](https://psychnerdjae.github.io/).

Built entirely in [RStudio](https://rstudio.com/) using [Distill for R Markdown](https://rstudio.github.io/distill/), hosted using [GitHub pages](https://docs.github.com/en/github/working-with-github-pages).

If you're interested in building your own site in this way, the [Distill documentation](https://rstudio.github.io/distill/) is great for getting started quickly. Feel free to look at my source materials (contained in the top-level directory in `.Rmd` format) to see how I configured mine. One little trick that I'm proud of is having written my CV entirely in markdown, knitting simultaneously to HTML and PDF, and having the HTML automatically link to the latest PDF (since it's quite common for academics to share their CVs as PDFs). Note that when the website is built from RStudio, it's configured to output to `/docs/`, which is where the public-facing website is hosted; these files are safe to ignore.
