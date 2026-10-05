# Actually, Tell Me the Odds

*Bayesian thinking for clinics, cards and code.*

Source for the blog at https://jliu771.github.io, built with [Quarto](https://quarto.org).

## Writing and publishing

- Each post is a folder in `posts/` containing an `index.ipynb` (or `index.qmd`). The notebook's first cell is a **Raw** cell holding the post's title, date and categories.
- Run the notebook in Jupyter and save it: the site uses the saved outputs and never re-runs code.
- `quarto preview` shows the site locally.
- `quarto publish gh-pages` builds it and publishes it to GitHub Pages.
