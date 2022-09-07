
in Rstudio:
library(blogdown)
serve_site()

make edits in RStudio, then do this in terminal:

git add *
git commit -m "I updated my info to the config.toml"
git push
./deploy.sh



