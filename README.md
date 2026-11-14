# Book Companion Notebooks

Full, runnable Jupyter notebooks for the book series *A Solutions Architect's Field Guide*. The books print short, edited excerpts as numbered Listings. This repo holds the complete notebooks those excerpts come from.

## Structure

Notebooks are grouped by book, then by chapter. Chapter numbers run on across the series, so Book 2 starts at Chapter 21.

```
book-companion-notebooks/
  book1/
    ch01/
      history_and_landscape.ipynb
    ch02/
      business_problem_framing.ipynb
    ...
```

| Book | Title | Chapters | Status |
|------|-------|----------|--------|
| 1 | *Classical Data Science* | 1–20 | Published |
| 2 | *Modern AI* | 21–37 | Coming later |
| 3 | *Systems & Performance* | 38–57 | Coming later |
| 4 | *Applied AI Domains* | 58–83 | Coming later |

Book 1 has one notebook for each of its 20 chapters.

## Using the notebooks

Install the packages, then start Jupyter:

```
pip install -r requirements.txt
jupyter lab
```

The notebooks are saved clean, with no outputs. Run them top to bottom to see the results. Some notebooks save charts (`.png`) and data (`.csv`) next to themselves. Git ignores these files. Listing 4.3 in the book is the third listing in Chapter 4, and you'll find its full code in `book1/ch04/`.

## Versioning

This repo is the source of truth for runnable code. The book's Listings are hand-edited excerpts. They can trim cells and show sample output for print. Each book edition cites a tagged release (for example `book1-v1.0`), not the latest commit. This stops the printed book and the repo drifting apart.

## License

The notebooks are licensed under the MIT License. See `LICENSE`. The books are licensed separately, under CC BY-SA 4.0.
