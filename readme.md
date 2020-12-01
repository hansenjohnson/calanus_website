# calanus_website
Simple website for coordinating Calanus datasets in the NW Atlantic

This project is in *active* development. The draft website is currently live [here](https://hansenjohnson.github.io/calanus_website/)

## Updating

1. Make changes  
    * Content is easy. Simply edit markdown files in the `content` directory
    * Formatting is hard. This could be to the html (in `layouts`). The default formatting is pulled from `themes/compose/`. To change any defaults, first copy the file to the main directory  

2. Preview changes
    * The easiest way to do this is to set `baseURL = ""` in `config.toml`, then run `hugo server` in the terminal and view the site in a web browser. Be sure to change the `baseURL = "/calanus_website"` prior to publishing any changes to GitHub
    * **Note**: image paths need to be changed for preview versus deployment. Add `/calanus_website/` as a prefix to the image file path for deployment

3. Update site    
    * Commit the change to content/formatting to `git` with a descriptive commit message(s)
    * Run `hugo` in the terminal to generate the static web page (in the `docs` directory)
    * Commit the static site updates to git using a commit message like `update site`
    * Push updates to GitHub

## About

The site was built in [Hugo](https://gohugo.io/) using the [Compose theme](https://docs.neuralvibes.com/)