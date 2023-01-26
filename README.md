# README

Generate static build:

`npm run build`

Publish to GitHub Pages with:

`git subtree push --prefix dist origin gh-pages`

Add git submodule on the [developer-website](https://github.com/opengeospatial/developer-website):

`git submodule add -b gh-pages https://github.com/opengeospatial/dev-ogc-org-sprint-landing-19.git sprints/19`

Update git submodule:

`git submodule foreach git pull origin gh-pages`

Available at:

`https://developer.ogc.org/sprints/19`

