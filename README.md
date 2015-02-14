DISQUS
===========

CONTENTS OF THIS FILE
---------------------

 - Introduction
 - Requirements
 - Installation
 - Permissions
 - Usage
 - Sponsors

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

Features

* The possibility of choosing the content types that can be added to the cart.
* The possibility of sending, or not, an email to the customer once an order is placed.
* Custom email messages for both the site administrator and the customer, along with the order details.
* A block with the contents of your shopping cart.

TESTED
-----

Not Working in Backdrop 1.0


KNOWN ISSUES
---------------------

None critical for Backdrop yet.

Basic Cart for Drupal stored node objects in the user $_SESSION variable and used pre-made Views, Features, etc...
The Backdrop port failed with this error because of it:
Fatal error: Call to undefined function module_implements() in /Applications/MAMP/htdocs/backdrop/core/includes/bootstrap.inc on line 3467
This happens when you add a product to the cart.

Basic Cart for Backdrop stores node id's as strings in the user $_SESSION variable and no pre-made etc...

REQUIREMENTS
------------

@todo

INSTALLATION
------------

@todo

Scott from Level Up Tuts put together a great tutorial on how to install Disqus on Drupal 7. He walks you through these steps:

<http://www.youtube.com/watch?feature=player_embedded&v=QAdjQaq9jxo>

Download and install the Disqus module into your respective sites directory (sites/all/modules).
Enable the module in admin/build/modules
Register your site at Disqus.com
Visit admin/settings/disqus and set your configuration options depending on what you registered with on Disqus, as well as what node types you'd like Disqus comments to be present on.
Enable the "view disqus comments" permission at admin/user/access or admin/user/permission for users you'd like to see the comments
Visit admin/build/block to show some Disqus information in the block regions
Disable Drupal commenting on the content types for which you have Disqus enabled. This will prevent Drupal comments from being open on new posts.
(optional) Disable permissions for site visitors to use Drupal comments. This is recommended if you are replacing all new comments on your site with the Disqus system. Otherwise, comments will remain open on your existing content
(optional) Install the Global Redirect module to enable URL Alias redirects with links from Disqus

Because the libraries module/concept is not yet set or taught, the actual Braintree code library is packaged with this module until a 3rd-party code library is agreed upon in Backdrop.

PERMISSIONS
------------

@todo

USAGE
-----

@todo

You will need to install the Libraries API module.

https://drupal.org/project/libraries

The Disqus Official PHP API can be downloaded at:

https://github.com/disqus/disqus-php

Copy the contents of the disqusapi folder to sites/all/libraries/disqusapi.
You will need to obtain your user access key from the application specific
page found here:

http://disqus.com/api/applications/

License
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.

Maintainers
-----------
Sponsors include Disqus, ImageX Media, AETN, Acquia and Examiner.com.

Current Maintainers on Drupal:

JayeshSolanki <https://www.drupal.org/u/jayeshsolanki>

slashrsm <https://www.drupal.org/u/slashrsm>

marcingy <https://www.drupal.org/u/marcingy>

RobLoach <https://www.drupal.org/u/robloach>

bkosborne <https://www.drupal.org/u/bkosborne>

Ported to Backdrop by:

 - biolithic <https://github.com/biolithic>
