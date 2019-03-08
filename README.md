# discourse-popular-tag-sidebar

This theme component displays a category's most popular tags in a sticky sidebar on screens wider than 767px (most tablets and desktop devices). 

:warning: You must enable the `show filter by tag` setting on your site for this theme component to work.

![59%20PM|690x302](https://discourse-meta.s3.dualstack.us-west-1.amazonaws.com/original/3X/f/0/f047b707a1015a80ac945117ddcee32467d6a68b.png) 



:speech_balloon: https://meta.discourse.org/t/discourse-popular-tag-sidebar/107853

 :thinking: https://meta.discourse.org/t/how-do-i-install-a-theme-or-theme-component/63682


## What can I do with this theme component? 

* Display 3-30 Popular tags in a sidebar for each category

* Set the sidebar side to left or right

* Prevent the sidebar from appearing in certain categories

* Change the "Popular tags" header text

![55%20PM|690x381, 75%](https://discourse-meta.s3.dualstack.us-west-1.amazonaws.com/original/3X/6/d/6d0b6f0407280f040d0849a9227a607a553c32f8.png) 


## Custom CSS 

Each sidebar is wrapped with a class that contains the category name, so for the UX category that would be `.ux-sidebar`. You can use these classes to style individual sidebars. 

The html tag on pages with sidebars also has a class added so you can use `html.custom-sidebar` to apply styles on all pages that have a sidebar. 

