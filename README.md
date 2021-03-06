# Markus Sagen homepage

- Features that can be included:
  - [Link to wowchemy](https://wowchemy.com/docs/guide/search/)

## Pre-requisite
``` sh
# install hugo
brew install hugo

# Run the Hugo pages locally
cd main
hugo server
```

## Structure

``` text
main 
|
|__config
|   |___default
|       |__config.toml
|       |__languages.toml
|       |__menus.toml
|       |__params.toml
|
|__content
|   |__authors/authors/_index.md
|   |__courses
|   |   |___index.md
|   |   |__example
|   |   |   |___index.md
|   |   |   |__example1.md
|   |   |   |__example2.md
|   |   |
|   |   |__example.1
|   |       |___index.md
|   |       |__example3.md
|   |       |__example4.md
|   |
|   |__home
|   |   |__gallery
|   |   |   |__index.md
|   |   |   |__gallery
|   |   |       |__LOTS OF IMAGES.png
|   |   |   
|   |   |__index.md
|   |   |__about.md
|   |   |__accomplishment~.md
|   |   |__contract.md
|   |   |__experience.md
|   |   |__featured.md
|   |   |__hero.md
|   |   |__people.md
|   |   |__posts.md
|   |   |__projects.md
|   |   |__publications.md
|   |   |__skills.md
|   |   |__slider.md
|   |   |__tags.md
|   |   |__talks.md
|   |
|   |__post
|   |   |___index.md
|   |   |__getting-started
|   |   |   |__index.md
|   |   |   |__gallery/gallery/...
|   |   |   |__featured.jpg
|   |   |
|   |   |__jupyter
|   |   |   |__index.md
|   |   |   |__academia.jpg   
|   |   |   |__featured.jpg
|   |   |
|   |   |__snail
|   |      |__index.md
|   |      |__gallery/gallery/...
|   |      |__featured.jpg
|   |
|   |__project
|   |   |__artificial-inteligence
|   |   |   |__index.jpg
|   |   |   |__featured.jpg
|   |   |
|   |   |__deep-learning
|   |   |   |__index.jpg
|   |   |   |__featured.jpg
|   |   |
|   |   |__external-project
|   |   |   |__index.jpg
|   |   |   |__featured.jpg
|   |   |
|   |   |__internal-project
|   |   |   |__index.jpg
|   |   |   |__featured.jpg
|   |   |
|   |   |__robotics
|   |   |   |__index.jpg
|   |   |   |__featured.jpg
|   |   |
|   |   |__Skin-Cancer-AI
|   |       |__index.jpg
|   |       |__featured.jpg
|   |
|   |__publication 
|   |   |___index.md
|   |   |__conference-paper
|   |   |   |__index.jpg
|   |   |   |__featured.jpg
|   |   |
|   |   |__journal-article 
|   |   |   |__index.jpg
|   |   |   |__featured.jpg
|   |   |
|   |   |__preprint 
|   |       |__index.jpg
|   |       |__featured.jpg
|   |
|   |__slides
|   |   |__example 
|   |       |__index.md
|   |
|   |__talk
|   |   |___index.md
|   |   |__Coding
|   |   |  |__index.jpg
|   |   |  |__featured.jpg
|   |   |
|   |   |__Qialitative
|   |   |   |__index.jpg
|   |   |   |__featured.jpg
|   |   |
|   |   |__Syntesizing
|   |       |__index.jpg
|   |       |__featured.jpg
|   |    
|   |__privacy.md
|   |
|__resources
|   |___gen
|       |__assets
|       |   |__scss
|       |       |__sass
|       |           |__main.scss.XXX.content
|       |           |__main.scss.XXX.json|
|       |
|       |__images
|           |__home
|           |   |__gallery/gallery/...
|           |__post
|           |   |__getting-started
|           |   |   |__gallery/gallery/...
|           |   |   |__featured_XXX~.jpg
|           |   |   |__featured_XYZ~.jpg
|           |   |
|           |   |__jupyter
|           |   |   |__featured_XXX~.jpg
|           |   |   |__featured_XYZ~.jpg
|           |   |
|           |   |__snail
|           |   |   |__gallery/gallery/...
|           |   |   |__featured_XXX~.jpg
|           |   |   |__featured_XYZ~.jpg
|           |   |
|           |__project
|           |   |__artificial-inteligence
|           |   |   |__featured_XXX~.jpg
|           |   |   |__featured_XYZ~.jpg
|           |   |
|           |   |__deep-learning
|           |   |   |__featured_XXX~.jpg
|           |   |   |__featured_XYZ~.jpg
|           |   |
|           |   |__external-project
|           |   |   |__featured_XXX~.jpg
|           |   |   |__featured_XYZ~.jpg
|           |   |
|           |   |__internal-project
|           |   |   |__featured_XXX~.jpg
|           |   |   |__featured_XYZ~.jpg 
|           |   |
|           |   |__robotics
|           |   |__featured_XXX~.jpg
|           |   |__featured_XYZ~.jpg
|           |   
|           |__Skin-Cancer-AI
|           |    |__featured_XXX~.jpg
|           |    |__featured_XYZ~.jpg
|           |
|           |__publication
|           |   |__conference-paper
|           |   |   |__featured_XXX~.jpg
|           |   |   |__featured_XYZ~.jpg
|           |   |
|           |   |__journal-article 
|           |   |   |__featured_XXX~.jpg
|           |   |   |__featured_XYZ~.jpg
|           |   |
|           |   |__preprint 
|           |       |__featured_XXX~.jpg
|           |       |__featured_XYZ~.jpg
|           |
|           |__talk 
|               |__conference-paper
|               |   |__featured_XXX~.jpg
|               |   |__featured_XYZ~.jpg
|               |   |__featured_YYY~.jpg
|               |__journal-article 
|               |   |__featured_XXX~.jpg
|               |   |__featured_XYZ~.jpg
|               |   |__featured_YYY~.jpg
|               |__preprint 
|                   |__featured_XXX~.jpg
|                   |__featured_XYZ~.jpg
|                   |__featured_YYY~.jpg
|
|__static
|   |__img
|       |__board.jpg
|       |__certificate.jpg
|       |__user-2.jpg
|       |__user-full-2.jpg
|       |__user-full.jpg
|       |__user.jpg
|
|__themes
    |__archetypes/...
    |__assets/...
    |__data/...
    |__exampleSite/...
    |__i18n/...
    |__images/...
    |__layouts/...
    |__scripts/...
    |__static/...
    |__demo.sh
    |__LICENCE.md
    |__package-lock.json
    |__package.json
    |__README.md
    |__theme.toml
    
____________________________

```

### INFO
- main/config/_default/config.toml  
  - Theme and website URL
- main/config/_default/menus.toml  
  - Show what items should be displayed in the clickable menu
- main/config/_default/params.toml  
  - Color themes, Twitter, Contact info, analytic and general info

