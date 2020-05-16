---
title: "textables"

publishDate: "2018-07-14T00:00:00Z"

# Summary. An optional shortened abstract.
summary: R package for automatically producing highly-customized LaTeX tables.

image:
  placement: 2
  caption: ""
  focal_point: "Bottom"
  preview_only: false
  alt_text: 

# links:
# - name: ""
#   url: ""
url_pdf: ''
url_code: 'https://github.com/setzler/textables'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

---

`textables` is an R package for automatically producing highly-customized LaTeX tables.

Simply install using `devtools::install_github("setzler/textables")`, then:
- `TR()` creates a LaTeX table row,
- `%:%` concatenates rows horizontally,
- `+` stacks rows vertically, and,
- `TS()` exports the table into LaTeX and compiled PDF files.

All of the tables in these papers were made using `textables`:
- "Imperfect Competition, Compensating Differentials and Rent Sharing in the U.S. Labor Market," by Lamadon, Mogstad, and Setzler.
- "The Effects of Foreign Multinationals on Workers and Firms in the United States," by Setzler and Tintelnot.
- "Imperfect Competition and Rents in Labor and Product Markets: The Case of the Construction Industry," by Kroft, Luo, Mogstad, and Setzler.
- "How Much Should we Trust Estimates of Firm Effects and Worker Sorting?" by Bonhomme, Holzheu, Lamadon, Manresa, Mogstad, and Setzler.
