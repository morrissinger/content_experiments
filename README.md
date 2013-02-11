Content Experiments
====================

This module allows a Drupal site administrator to create Google Content Experiments within
a Drupal site. It is in extreme alpha (if there ever were such a thing). What this means
is that it does what is to be expected, most of the time, and that known bugs cause
frustration for users, but there are known workarounds. It also means that the user
interface is extremely minimal and is limited.

In short, this module allows users to insert Google Content Experiments code into their
sites, which appears in the header of the page in the appropriate place. A user should
simply paste the code provided by Google Content Experiments into the box on the node
edit form for the node consisting of the control page.

Note: the site administrator will have to add the following line immediately after
the `<head>` tag on the theme's html.tpl.php file, in order for the module to work:

    <?php if (module_exists('content_experiments')) { print content_experiments_code(); } ?>

Once the module is enabled and this line of code appears in html.tpl.php, the user can
navigate to the node edit form for any existing node or for any new node the user
wishes to create, and scroll to the bottom and paste Content Experimemnts code in the
Content Experiments tab, which should appear above the "Publishing Options" tab.

This module is destined for numerous improvements or deprication, but what it does do,
at the time of this writing, is fill a gaping need for Drupal users who want to do
A/B testing with Google Content Experiments.
