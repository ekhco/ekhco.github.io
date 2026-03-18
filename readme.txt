2026: 

Just update the MASTER html file and commit it to pudate the website.
-----

in Rstudio:
library(blogdown)
serve_site()

make edits in RStudio, then do this in terminal:

git add *
git commit -m "I updated my info to the config.toml"
git push
./deploy.sh



if git authentication problems, try personal access token:
g
