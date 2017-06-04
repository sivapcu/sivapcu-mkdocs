# sivapcu-mkdocs

This project is developed using [mkdocs.org](http://mkdocs.org). This is the source project for [sivapcu.github.io](http://sivapcu.github.io). 

## Developer Guide
1. Install python
    1. Don't forget to add the python to path
2. Verify the installation by runing the below commands.
    1. python --version
    2. pip --version
3. Upgrade pip to latest version using the below command
    1. pip install --upgrade pip
4. Install mkdocs using the command below
    1. pip install mkdocs
5. Install the mkdocs-material theme
    1. pip install mkdocs-material
6. Run the application using the below command.
    1. mkdocs serve
    
## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs help` - Print this help message.

## Deployment

* `mkdocs build` command generates the directory `site`. 
* Copy and push the contents of this directory to `sivapcu.github.io` repository.
* Visit [sivapcu.github.io](http://sivapcu.github.io) to find the new content deployed automatically.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.
