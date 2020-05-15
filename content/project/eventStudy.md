---
title: "eventStudy"

publishDate: "2019-01-02T00:00:00Z"

# Summary. An optional shortened abstract.
summary: R package and guide for performing event studies with heterogeneous dynamic effects. 

image:
  placement: 1
  caption: "Photo by [Academic](https://sourcethemes.com/academic/)"
  focal_point: "Center"
  preview_only: false
  alt_text: An optional description of the image for screen readers.

# links:
# - name: ""
#   url: ""
url_pdf: 'https://github.com/setzler/eventStudy/blob/master/guide/event_study_guide.pdf'
url_code: 'https://github.com/setzler/eventStudy'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

---

`eventStudy` is an R package and guide for performing event studies with heterogeneous dynamic effects. It provides point estimates and standard errors for average treatment effects on the treated (ATT) parameters that vary by treatment cohort and event time.

The package provides a single command that handles everything automatically, including complicated data manipulation and regression steps, such as:
- "stacking" control units and employing a fully-interacted regression to estimate the various ATTs,
- correcting for anticipation and deviations from parallel trends using parametric and non-parametric approaches,
- providing various summary ATT estimates collapsed across treatment cohorts and/or event times with appropriate clustered standard errors.

Simply install using `devtools::install_github("setzler/eventStudy/eventStudy")`, then the entire data preparation and estimation process is performed in one line using the `ES` command.

Papers using this software include:
- "Imperfect Competition and Rents in Labor and Product Markets: The Case of the Construction Industry," by Kroft, Luo, Mogstad, and Setzler
