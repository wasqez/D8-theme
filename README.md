## Installation

`git clone git@github.com:wasqez/D8-theme.git projectx`

cd/projectx

`composer install`

## Install theme

cd web/themes/contrib/

`git clone git@github.com:wasqez/dexone.git`

## Usage

Run Drupal from Acquia DevDesktop. 
Need to select root folder: projectx/web
>Note: select php 7.x
Go to URL of your Local Site at the Acquia Dev Desktop panel and start your Drupal 8 installation at standard profile.

Install Drupal and visit your site.

## Theme settings
Go to Drupal Administration Appearance and install and set default Dexone theme.

Overrides:

* Go to admin/structure/types/manage/article/display

  Disable comments and tags fields and set image format style to Original image for Deault and Teaser display.
  
* Go to admin/structure/types/manage/article

  Under the Display settings tab uncheck Display author and date information.
  
* Go to admin/structure/block

  Set Headline region like this:
  
  -Main navigation
  
  -Site branding
  
  -Page title
  
  -Breadcrumbs
  
  
  Set Content region like this:
  
  -Primary admin actions
  
  -Main page content
  
  -Status messages
  
  
 Sidebar and Footer has no region blocks.
 
## Frontpage
 * Go to admin/structure/views/view/frontpage/edit
  Under Page Display set Pager to Mini and under Pager options set 1 item per page.

## Add Content

Add 3 Articles with Lorem ipsum text content, with images and provide Main navigation links for all 3.
>Note: Sample images for testing Article conent type, you can find under projectx\web\themes\contrib\dexone\img
>*drupal.jpg*
>*passion.jpg*
>*ride.jpg*

> Close Comment options for all 3 Articles.

Go to Home page.

