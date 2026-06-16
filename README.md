# Edit content/config

## Steps of revision:
1. Revise .rmd file, Save, Knit
2. Run command blogdown::build_site() in console to rebuld site
3. Commit push in github

## Don't change the directory of local github files!!!

## Settings-page: check DNS status

## rebuild site
hugo
## commit generated docs
git add .
git commit -m "Update site"
git push
