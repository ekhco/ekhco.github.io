make edits in RStudio, then do this in terminal:

git add *
git commit -m "I updated my info to the config.toml"
git push
./deploy.sh



also in Rstudio:
library(blogdown)
can serve_site()
