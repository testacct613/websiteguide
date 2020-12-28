# run the global .Rprofile if it exists (you may configure blogdown options
# there, too, so they apply to any blogdown projects)
if (file.exists("~/.Rprofile")) {
  base::sys.source("~/.Rprofile", envir = environment())
}

# a few sample options to customize the behavior of blogdown; for more options,
# see https://bookdown.org/yihui/blogdown/global-options.html
options(
  # to automatically serve the site on RStudio startup, set this option to TRUE
  blogdown.serve_site.startup = FALSE,
  # to disable knitting Rmd files on save, set this option to FALSE
  blogdown.knit.on_save = TRUE
)

# fix Hugo version
options(blogdown.hugo.version = "0.79.0")
options(blogdown.new_bundle = TRUE)
options(blogdown.author = "Arnie",
        blogdown.ext = ".Rmd",
        blogdown.subdir = "blog",
        blogdown.yaml.empty = TRUE,
        blogdown.new_bundle = TRUE,
        blogdown.title_case = TRUE)
