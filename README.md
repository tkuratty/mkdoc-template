# MkDocs Template

This is a ready to go template for MkDocs site.  
Several extensions have already been set up.  

## Setup

```
git clone [to repo]
py -3.9 -m venv .venv
pip install -r requirements.txt
mkdocs serve

```

for mac to activate venv.  
```
source .venv/bin/activate
```

## GitHub Actions
This command does not work if you need to use a custom domain. 
```
mkdocs gh-deploy --force
```
Run a shell script instead of <gh-deploy> option for deploy pages in the page.yml.

## Recommended extensions for VSCode

- Markdown All in One
- Markdown Image
