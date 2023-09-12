# mkdocs_skeleton

This project is a skeleton base for a Github project that includes an mkdocs documentation site (hosted using Github Pages). 

To create this project, the following was performed: 

## Install Required Packages
You can view the required packages from environment.yml

## Create MKDocs Project Files
Activate your python environment (with necessary packages installed), then run the following in the from the project folder: 
> mkdocs new .

Then, inside the newly-created mkdocs.yml file in your project, add the following (at minimum):
theme: 
    name: material

## Publish Site
Run the following (from the directory containing mkdocs.yml file):
> mkdocs gh-deploy --force


## Push Changes & Wait
Push all your changes to the remote (main) repository. It make take a few minutes for your site to become active. 



### MKDocs - Further References

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.
