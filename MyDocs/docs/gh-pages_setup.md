# Setting up github pages

## New Pages
```
pip install mkdocs
pip install mkdocs-material 
mkdocs new MyDocs
mkdocs serve # This will run the server locally otherwise
mkdocs build # this will generate the static files under ./site
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
git build #
git add . 
git commit -m "message"
git push
- Remember to add site to .gitignore
```

