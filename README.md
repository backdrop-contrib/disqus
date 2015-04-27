DISQUS
===================

CONTENTS OF THIS FILE
---------------------

 - Introduction
 - Tested
 - Known Issues
 - Special Thanks
 - Requirements
 - Installation
 - Coming From Drupal?
 - Usage
 - License
 - Credits
 - Maintainers

INTRODUCTION
------------

DISQUS is a comments platform that helps you build an active community from your website's audience. It has awesome features, powerful tools, and it's easy to install.

Display recent comments, popular threads, and other widgets in blocks
Provide comments on any node type or user
Views 2/3 integration (number of comments)
Single Sign-On

Threaded comments and replies
Notifications and reply by email
Subscribe and RSS options
Aggregated comments and social mentions
Powerful moderation and admin tools
Full spam filtering, blacklists and whitelists
Support for Disqus community widgets
Connected with a large discussion community
Increased exposure and readership

This module can automatically update and/or delete your Disqus threads when you
delete/update your nodes.

Visit Disqus configuration page after you installed Disqus API to configure it's
behaviour.


TESTED
-----

Simple Working in Backdrop 1.0 -- needs more testing with real accounts and copious content


KNOWN ISSUES
---------------------

None critical for Backdrop yet.


SPECIAL THANKS
--------------

Sponsors include Disqus, ImageX Media, AETN, Acquia and Examiner.com.

REQUIREMENTS
------------

none

INSTALLATION
------------

Install this module using the official Backdrop CMS instructions at https://backdropcms.org/guide/modules

Scott from Level Up Tuts put together a great tutorial on how to install Disqus. He walks you through these steps:

<http://www.youtube.com/watch?feature=player_embedded&v=QAdjQaq9jxo>

<<<<<<< HEAD
Register your site at Disqus.com

Visit admin/settings/disqus and set your configuration options depending on what you registered with on Disqus, as well as what node types you'd like
Disqus comments to be present on.
=======
Download and install the Disqus module into your respective sites directory (sites/all/modules).

Enable the module in admin/build/modules

Register your site at Disqus.com

Visit admin/settings/disqus and set your configuration options depending on what you registered with on Disqus, as well as what node types you'd like Disqus comments to be present on.
>>>>>>> 580eb7b8010713dd9d32b78ce74f124312006154

Enable the "view disqus comments" permission at admin/user/access or admin/user/permission for users you'd like to see the comments

Visit admin/build/block to show some Disqus information in the block regions

<<<<<<< HEAD
Disable normal commenting on the content types for which you have Disqus enabled. This will prevent normal comments from being open on new posts.

(optional) Disable permissions for site visitors to use normal comments. This is recommended if you are replacing all new comments on your site with the Disqus system. Otherwise, normal comments will remain open on your existing content
=======
Disable Backdrop commenting on the content types for which you have Disqus enabled. This will prevent Backdrop comments from being open on new posts.

(optional) Disable permissions for site visitors to use Backdrop comments. This is recommended if you are replacing all new comments on your site with the Disqus system. Otherwise, comments will remain open on your existing content
>>>>>>> 580eb7b8010713dd9d32b78ce74f124312006154

(optional) Install the Global Redirect module to enable URL Alias redirects with links from Disqus

Because the libraries module/concept is not yet set or taught, the actual Disqus code library is packaged with this module until a 3rd-party code library is agreed upon in Backdrop.
<<<<<<< HEAD


COMING FROM DRUPAL?
-------------------

Nothing substantially different.
=======
>>>>>>> 580eb7b8010713dd9d32b78ce74f124312006154

PERMISSIONS
------------

@todo


USAGE
-----

@todo

LICENSE
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for complete text.

CREDITS
-----------

This module is based on the Disqus module for Drupal, originally written and maintained by a large number of contributors, including:

Current Maintainers on Drupal:

JayeshSolanki <https://www.drupal.org/u/jayeshsolanki>

slashrsm <https://www.drupal.org/u/slashrsm>

marcingy <https://www.drupal.org/u/marcingy>

RobLoach <https://www.drupal.org/u/robloach>

bkosborne <https://www.drupal.org/u/bkosborne>

MAINTAINERS
-----------

- seeking

Ported to Backdrop by:

 - biolithic <https://github.com/biolithic>
