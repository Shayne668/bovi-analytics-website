Sys.setenv(RENV_DOWNLOAD_FILE_METHOD = "libcurl")
source("renv/activate.R")

# Run the global .Rprofile if it exists
if (file.exists("~/.Rprofile")) {
  base::sys.source("~/.Rprofile", envir = environment())
}
