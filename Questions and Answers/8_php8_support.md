**Status: Version 2020/11/25. Finalization with the Release Squad.**

# PHP 8.0 Support
WordPress Core in its 5.6 release is taking the first step to support PHP 8.0, which is due out in late November 2020. It is a good time to start planning to migrate your WordPress products, services and sites to the latest PHP version. 
https://make.wordpress.org/core/2020/11/20/wordpress-5-6-field-guide/

Many of your questions can be answered by reading this post on Core about how WordPress will be beta compatible with PHP 8.0. 
https://make.wordpress.org/core/2020/11/23/wordpress-and-php-8-0/ 


***

## Questions and Answers - aimed at supporting Non-Developers 

### Q. What does ‘beta-compatible’ mean?
A. Terming it as beta-compatible acknowledges the hard work that has been done to get WordPress running on PHP 8.0 without major issues and to achieve passing PHPUnit tests. It also honors the WordPress project’s commitment to being compatible with the new versions of PHP when they are released.
WordPress will be “beta compatible” with PHP 8.0. The WordPress project has a long history of being compatible with new versions of PHP as soon as possible, and this release is no different. There has been many hours of work on parts of the  WordPress core. To enable WordPress to run 
***

## Questions and Answers - aimed at supporting developers 

### Q: How do I update to PHP 8.0? 
You will need to speak to your hosting provider about updating to PHP 8.0 and the options you may have within the service.


### Q: How will this impact the plugins that are no longer maintained or  have not been updated for a long time? 
Some plugins will work just fine with PHP 8.0, and some will not. You will need to test your site first to ensure the plugins you use are compatible. If they aren’t you will have to find an alternative.


### Q:  Should you update your WordPress project to PHP 8?
it is highly recommended that you thoroughly test your site before upgrading to PHP 8. You can read more information on why here: 
https://make.wordpress.org/core/2020/11/23/wordpress-and-php-8-0/


### Q: Will Updating to PHP 8 Break WordPress Sites?
As long as your plugins are compatible with PHP 8 you shouldn’t have an issue with updating to php 8, but you should ask your host to test this for you prior to updating. 


### Q: Speed wise what are the benefits of moving to PHP 8?
There are a lot of underlying improvements with regards to PHP 8, one of the main ones will allow PHP 8 to run faster due to it compiling the code and running it directly on the CPU.  This is called J(ust) i(n) T(ime).

The “just in time” compiler promises speed improvements for complex tasks and algorithms and opens new opportunities for the PHP language to broaden its reach and applications.


### Q: What if my host does not support PHP 8 ?
You should try and contact your host to ask them when they plan on moving up to PHP 8, most hosts should be on at least PHP version 7.3, the previous version PHP 7.2 came to the end of it’s life on 11/30/2020.  You can find up to date information with regards to which versions are currently supported here: 
https://www.php.net/supported-versions.php


### Q: Are there any security concerns with WordPress 5.6 and PHP 8?
PHP 5.6  came to the end of it’s life on December the 31st 2018, you should always try and keep your php as up to date as possible to try and mitigate any potential bugs or vulnerabilities. 


### Q: Where can I find out more information about PHP 8? 
There are two main resources at the moment to read up about PHP 8 and some of the issues facing WordPress during this update, Yoast have written up a highly technical report: 
 Yoast php 8 report: https://developer.yoast.com/blog/the-2020-wordpress-and-php-8-compatibility-report/
 
And the core team have provided a write up: https://make.wordpress.org/core/2020/11/23/wordpress-and-php-8-0/

***

#### Thanks to [Christopher Churchill](https://profiles.wordpress.org/vimes1984/), [Abha Thakor](https://profiles.wordpress.org/webcommsat/) and [Meher Bala](https://profiles.wordpress.org/meher/) for researching and working on this document, and to the teams that provided assistance.

