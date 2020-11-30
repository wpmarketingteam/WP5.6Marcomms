**Status: Version 2020/11/25. Finalization with the Release Squad.**

# jQuery

Updates to jQuery in WordPress take place across three releases 5.5, 5.6 and 5.7.
https://make.wordpress.org/core/2020/06/29/updating-jquery-version-shipped-with-wordpress/   

Before updating to 5.6, you should preemptively check your sites using the update test plugin: https://wordpress.org/plugins/wp-jquery-update-test/    
This will help you find errors which can occur after an update.

We advise you install the jQuery Migrate plugin if you encounter any issues relating the the visual aspects of your site ( E.G a slider doesn’t work, a button is stuck etc etc ) after updating as some plugins and theme JavaScript code on your website could result in some broken sites. 
[[https://wordpress.org/plugins/enable-jquery-migrate-helper/ ]] 


***

## Questions and Answers - aimed at supporting Non-Developers 

### Q. How do I make sure I’m ready for the full Jquery update? 

A: To test your site ready for jQuery:
1. Please make sure you first install the jQuery Migrate plugin: https://wordpress.org/plugins/enable-jquery-migrate-helper/
2. Then install the jQuery update text plugin: https://wordpress.org/plugins/wp-jquery-update-test/ 
3. Now you need to configure the plugin by going to Plugins -> Test jQuery Updates 
4. In the Test jQuery Updates plugin, set the options as below:
 - jQuery version: Default (This will be the default jQuery version used in the WordPress Core)
 - jQuery Migrate: Disable (Keep it disabled for WordPress 5.5.)
 - jQuery UI version: Default

More information on how to do this can be found on the plugin page: 
https://wordpress.org/plugins/wp-jquery-update-test/

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
 -I updated to WordPress 5.6 and now I cannot save anything in the admin
 -I updated to WordPress 5.6 and sliders on my pages don’t work
 - ETC
 
The WordPress.org core team has put together a plugin to re-enable the first file that was removed in 5.5 to help mitigate these issues and give the plugin and theme authors time to perform the needed updates. This plugin is called “enable jQuery migrate helper” and can be found at: https://wordpress.org/plugins/enable-jquery-migrate-helper/
After installing this plugin, many people have found that a lot of the errors they have developed during the 5.5 update have disappeared.


### Q: How do I make sure my plugins / themes are ready for the new jQuery version? 
A: You need to ensure that any jQuery you wrote is compatible with jQuery version 3.3.2, the WordPress core team are putting together a three step plan to help you, you can find more information here:  https://make.wordpress.org/core/2020/11/05/updating-core-jquery-to-version-3-part-2/


***


#### Thanks to [Christopher Churchill](https://profiles.wordpress.org/vimes1984/), [Abha Thakor](https://profiles.wordpress.org/webcommsat/) and [Meher Bala](https://profiles.wordpress.org/meher/) for researching and working on this document, and to the teams that provided assistance.



 
