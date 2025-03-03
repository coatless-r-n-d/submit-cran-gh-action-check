
<!-- README.md is generated from README.Rmd. Please edit that file -->

# testpkg

<!-- badges: start -->

[![R-CMD-check](https://github.com/coatless-r-n-d/r-pkg-submit-on-tag/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/coatless-r-n-d/r-pkg-submit-on-tag/actions/workflows/R-CMD-check.yaml)
<!-- badges: end -->

The goal of the repository is to demonstrate how to submit an R package
to CRAN on a tag push.

## Background

The Python community has the ability to submit a package to the Python
Package Index (PyPI) on a tag push. This is done by setting up a GitHub
Action that listens for a tag push and then runs the necessary steps to
submit the package to PyPI.

The R community does not have a similar mechanism for submitting a
package to CRAN on a tag push. This repository demonstrates how to set
up a GitHub Action that listens for a tag push and then runs the
necessary steps to submit the package to CRAN.

Unfortunately, the CRAN submission process is not fully automated. The
package form must be submitted by a human, and the review process of the
package can take several days to complete. However, the GitHub Action in
this repository automates the process of creating the submission tarball
and submitting it to CRAN when a pre-release tag is pushed.

## License

AGPL (\>= 3)
