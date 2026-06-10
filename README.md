# Quarto Project Template

## Set up tasks on local

- Create an `_environment.local` env var file.
- Create a `./data` directory. It is best to _not_ check data directories into Git to save space and avoid exposing sensitive data.
  - The [yaup](https://github.com/jamespcollins/yaup) package has helper functions for initializing and using a data directory.

## Other potential set up tasks

- `usethis::create_package('.')` to create an R package in the current directory.
- `usethis::use_testthat()` to create automated tests.
- `renv::snapshot()` and `renv::use()` to create package environments.
- Copy `render.sh` from Longleaf.
