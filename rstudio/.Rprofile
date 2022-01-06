# Welcome Message 
message("")
message("=========================================================================================================================")
message("=========================================================================================================================")
message("")
message("[R SESSION]: R Engine started.")
message("")
message("")
message("[R SESSION]: Packages fs, data.table, arrow, ggplot2 already loaded into the session.")
message(" ")
message(" ")
message("[R SESSION]: To change your RStudio theme type:")
message("[R SESSION]: rstudioapi::addTheme(file.path('rstudio', 'material_dark.rstheme'), apply = TRUE, force = TRUE, globally = FALSE)")
message(" ")
message("=========================================================================================================================")
message("=========================================================================================================================")
message(" ")
message(" ")

# My Options 
options(papersize = "a4")
options(editor = "sublime")
options(pager = "internal")
options(prompt = "R > ")
options(scipen = 10)
options(digits = 3)
options(max.print = 50)
options(continue = "    ")

# R CRAN Mirror 
local({
     r = getOption("repos")           
     r["CRAN"] = "https://cran.rstudio.com/"
     options(repos = r)
})


# LIBRARY FOR PIPES
suppressWarnings(suppressMessages(library("data.table", warn.conflicts = FALSE, quietly = TRUE)))
suppressWarnings(suppressMessages(library("ggplot2", warn.conflicts = FALSE, quietly = TRUE)))
suppressWarnings(suppressMessages(library("fs", warn.conflicts = FALSE, quietly = TRUE)))
suppressWarnings(suppressMessages(library("arrow", warn.conflicts = FALSE, quietly = TRUE)))
