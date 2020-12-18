**Status: Version 2020/11/25. This is being finalized with the Release Squad.**

# Twenty Twenty One Theme 

Introducing Twenty Twenty One which is the default theme with this release.
https://make.wordpress.org/core/2020/09/23/introducing-twenty-twenty-one/


***

## Questions and Answers - aimed at supporting non-developers 

### Q1 What is the difference between WordPress theme Twenty Twenty and Twenty Twenty-One?
A. Both themes have high levels of accessibility and performance and follow good practice. Just like other WordPress default themes, they receive the necessary updates to be fully compatible with the latest WordPress version.

The main reason to choose the new Twenty Twenty-One theme is its modern design, freshness and flexibility. Twenty Twenty-One adds beautifully styled block patterns, block styles, and a custom color palette to make adding content to your site easy. This theme has a new color palette with pastel colors ideal for different purposes from a photographer’s personal portfolio to a cosmetic store, or beauty blog. It is also the first time where the default WordPress theme has a Dark mode feature.  


### Q2 What are the benefits of using a WordPress default theme Twenty Twenty-One? 

This new theme has:

#### 1. A unique design pattern in line with modern trends.

![Unique design patterns in 2021 Theme](https://github.com/wpmarketingteam/WP5.6Marcomms/blob/master/Questions%20and%20Answers/images/2021-design-patterns.jpg "Unique design patterns in 2021 Theme")

To find out more about patterns which were introduced in August 2020 in WordPress 5.5 go to [this link](https://github.com/wpmarketingteam/WP5.5/blob/main/Q%26A%20for%20non-technical%20users.md#section-4-block-patterns)

#### 2. New color palette with nice pastel colors

![Color Palette for 2021 Theme](https://github.com/wpmarketingteam/WP5.6Marcomms/blob/master/Questions%20and%20Answers/images/2021-new-color-palette.jpg "Color Palette for 2021 Theme")

You can choose the background color in the Customizer (check it below) and change color of text or background of a block in The Block Editor.

![Choose Background color in Customizer for 2021 Theme](https://github.com/wpmarketingteam/WP5.6Marcomms/blob/master/Questions%20and%20Answers/images/2021-choose-the-background-color.jpg  "Choose Background color in Customizer for 2021 Theme")

#### 3. Ability to give visitors the possibility to switch to the Dark mode with one button

![Dark Mode in 2021 Theme](https://github.com/wpmarketingteam/WP5.6Marcomms/blob/master/Questions%20and%20Answers/images/2021-switch-to-dark-mode.png  "Dark Mode in 2021 Theme")

You can choose a background color and enable or disable this feature in the Customizer (Dashboard > Appearance > Customize > Colors & Dark Mode)

![Dark Mode in 2021 Theme](https://github.com/wpmarketingteam/WP5.6Marcomms/blob/master/Questions%20and%20Answers/images/2021-dark-mode.png  "Dark Mode in 2021 Theme")

#### 4. Highest level of Accessibility from WordPress default themes

![Highest level of Accessibility in 2021 Theme](https://github.com/wpmarketingteam/WP5.6Marcomms/blob/master/Questions%20and%20Answers/images/2021-accessibility.png  "Highest level of Accessibility in 2021 Theme")

While the Twenty Twenty One theme is of this highest accessibility level, accessibility of your site will also depend on which plugins you install. The WordPress Accessibility team recommends that you review all plugins for accessibility before installing them on your site. [These scores](https://web.dev/accessibility-scoring/) are also dependent on which plugins you have on your site as well, so be careful and do your research before choosing to install a plugin on your site.

The WordPress community has a whole team devoted to accessibility which will be celebrating its 10th anniversary in 2021. If you want to find more about their work or to and get involved, [visit](https://make.wordpress.org/accessibility/)

Try the Twenty Twenty One theme for yourself and discover its many benefits. The Release Squad working with many other contributors across the WordPress open source project have done a lot of work on this theme and it’s an exciting step forward


























### Q.  How to create a Twenty Twenty One child theme?
To create the child theme to Twenty Twenty-One you can follow that same steps as to create a child theme to any other theme: 
1. Create a “twentytwentyone-child” folder.
2. Create “style.css” file inside with minimum required information: 

```
/*
Theme Name: Twenty Twenty-One Child
Template: twentytwentyone
*/
```

Make new styles or add your custom functions in “functions.php”
Activate your theme and enjoy your Twenty Twenty-One Child theme. For this go to Dashboard > Appearance > Themes, choose your new theme and click Activate. 

Keep in mind that not all themes include parents styles automatically. Twenty Twenty-One theme will do this for you. You can also include an image with the name screenshot.png in this folder as well to make it look nice in your Admin.

More information about the process: https://developer.wordpress.org/themes/advanced-topics/child-themes/


### Q. How can I customize my Twenty Twenty-One theme?
There are several ways to customize your WordPress theme.
You can use the  “Customizer” (Dashboard > Appearance > Customize) where you can add your logo, change colors, add background image, edit menu and widgets but also add custom styles. https://wordpress.org/support/article/appearance-customize-screen/

Make a child theme to extend the functionality further. https://developer.wordpress.org/themes/advanced-topics/child-themes/

A lot of functionality is already available as plugins. To install a plugin, you can  use keywords to search and find plugins  in the official WordPress repository on https://wordpress.org/plugins/

We advise you to try new plugins and all style adjustments on a staging site. More information on how to run a development copy of WordPress. https://wordpress.org/support/article/running-a-development-copy-of-wordpress/

You can install the copy of your site locally on your computer and some hosting companies provide the ability to create a staging site automatically. If you have this option,  you should take advantage of it. 


***

## Questions and Answers - aimed at supporting Developers 

### Q. What is the difference between WordPress theme Twenty Twenty and Twenty Twenty-One?

Both themes have high levels of accessibility and performance and follow good practice. Just like other WordPress default themes, they receive the necessary updates to be fully compatible with the latest WordPress version. 

The main reason to choose the new Twenty Twenty-One theme is it’s modern design, freshness and flexibility. 



***

# Dark Mode In Twenty Twenty One Theme 

TwentyTwentyOne will include support for Dark Mode, with options for its use found within the customiser.

![Dark Mode in 2021 theme](https://github.com/wpmarketingteam/WP5.6Marcomms/blob/master/Questions%20and%20Answers/images/dark-mode.png "Dark Mode in 2021 theme")

As the information next to the option for Dark Mode explains, it allows the site to honour the users dark mode preferences on the device they are viewing your site on.

Once enabled, the front end of the site will show a floating button to enable/disable dark mode.

![Dark Mode Floating button in the front end](https://github.com/wpmarketingteam/WP5.6Marcomms/blob/master/Questions%20and%20Answers/images/dark-mode-buttons-in-front-end.png  "Dark Mode Floating button in the front end ")

If a visitor to your site has dark mode enabled on their system preferences, the site will default to their chosen preference (dark mode on/off). While still having the option on the site to disable it, should they wish with this floating button.

If you do enable dark mode, pay careful attention to any logos and graphics used on your site.

![Logos and graphics to keep in mind when turning dark mode on](https://github.com/wpmarketingteam/WP5.6Marcomms/blob/master/Questions%20and%20Answers/images/dark-mode-front-end-1.png "Logos and graphics to keep in mind when turning dark mode on")

![Logos and graphics to keep in mind when turning dark mode on](https://github.com/wpmarketingteam/WP5.6Marcomms/blob/master/Questions%20and%20Answers/images/dark-mode-front-end-2.png "Logos and graphics to keep in mind when turning dark mode on")


***

## Questions and Answers - aimed at supporting non-developers 

You can use dark mode in the Twenty Twenty One theme by asking your developer or self-installing if you have administrator rights, the  dark mode. 


***


#### Thanks to [Olga Glekler](https://profiles.wordpress.org/oglekler/), [Mark Smallman](https://profiles.wordpress.org/marks99/), [Christopher Churchill](https://profiles.wordpress.org/vimes1984/), [Abha Thakor](https://profiles.wordpress.org/webcommsat/), [Meher Bala](https://profiles.wordpress.org/meher/) for researching and working on this document, and to the teams that provided assistance. Thanks to [Angela Jin](https://profiles.wordpress.org/angelasjin/), [Daisy Oslen](https://profiles.wordpress.org/daisyo/) and all the release squad members who have provided input.



 
