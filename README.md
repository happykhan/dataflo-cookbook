# Welcome to the Data-flo Cookbook

[![Netlify Status](https://api.netlify.com/api/v1/badges/5c65c255-603d-4d8d-b1ab-c0f0040d0b76/deploy-status)](https://app.netlify.com/sites/dataflo-cookbook/deploys)

This is a *cookbook* for Data-flo. Available at https://happykhan.github.io/dataflo-cookbook/ or https://dataflo-cookbook.netlify.app/


## About Data-flo 

Data-flo (pronounced data-flow) is an open-source web application for data integration. It provides an easy-to-use visual interface to design reusable Workflows (data pipelines) that import, merge, clean, and manipulate data in many different ways. Once a Workflow has been created, it can be run anytime, by anyone with access, to enable push-button data extraction and transformation.

## Install and serve
```
# Clone the repo
git clone git@github.com:happykhan/dataflo-cookbook.git
cd dataflo-cookbook

python3 -m venv .venv
pip install mkdocs-material

mkdocs serve
```

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Other Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## How to contribute

Contributions are welcome, either via a direct commit or as a pull request. Recipes and tutorials are written in markdown in the `docs` folder. 

* Examples should be self contained examples, with all the required raw data. 
* Try to show one, perhaps two, features in a single example 
* Keep it brief 
* Copy and use the template in `recipe-template` for consistency. 

## Wishlist of recipe 

Please add ideas for recipe here. 

* Basic usage of data-flo 
* Deduplication of a table 
* Calculate days between two dates
* Geocoding
