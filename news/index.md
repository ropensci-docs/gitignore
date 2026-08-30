# Changelog

## gitignore (development version)

## gitignore 0.1.8

CRAN release: 2024-11-01

- Use testthat edition 3
  ([@jrdnbradford](https://github.com/jrdnbradford)).

- Do not run examples if internet is not available.

## gitignore 0.1.7

CRAN release: 2024-07-08

- gitignore now provides clickable links as it uses cli instead of
  crayon ([@olivroy](https://github.com/olivroy)).

- Upgrading to use Bootstrap 5.

- Add light and dark themes to the vignette.

## gitignore 0.1.6

CRAN release: 2023-12-12

- Skip or do not execute code chunks in vignettes if the internet or the
  gitignore API is not available, to fix CRAN problems.
- Update workflow link to point to the v2 branch of r-lib/actions
  repository.

## gitignore 0.1.5

CRAN release: 2021-10-31

- Using GitHub Actions for continuous integration.

- Fixing CRAN check results where tests failed when internet connection
  was not available
  ([\#18](https://github.com/ropensci/gitignore/issues/18)).

## gitignore 0.1.4

CRAN release: 2020-11-04

- Change backend from <https://www.gitignore.io/> to
  <https://www.toptal.com/developers/gitignore> as the former now
  redirects to the latter
  ([\#13](https://github.com/ropensci/gitignore/issues/13)
  [@pat-s](https://github.com/pat-s)).

- Use [`file.path()`](https://rdrr.io/r/base/file.path.html) instead of
  [`paste0()`](https://rdrr.io/r/base/paste.html) to build path.
  [@dpprdan](https://github.com/dpprdan)

## gitignore 0.1.3

CRAN release: 2019-07-29

- This is a minor update that prevent the use of the clipboard on CRAN
  Linux systems.

## gitignore 0.1.2

CRAN release: 2019-06-28

- First release on CRAN.

## gitignore 0.1.1

- First release on rOpenSci.
