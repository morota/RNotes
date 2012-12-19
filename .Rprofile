##
## My ~/.Rprofile
##

.First <- function(){
  if (interactive()){
   suppressPackageStartupMessages(require(fortunes))
   print(fortune())
   }
}

.Last <- function(){
  if (interactive()){
    system(paste("cowsay", date()))
  }
}

options("repos" = c(CRAN = "http://cran.r-project.org/"))
options(prompt="R> ", digits=5, show.signif.stars=FALSE)
options(help_type = "text")
options(browser = "/usr/bin/google-chrome")

# enable auto-complete package names
utils::rc.settings(ipck=TRUE) 

#options(showWarnCalls=TRUE, showErrorCalls=TRUE)
#options(download.file.method="/usr/bin/wget")
#options("pdfviewer"="evince") 
