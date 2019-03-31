##Installation

`git clone git@github.com:wasqez/D8-theme.git projectx`

cd/projectx

`composer install`

#Install theme

cd web/themes/contrib/dexone/

`git clone git@github.com:wasqez/dexone.git`

## Usage

Run Drupal from Acquia DevDesktop. 
Need to select root folder: projectx/web


## Theme settings
Go to Drupal Administration Appearance and install and set default Dexone theme.

Overrides:

* Go to admin/structure/types/manage/article/display

  Disable comments and tags fields for Deault and Teaser display, and set image format to Original image
  
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
  
  -Status messages
  
  -Main page content
  
  
 Sidebar and Footer has no region blocks.
 
## Frontpage
 * Go to admin/structure/views/view/frontpage/edit
  Under Page Display set Pager to Mini and under Pager options set 1 item per page.

## Add Content

Add 3 Articles with Lorem ipsum text content, with images and provide Main navigation links for all 3.
>Note: Sample images for testing Article conent type, you can find under projectx\web\themes\contrib\dexone\img
*drupal.jpg
*passion.jpg
*ride.jpg

Go to Home page.

