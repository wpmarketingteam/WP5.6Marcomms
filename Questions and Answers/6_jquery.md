**Status: Version 2020/11/25. THIS DOCUMENT IS IN DRAFT.**

# jQuery

Updates to jQuery in WordPress take place across three releases 5.5, 5.6 and 5.7.
https://make.wordpress.org/core/2020/06/29/updating-jquery-version-shipped-with-wordpress/   

Before updating to 5.6, you should preemptively check your sites using the update test plugin: https://wordpress.org/plugins/wp-jquery-update-test/    
This will help you find errors which can occur after an update.

This update test plugin will help you find errors which can occur after an update.

The WordPress Core team recommends that you install the jQuery Migrate plugin if you encounter any issues relating to the visual aspects of your site after updating (for example, if a slider doesn’t work, a button is stuck, etc). This is because some plugins and theme JavaScript code on your website could result in some broken sites. [[https://wordpress.org/plugins/enable-jquery-migrate-helper/ ]]


***

## Questions and Answers - aimed at supporting Non-Developers 

### Q1  After updating to the 5.6 version of WordPress I am experiencing issues with unexpected behavior on my site. What can I do about these issues?

: If you updated to WordPress 5.6, and you are experiencing issues with scripts on your site, such as being unable to save changes to the WordPress Dashboard, broken sliders or buttons that are unclickable, there are a few things you can try. 

The WordPress.org Core team developed a plugin that can help mitigate these issues by re-enabling the first file that was removed in WordPress 5.5, giving plugin and theme authors time to perform the needed updates. This plugin is called “Enable jQuery Migrate Helper” and can be found at: https://wordpress.org/plugins/enable-jquery-migrate-helper/.  After installing this plugin, many people have found that a lot of the errors developed during the 5.6 update disappear. If you want to get ready for the updates you can do so by making sure your site is compatible with the full jQuery update. 

![Enable jQuery Migrate Helper plugin settins page](https://github.com/wpmarketingteam/WP5.6Marcomms/blob/master/Questions%20and%20Answers/images/jquery-migrate-plugin.png  "Enable jQuery Migrate Helper plugin settins page")
After installation of the plugin to reverse changes in WordPress 5.6, you need to go to “Dashboard > Tools > jQuery Migrate” and change jQuery Version to “Legacy 1.12.4-wp”.

### Q2. How do I make sure my site is ready for the full jQuery update? 

A: To test your site ready for jQuery:
1. Install and activate the “Test jQuery Updates” plugin: https://wordpress.org/plugins/enable-jquery-migrate-helper/
2. Configure the plugin by going to Plugins -> Test jQuery Updates in your WordPress site’s admin panel (dashboard): https://wordpress.org/plugins/wp-jquery-update-test/ 
3. In the “Test jQuery Updates” plugin, set the options as below:
 - jQuery version: leave it at the default 
 - jQuery Migrate: Disable
 - jQuery UI version: Default

All of these tests should be done on a staging or development site, so you don’t break your live site. 

More information on how to do this can be found on the plugin page. [https://wordpress.org/plugins/wp-jquery-update-test/](https://wordpress.org/plugins/wp-jquery-update-test/)












### Q. How can I help test this? 
A: You can follow the guide laid out here: https://make.wordpress.org/core/2020/06/29/updating-jquery-version-shipped-with-wordpress/ 
If you run into any issues that aren’t already documented please reach out on the core.trac ticket: https://core.trac.wordpress.org/ticket/50564

***

## Questions and Answers - aimed at supporting Developers 

### Q: Why is WordPress updating jQuery?
A: WordPress is planning during the three releases 5.5, 5.6 and 5.7 to phase out an old, unsupported version of the popular front-end JavaScript library “jQuery”. 

During this transition period, Plugin and theme authors are obliged to take it upon themselves to update their own themes / plugins to the latest version of jQuery, this may cause some issues.

### Q: After updating to  the 5.6 version of WordPress I am experiencing issues regarding scripts and the unexpected behavior of elements on my site. What do I need to do?

A: I updated to WordPress 5.6 and now something went wrong with scripts on my site
 - I updated to WordPress 5.6 and now I cannot save anything in the admin
 - I updated to WordPress 5.6 and sliders on my pages don’t work
 - ETC
 
The WordPress.org core team has put together a plugin to re-enable the first file that was removed in 5.5 to help mitigate these issues and give the plugin and theme authors time to perform the needed updates. This plugin is called “Enable jQuery Migrate Helper” and can be found at: https://wordpress.org/plugins/enable-jquery-migrate-helper/
After installing this plugin, many people have found that a lot of the errors they have developed during the 5.5 update have disappeared.

![Enable jQuery Migrate Helper plugin settins page](https://github.com/wpmarketingteam/WP5.6Marcomms/blob/master/Questions%20and%20Answers/images/jquery-migrate-plugin.png  "Enable jQuery Migrate Helper plugin settins page")


After installation of the plugin to reverse changes in WordPress 5.6, you need to go to “Dashboard > Tools > jQuery Migrate” and change jQuery Version to “Legacy 1.12.4-wp”. 


### Q: How do I make sure my plugins / themes are ready for the new jQuery version? 
A: You need to ensure that any jQuery you wrote is compatible with jQuery version 3.3.2, the WordPress core team are putting together a three step plan to help you, you can find more information here:  https://make.wordpress.org/core/2020/11/05/updating-core-jquery-to-version-3-part-2/


***


#### Thanks to [Christopher Churchill](https://profiles.wordpress.org/vimes1984/), [Abha Thakor](https://profiles.wordpress.org/webcommsat/) and [Meher Bala](https://profiles.wordpress.org/meher/) for researching and working on this document, and to the teams that provided assistance.



 
