# STL_DEMOGRAPHY_NhoodChange

[![](https://img.shields.io/badge/extent-st.%20louis%20city-red.svg)](https://github.com/chris-prener/STL_CRIME_Belmar/)
[![](https://img.shields.io/badge/category-crime-orange.svg)](https://github.com/chris-prener/STL_CRIME_Belmar/)
[![](https://img.shields.io/github/release/chris-prener/STL_CRIME_Belmar.svg?label=version)](https://github.com/chris-prener/STL_CRIME_Belmar/releases)
[![](https://img.shields.io/github/last-commit/chris-prener/STL_CRIME_Belmar.svg)](https://github.com/chris-prener/STL_CRIME_Belmar/commits/master)
[![](https://img.shields.io/github/repo-size/chris-prener/STL_CRIME_Belmar.svg)](https://github.com/chris-prener/STL_CRIME_Belmar/)

### Abstract
This repository contains maps and plots that detail a map included in St. Louis County Police Chief Belmar's [proposal for a merged city-county police department](https://bloximages.newyork1.vip.townnews.com/stltoday.com/content/tncms/assets/v3/editorial/8/42/8423788c-c647-54dc-89c9-db985e6e77ce/5c3028f56c8fe.pdf.pdf). See my [dataviz gallery](https://chris-prener.github.io/dataviz/project/stl-pop-change/) for additional details.

### Citing These Images
This repository is associated with a [Digital Object Identifier](https://en.wikipedia.org/wiki/Digital_object_identifier) (or DOI). Please include the DOI when citing these images. You can find pre-formatted citations and a BibTeX entry, among other citation resources, on the associated [Zenodo release page](#).

## Technical Notes
The repository contains mostly `R` code with one bash script. It requires a valid Census Bureau API key. Files were executed in the following order:

1. `docs/cleanData.Rmd`
2. `docs/demoData.Rmd`
3. `docs/densityMap-p1.Rmd`
4. `docs/densityMap-v.Rmd`
5. `docs/popPlot.Rmd`
6. `docs/popMap-p1.Rmd`
7. `docs/popMap-v.Rmd`

## About Christopher Prener, Ph.D.
Chris is an urban and medical sociologist with an interest in mixed methods research designs that incorporate spatial data. His dissertation examined the effect of neighborhood context and conditions on emergency medical services work, particularly with patients who have mental illnesses or substance use disorders. He is also part of a research team examining the effects of literacy on mental health service use and recovery, and his student research team is documenting the effects of systemic street closures in St. Louis. He is an Assistant Professor in the Department of Sociology and Anthropology at Saint Louis University. More details are available at [his website](https://chris-prener.github.io) and he can be contacted at [chris.prener@slu.edu](mailto:chris.prener@slu.edu).
