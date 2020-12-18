**Status: Version 2020/12/04. This is being finalized with the Release Squad.**

Finalization with the Release Squad.

# Automatic updates for major WordPress Core releases

### Key documents
https://make.wordpress.org/core/2020/11/24/core-major-versions-auto-updates-ui-changes-in-wordpress-5-6-correction/ 

***

## Questions and Answers - aimed at supporting Non-Developers 

### Q1. What does “Automatic Updates for major WordPress Core releases” mean for my website?
A. Automatic updates, often referred to as auto-updates, enables WordPress software to update itself to the latest version automatically. This means you will not need to check and install updates manually! Currently, and since version 3.7, WordPress by default will auto-update for minor releases. With the latest release of WordPress software, version 5.6, WordPress can  be configured to automatically update for major versions as well.
With 5.6, WordPress users will be able to opt-in or out of auto-updates for major WordPress software releases. This is done through the Updates screen in your WordPress Dashboard, and any site administrator can manage this new feature.

![alt text](https://github.com/wpmarketingteam/WP5.6Marcomms/blob/master/Questions%20and%20Answers/images/core-major-auto-updates-enabled-manually.png "Auto updates enabled manually Screenshot")

### Q2. Are auto-updates enabled by default?
A. For any new WordPress 5.6 installation, auto-updates are enabled by default. This means that your WordPress site will continue to keep itself up to date with each new version of WordPress! 
If you are updating your existing WordPress site to 5.6, you will need to opt-in to enable auto-updates for major WordPress Core releases. This can be done in the Updates screen in your WordPress dashboard. 
If you do not want to have your site auto-update, you can also turn off this feature in the Updates screen in the Dashboard.
Remember, auto-updates for minor releases are enabled by default since WordPress 3.7.


### Q4. Will auto-updates affect my site?
A. With a fresh install of WordPress 5.6, auto-updates will be enabled by default, meaning that your WordPress site will continue to regularly and automatically update to the latest minor and major versions of WordPress. You can choose to enable this feature if you are updating an existing site to WordPress 5.6. By enabling auto-updates, your website will always run the most secure version of WordPress available. 
If you don’t opt in to auto-updates, or, if you turn this feature off, your WordPress site will not be updated to the latest version unless you do so manually. 


## Q5. If I enable auto-updates for major WordPress core updates, will all my themes and plugins be updated automatically too?
A. No, they will not. Auto-updates for major WordPress core updates is related to updating the WordPress core software only. Plugins and themes allow users to customize their website by extension of core WordPress software, which is why plugins and themes are not considered a part of the core software  However, you can enable auto-updates for individual themes and plugins by turning on that setting in the Themes and Plugins sections in your Dashboard.


## Q6. Will my existing WordPress site be updated to the next major WordPress version automatically after 5.6?
A. For existing WordPress sites, only if you update to WordPress 5.6 and turn on auto-updates for major releases! Otherwise, your website will not be updated to the next major WordPress version automatically.  


## Q7. If I opt-in to auto-updates, will I know when my website gets updated to the latest version of WordPress?
A. Yes! With auto-updates enabled, after the WordPress software updates itself to the latest version, you will receive an email notification. Notifications are sent to the email address saved as the administration email address, found under Settings-> General-> Administration Email Address. Please note that this email address could be different from the one which is saved as your user’s email address.


## Q8. How soon will my WordPress be auto-updated after a new version is released?
A. After a new version of WordPress is released, it will take no longer than 12 hours before it is auto-updated on your installation!


## Q9.  I opted-in to auto-updates but they don’t work?
A.  WordPress uses a tool called “WP Cron”, which handles scheduled events (such as regularly checking for the latest version of WordPress software!) for your website. If your auto-updates aren’t working,  You can check whether WP Cron is enabled via the site health  under dashboard tools as seen in this photo: 
![alt text](https://github.com/wpmarketingteam/WP5.6Marcomms/blob/master/Questions%20and%20Answers/images/wordpress-site-health-1.png "Shows the site health.")


## Q10. If I opt-in for automatic updates is it possible that my site will crash on the next update?
A.  As WordPress is modular, there is a chance that something might not be compatible with something else, which may cause issues! To help address this, the WordPress Core team recommends that everything be updated to its recent versions.  This will help improve the compatibility of all elements that comprise your WordPress site, and lower the probability of issues like crashes.


### Q. How is this different from what it was before?
A. This feature follows plugins and themes auto-updates user interface which was shipped in WordPress 5.5.

Currently, by default, WordPress auto-updates itself, but only for minor releases. With this option enabled WordPress will be automatically updated for major versions as well.  

The feature of auto-updating core to major versions has been in WordPress for years. 
But now it will be accessible not only for developers but also via user interface located on the Updates screen. Therefore, site admin can opt-in to automatic updates for major versions easily and have their website automatically kept up to date with each new version of WordPress.




### Q. Are auto-updates enabled by default?
A. For new WordPress installations: yes, it’s enabled by default.

For existing WordPress installations (if you are updating your existing site to 5.6): no, you must opt-in to enable Automatic updates for major WordPress Core releases. 

Note: automatic updates for minor releases are enabled by default since WordPress 3.7.

### Q. Why enable auto-updates?
A. WordPress core development is an ongoing process. New exciting features are introduced to make work with WordPress more easy, more productive, more fun. Latest performance techniques are applied to make your website load fast. But what is more important: new vulnerabilities are discovered and fixed in a timely manner to keep millions of websites that use WordPress as safe as possible.

By having automatic updates enabled you ensure your website is running on the most secure version available.


### Q. Will this feature affect my site?
A. Unless you opted-in, it will not do so.
If you did opt-in, you will get WordPress core automatically updated not only to minor versions as it was before but to major versions, as well. This way you can ensure your website is running on the most secure version of WordPress available.


### Q. Will all my themes and plugins be updated automatically once I enable this?
A. No, they will not. This setting is related to updating WordPress core only.
And as translations are hosted on WordPress.org this enables automatic updates of core, themes and plugin translations.
To enable automatic updates for themes and plugins set them in Themes and Plugins sections accordingly in your Dashboard.


### Q. Will my site be updated to the next major WordPress version automatically after 5.6?
A. No, this option is not enabled by default for existing WordPress installations.
So in order to have your website automatically staying up to date you need to enable auto-updates in Updates section in your WordPress Dashboard.


### Q. Will I know when my website gets updated?
A. Yes, after WordPress core automatic update is done you will receive an email notification to an email address saved as the administration one  under Settings-> General-> Administration Email Address.
Please note, it might be different from the one which is saved as your user’s email address.


### Q. How soon will my WordPress be updated after a new version is released?
A. Every WordPress site checks for updates twice a day. So after a new version of WordPress is released, it will take no longer than 12 hours before it is updated on your installation.


### Q. I opted-in to auto-updates but they don’t work?
A. To check for updates WordPress uses [WP Cron](https://developer.wordpress.org/plugins/cron/), it handles all scheduled events for your installation. Make sure you don’t have it disabled and it’s operationable on your install.


### Q. If I opt-in for automatic updates is it possible that my (or worse, my client’s site) site will crash on the next update?
A. Due to a modular nature of WordPress there is always a chance that something might not be compatible with something else, and this may cause issues. 
The best possible compatibility between WordPress core, server side software, plugins and themes - is provided by having everything updated to its recent versions. 
Therefore, automatic updates feature is specifically aimed to improve the compatibility of all elements and lower the probability of such issues.


### Q. I can’t see the Enable/Disable Auto-updates option in my WordPress admin?
A. If you see the notice “This site will not receive automatic updates for new versions of WordPress” that is not followed by a link to enable automatic updates it might have been disabled by your host - you should contact them.

![alt text](https://github.com/wpmarketingteam/WP5.6Marcomms/blob/master/Questions%20and%20Answers/images/core-auto-updates-disabled-programatically.png "Updates disabled programmatically Screenshot")

If you get the notice “This site appears to be under version control. Automatic updates are disabled.” it means you have some kind of version control software active on your website (can be handled in different ways - by plugins, cPanel, directly from your host etc) and auto-updates won’t be enabled.

### Q. What if something goes wrong during automatic update? 
A. You will receive an email notification saying “Your Site is Experiencing a Technical Issue” just like in any other case of technical issues.


### Q. Will I be able to roll back to the previous version? 
This is not a recommended way to solve issues, but in case of emergency you could use one these plugins: https://wordpress.org/plugins/wp-downgrade/ or https://github.com/afragen/core-rollback/

***

## Questions and Answers - aimed at supporting Developers

### Q. How do I disable automatic updates for core major versions?
It’s disabled by default for existing installations.
If you have enabled it before and changed your mind, just opt-out on the same Update section in your WordPress Dashboard. You also can use [constants or filter](https://make.wordpress.org/core/2020/11/24/core-major-versions-auto-updates-ui-changes-in-wordpress-5-6-correction/)  to do it programmatically.

![alt text](https://github.com/wpmarketingteam/WP5.6Marcomms/blob/master/Questions%20and%20Answers/images/core-major-auto-updates-default.png "Auto updates disabled Screenshot")

### Q. How do I turn it off for the new installs?
The same way you can turn it off for an existing install through the newly introduced user interface in your WordPress Dashboard (Updates section) or [programmatically](https://make.wordpress.org/core/2020/11/24/core-major-versions-auto-updates-ui-changes-in-wordpress-5-6-correction/).

***

#### Thanks to [Sabrina Zeidan](https://profiles.wordpress.org/sabrinazeidan/), [Christopher Churchill](https://profiles.wordpress.org/vimes1984/), [Abha Thakor](https://profiles.wordpress.org/webcommsat/), [Meher Bala](https://profiles.wordpress.org/meher/), [Olga Glekler](https://profiles.wordpress.org/oglekler/), [Angela Jin](https://profiles.wordpress.org/angelasjin/), [Daisy Oslen](https://profiles.wordpress.org/daisyo/) and all the release squad members who have given input into this document.

