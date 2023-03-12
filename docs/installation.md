## Installation

### Step 1 - Create a repository on GitHUB <https://github.com/username/mkdocs>

### Step 2 - Enable Discussions on Settings/General
### Step 3 - Open Visual Studio Code and Clone the repository you have created.
### Step 4 - Open a terminal on Visual Studio Code


Create a virtual environment first. Shift+Command+P --> Python : Create Environment --> .venv

```shell
pip install mkdocs-material
pip install mkdocs-mermaid2-plugin
pip install mkdocs-macros-plugin


# Then change directory to an upper folder.
cd ..
# Create your documentation site repo_name. Here my repo name is mkdocs
mkdocs new mkdocs
cd mkdocs
mkdocs gh-deploy
```

### Step 5 - Go to Settings/Pages on your repository. 

Choose gh-pages as your new branch 

![Settings-->Pages](assets/images/README.png)

Your site is live at (https://bbmorten.github.io/mkdocs/)