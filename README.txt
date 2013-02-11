Content Experiments
====================

This module allows a Drupal site administrator to create Google Content Experiments within
a Drupal site. It is in extreme alpha (if there ever were such a thing). What this means
is that it does what is to be expected, most of the time, and that known bugs cause
frustration for users, but there are known workarounds. It also means that the user
interface is extremely minimal and is limited.

In short, this module allows users to insert Google Content Experiments IDS into their
sites, which generate valid Google Content Experiments JavaScript in the header of the
pages in the appropriate place. A user should simply paste the Experiment ID provided by
Google Content Experiments into the box on the node edit form for the node consisting of
the control page.

Once the module is enabled, the user can navigate to the node edit form for any existing
node or for any new node the user wishes to create, and scroll to the bottom and paste
Content Experimemnts code in the Content Experiments tab, which should appear above the
"Publishing Options" tab.

This module is destined for numerous improvements or deprication, but what it does do,
at the time of this writing, is fill a gaping need for Drupal users who want to do
A/B testing with Google Content Experiments.
