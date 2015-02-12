# eclipse-templates
eclipse-templates

----------------

To pull in a new repository, often you simply just:
git clone https://github.com/gar2000b/eclipse-templates.git

Note: these are the steps you take after you have checked out these template projects.
If however, you wish to checkout into a pre-existing directory where you may have additional setup you didn't intend to reside in the repo (like eclipse project templates), then do the following:

clone the template(from this checked out project): cp -R ulysses-luna eejava
navigate to directory: cd eejava
Then initialise with: git init
Add remote: git remote add origin https://github.com/gar2000b/eejava.git
Then pull from existing repo: git pull origin master
->
Do an initial push when ready: git push -u origin master

^ then the normal flow can continue as usual.
