**Status:** Version 2020/12/19 

# Gutenberg Updates

***

## Questions and Answers - aimed at supporting Non-Developers

### Reminder: Resources for Using the Block Editor Reminder: Resources for Using the Block Editor 

The Block Editor can help you produce nice layouts for your content with tons of blocks and block patterns that offer you an easy way to use multiple blocks at once. With the new Block Directory , you can also add new blocks into your Block Editor seamlessly. 

To learn more about how to make the most of what the block editor has to offer, check out the following resources:

- Adding a new block: https://wordpress.org/support/article/adding-a-new-block/ 
- Blocks: https://wordpress.org/support/article/blocks/ 
- Block Directory: https://wordpress.org/support/article/block-directory/ 


### Q. I still use the Classic Editor, will this new update affect it?
A. No, the classic editor plugin will continue to be maintained until 2022. In the Writing Settings of your site, you can decide which editor to use for each page or post. Alternatively, you can use the classic block available in the Block Editor: https://wordpress.org/support/article/classic-block/ 


### Q. Can I still use a  third-party page builder?
A. The hope is that the core editor has what you need! If it doesn’t, feature requests are always welcome. However, whether you choose to use a page builder or not is entirely up to you as the end-user. The potential compatibility of the page builder with these new Gutenberg updates is entirely dependent on the third party that develops your page builder. If you do run into issues we recommend you reach out directly to them so they can help advise you.


### Q. What are Block Patterns?
A. The block patterns are pre-configured  blocks, added via core, themes, and plugins, that you can add to your content similar to single blocks. Block patterns  can be registered to use any core block or 3rd party block present on a site. 

Glossary, WordPress Block Editor  https://developer.wordpress.org/block-editor/handbook/glossary/


### Q. Is the Gutenberg plugin required to use the Block Editor?
A. Since WordPress 5.0, the Block Editor is present in the WordPress core and the Gutenberg plugin is no longer required. However, if you would like to see what is being developed with the WordPress editor, the Gutenberg plugin will provide  access to newer features that are under development, and not yet included in the WordPress core. This currently includes Full Site Editing!

***

## Additional Question and Answers specifically for developers

### Q. How does Full Site Editing relate to 5.6 release?
A. Full site editing (FSE) will be added to the Gutenberg plugin once available.


### Q. Has 5.6 merged Full site editing into Core?
A. Full Site Editing remains an experimental feature in 5.6 that site administrators will need to opt into with the Gutenberg plugin. If you would like to help us with testing, great! Testing these areas helps to set the groundwork for future functionality.

More details about this work can be found under the heading ‘Experiments’ in this Gutenberg post. https://make.wordpress.org/core/2020/11/04/whats-new-in-gutenberg-4-november/ 


### Q. How do I enable and try Full Site Editing?
A. For starters, please only test this feature on a test or development site since this feature is still experimental. To do so on a test site, you only need to install and enable the Gutenberg plugin while using a block based theme. Of note, the Full Site Editing experiment will automatically be enabled if you’re using a block- based theme. 

Here are three options for current block-based themes:
- https://wordpress.org/themes/q/  
- https://wordpress.org/themes/block-based-bosco/
- You can find more experimental [block-based themes here too](https://github.com/WordPress/theme-experiments). 



### Q. How do I know that my theme supports Full Site Editing?

A. After installing the Gutenberg plugin, visit the WordPress Dashboard. If you can see “Site Editor” on the menu, great! That means your theme supports the experimental feature.



### Q. Will blocks be accessible within the website’s header and footer?

A. Blocks are only accessible within the site header and footer if you are using a block-based theme and the Full Site Editing experiment is enabled through the Gutenberg plugin., This means that if you have block templates in a theme, they won’t be used until the Full Site Editing experiment is enabled. For now, developers can create block-based themes including theme template files that are block enabled.


### Q. Where are the Customizer and Widget screens?

A. If you can’t view your Customizer and Widget screens, this means you have the  Full-Screen Editing (FSE) experiment enabled. This is because FSE themes do not have widget areas and the “Site Editor” offers similar capabilities to the “Customizer” screen.Additionally, in FSE themes there is no longer a “sidebar”, as the concept of theme-options that modify structure/layout no longer applies. Instead, users can create their own layout and page structure from the editor itself.



### Q. I am theme developer, should I update my theme to be compatible with Full Site Editing? Will previous features that my theme uses such as Customizer and Widgets be phased out?

A. The customizer and widgets screens will remain available for themes created using the current theme system.  There is no plan, at this time, to phase out support for  current themes, updating your theme is optional.



### Q. How do I enable Full Site Editing on my theme?

A. You will want to create a Block-based theme as described on this document: https://github.com/WordPress/gutenberg/blob/master/docs/designers-developers/developers/themes/block-based-themes.md 

Since the feature is currently experimental, you will also need to detect the existence of Gutenberg prior to enabling Full Site Editing. For this to happen, your theme needs to contain a folder called block-templates with a file called index.html within it. 

For more information, [check out this Pull Request](https://github.com/WordPress/gutenberg/pull/26500). 




### Q. Will there be documentation released for theme developers so we can be more prepared for FSE?

A. Yes! There is a WordPress tutorial on how to create a block-based theme — https://developer.wordpress.org/block-editor/tutorials/block-based-themes/  .

The original GitHub documentation on what a block is also describes the structure layout and functionality of a block-based theme — https://github.com/WordPress/gutenberg/blob/master/docs/designers-developers/developers/themes/block-based-themes.md 






### Q. What is the difference between a block pattern and a reusable block?

A. Reusable blocks or groups of blocks that are  centrally  managed with changes applied to the reusable block affecting all instances used across the site. . This is helpful if you have content that you will use in multiple locations on your site that you would like to keep updated by editing in a single, central location. For example, if you’re writing a series of posts, you can use a reusable block to link to all posts in the series with each new post you share. Generally speaking, reusable blocks are primarily user content and can be thought of as custom user blocks.

Block patterns offer an entirely different approach both in behavior and presentation to reusable blocks. Block patterns are registered by core, themes, or plugins to act as pre-configured blocks or groups of blocks. . For example   a block pattern with starter content can be registered so that a user can insert the block pattern into content and add their own content adjustments. Once inserted, blocks added from a block pattern are regular blocks, changes made to these blocks will not affect the registered block pattern or any previous content that used that block pattern to create content. .

### Q. How can I register a block pattern on my site?

Several block patterns are included with WordPress core.  Theme and plugin authors can register additional custom block patterns using the register_block_pattern function. To learn more about how to set this up, head to the Block Patterns page in the [Block Directory Handbook](https://developer.wordpress.org/block-editor/developers/block-api/block-patterns/).


Block patterns were introduced in WordPress Release 5.5. More on the block pattern registration and core block patterns https://make.wordpress.org/core/2020/07/16/block-patterns-in-wordpress-5-5/ 


***


***


#### Thanks to all members of the release squad, [Angela Jin](https://profiles.wordpress.org/angelasjin/), [Daisy Olsen](https://profiles.wordpress.org/daisyo/), [Anne McCarthy] (https://profiles.wordpress.org/annezazu/), [Dika Fei](https://profiles.wordpress.org/jellypixel/), [Christopher Churchill](https://profiles.wordpress.org/vimes1984/), [Olga Glekler](https://profiles.wordpress.org/oglekler/), [Abha Thakor](https://profiles.wordpress.org/webcommsat/) and [Meher Bala](https://profiles.wordpress.org/meher/), for researching and working on this document, and to the teams that provided assistance. 




