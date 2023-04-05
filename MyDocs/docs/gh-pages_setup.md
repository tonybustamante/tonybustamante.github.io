# Setting up github pages

## New Pages
```
pip install mkdocs
pip install mkdocs-material 
mkdocs new MyDocs

# choose one
mkdocs serve # This will run the server locally otherwise...
mkdocs build # this will generate the static files under ./site otherwise...
mkdocs gh-deploy # deploy will automatically generate and deploy static site to gh-pages branch
```

## Old site
```
# instead of mkdocs new, just run serve from repo
git clone <repo>
git serve # again, to preview
```

# make/deploy changes
```
# make changes by adding md pages to ./docs and updating mkdocs.yaml
```

