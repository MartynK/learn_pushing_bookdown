This is a minimal example of a book based on R Markdown and **bookdown** (https://github.com/rstudio/bookdown). Please see the page "Get Started" at https://bookdown.org/home/about/ for how to compile this example.


To render the book while in an open project in R studio, use:

bookdown::render_book("_bookdown.yml", output_format = NULL,
                      clean = TRUE, envir = parent.frame(),
                      clean_envir = !interactive(), output_dir = NULL,
                      new_session = NA, preview = FALSE,
                      config_file = "_bookdown.yml")
              
file.create('docs/.nojekyll')