**Status: Version 2020/12/19.**

**More information is being finalized with the Release Squad.**

# jQuery

Updates to jQuery in WordPress take place across three releases 5.5, 5.6 and 5.7.
https://make.wordpress.org/core/2020/06/29/updating-jquery-version-shipped-with-wordpress/   

Before updating to 5.6, you should preemptively check your sites using the update test plugin: https://wordpress.org/plugins/wp-jquery-update-test/    
This will help you find errors which can occur after an update.

This update test plugin will help you find errors which can occur after an update.

The WordPress Core team recommends that you install the jQuery Migrate plugin if you encounter any issues relating to the visual aspects of your site after updating (for example, if a slider doesn’t work, a button is stuck, etc). This is because some plugins and theme JavaScript code on your website could result in some broken sites. [[https://wordpress.org/plugins/enable-jquery-migrate-helper/ ]]


***

## Questions and Answers - aimed at supporting General Users

### Q1  After updating to the 5.6 version of WordPress I am experiencing issues with unexpected behavior on my site. What can I do about these issues?

A: If you updated to WordPress 5.6, and you are experiencing issues with scripts on your site, such as being unable to save changes to the WordPress Dashboard, broken sliders or buttons that are unclickable, there are a few things you can try. 

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

***

## Questions and Answers - aimed at supporting Developers 

### Q1: Why is WordPress updating jQuery?
A: WordPress is phasing out an old, unsupported version of the popular front-end JavaScript library “jQuery” across three releases: 5.5, 5.6 and 5.7. This is so that WordPress stays up to date with the latest jQuery versions, which will enable WordPress to patch and keep up with  security issues. 

During this transition period, the WordPress Core Team asks plugin and theme authors to help by updating their own plugins and themes to the latest version of jQuery.


***


#### Thanks to  [Christopher Churchill](https://profiles.wordpress.org/vimes1984/), [Andrew Ozz](https://profiles.wordpress.org/azaozz/), [Daisy Olsen](https://profiles.wordpress.org/vimes1984/), [Abha Thakor](https://profiles.wordpress.org/webscommsat/), [Olga Gleckler](https://profiles.wordpress.org/oglekler/), [Mark Smallman](https://profiles.wordpress.org/marks99/), [Meher Bala](https://profiles.wordpress.org/meherbala/), [Angela Jin](https://profiles.wordpress.org/angelasjin/), [Shanta R. Nathwani ](https://profiles.wordpress.org/tantienhime/) for researching and working on this document, and to the teams that provided assistance. Thanks to all the release squad members and WordPress.org teams who have provided input.



 
