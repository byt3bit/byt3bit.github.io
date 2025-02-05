# How to use

### Your picture
Add you picture to `assets/img/` and change the `image` entry in `_pages/about.md` accordingly.

### Change the configuration
Modify the configuration entries in `_config.yml`. 

### Add and modify your publications
Upload your `.bib` file in `_bibliography`. 
In `_config.yml`, in the Jekyll scholar section, change the name of the file accordingly.


In your BIB file you can set an entry to be a selected publication by adding the tag `selected = {true}`.

If you want to modify the sorting or other settings, modify the correct entries in the Jekyll scholar section of the `_config.yml` file.

### Modify your pages
You can modify your pages in `_pages`. Just write simple Markdown.



# Deployment
Soon available.


# On your local machine

`gem install jekyll bundler`

`bundle exec jekyll build`

`bundle exec jekyll serve`

