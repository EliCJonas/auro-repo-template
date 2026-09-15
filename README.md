# auro-repo-template
A template to create an Auro repo of your own. Includes web UI!

## How to use:

### Step 1: Add Packages
To add a package, it is first recommended to clone this repository locally.
Once this is done, you can either:
make a .ikeg file yourself and add its name in pkgs.list 
OR
use my [ikeg-maker](https://github.com/EliCJonas/ikeg-maker) tool, which handles this itself.
```
cd path/to/the/pkgs/folder
ikeg-maker --url URL --description DESCRIPTION --author AUTHOR --repo . --version VERSION PACKAGE_NAME
```

### Step 2: Enable GitHub Pages
You will need to enable GitHub Pages on the 'main' branch.

### Step 3: Add instructions to add your repository
Here's an example:
```
auro add-repo mycoolrepo https://YOURNAME.github.io/YOURREPONAME/pkgs/
```

## And you're done! 🎉
