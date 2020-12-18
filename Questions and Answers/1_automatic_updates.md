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
![alt text](https://github.com/wpmarketingteam/WP5.6Marcomms/blob/master/Questions%20and%20Answers/images/auto-update-site-health-wp-cron-disabled.png "Shows the site health.")


## Q10. If I opt-in for automatic updates is it possible that my site will crash on the next update?
A.  As WordPress is modular, there is a chance that something might not be compatible with something else, which may cause issues! To help address this, the WordPress Core team recommends that everything be updated to its recent versions.  This will help improve the compatibility of all elements that comprise your WordPress site, and lower the probability of issues like crashes.

## Q11. I can’t see the Enable/Disable Auto-updates option in my WordPress admin?
A. After updating to WordPress 5.6, if you see the notice “This site will not receive automatic updates for new versions of WordPress”, and it is not followed by a link to turn on automatic updates, it might have been disabled by your hosting provider. In this case, you will need to contact your host for more information.

![alt text](https://github.com/wpmarketingteam/WP5.6Marcomms/blob/master/Questions%20and%20Answers/images/core-auto-updates-disabled-programatically.png "shows how to disable programtically auto updates.")


If you get the notice “This site appears to be under version control. Automatic updates are disabled.” - this is not a standard feature.
It means your website’s code might be managed by a version control system such as Git. In this case, please speak with your web developer. 



## Q12. What if I lose my internet connection during an automatic update?

A. If you lose your internet connection, it has no effect on the automatic updates. This is done completely independently of whether you are accessing the site or not. The updates are automatic, once they are set up, they need no interaction from your part.

***

## Questions and Answers - aimed at supporting Developers

### Q1. How do I disable automatic updates for core major versions?
A. It’s disabled by default for existing installations.
If you have enabled it before and changed your mind, just opt-out on the same Update section in your WordPress Dashboard. You also can use [constants or filter](https://make.wordpress.org/core/2020/11/24/core-major-versions-auto-updates-ui-changes-in-wordpress-5-6-correction/)  to do it programmatically.

![alt text](https://github.com/wpmarketingteam/WP5.6Marcomms/blob/master/Questions%20and%20Answers/images/core-major-auto-updates-default.png "Auto updates disabled Screenshot")

### Q2. How do I turn it off for the new installs?
A. The same way you can turn it off for an existing install through the newly introduced user interface in your WordPress Dashboard (Updates section) or [programmatically](https://make.wordpress.org/core/2020/11/24/core-major-versions-auto-updates-ui-changes-in-wordpress-5-6-correction/).

### Q3. What if I am developing locally and I run automatic updates?
A. These updates are performed between the virtual server on your system, and the server the plugins are being updated from. So if you are developing your site locally, and lose your connection (I.E You lose your connection to the web or you lose power etc)  or don’t have a connection during an auto update it will fail. You need to ensure you have a good stable connection to the web during updates.



***

#### Thanks to [Sabrina Zeidan](https://profiles.wordpress.org/sabrinazeidan/), [Christopher Churchill](https://profiles.wordpress.org/vimes1984/), [Abha Thakor](https://profiles.wordpress.org/webcommsat/), [Meher Bala](https://profiles.wordpress.org/meher/), [Olga Glekler](https://profiles.wordpress.org/oglekler/), [Angela Jin](https://profiles.wordpress.org/angelasjin/), [Daisy Oslen](https://profiles.wordpress.org/daisyo/) and all the release squad members who have given input into this document.

