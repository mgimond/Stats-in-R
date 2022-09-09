There may be an issue where extrafonts cannot find the Architect's Daughter fonts. To resolve this:

remove.packages("Rttf2pt1")   
remotes::install_version("Rttf2pt1", version = "1.3.8") 