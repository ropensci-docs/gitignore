# Append or create a .gitignore file

Use the returned template(s) to append the existing .gitignore file.

## Usage

``` r
gi_write_gitignore(fetched_template, gitignore_file = here::here(".gitignore"))
```

## Arguments

- fetched_template:

  Template(s) returned by \`gi_fetch_templates()\`.

- gitignore_file:

  Path of the .gitignore file to modify.

## Value

TRUE if succeeds to write/append the .gitignore, FALSE otherwise.

## Examples

``` r
if (FALSE) { # \dontrun{
f <- file.path(tempdir(), ".gitignore")
new_lines <- gi_fetch_templates("r")
gi_write_gitignore(new_lines, f)

unlink(f)
} # }
```
