Status: Version 2020/11/25. Finalization with the Release Squad.

# Gutenberg updates

**(Please note: additional items are being added to this document by the team as information is available)**

### Key reading
https://make.wordpress.org/core/2020/11/04/whats-new-in-gutenberg-4-november/ 

https://make.wordpress.org/core/2020/11/02/whats-next-in-gutenberg-november-2020/ 

***

## Questions and Answers - aimed at supporting Non-Developers 

### Q. Why should I use the block editor?
A. The Block Editor can help you produce nice layouts for your content with many in-built block choices and new block patterns. With the new Block Repository, you can also add new blocks into your Block Editor.


### Q. I still use the Classic Editor, will this new update affect it?
A. No, the classic editor plugin will be maintained until 2022. In the Writing Settings of your site, you can decide if you allow choosing which editor to use for each page or post. Alternatively, you can use the new Block Editor and use the Classic Block: https://wordpress.org/support/article/classic-block/


### Q. Do I still need a third-party page builder?
A. Whether you choose to use a page builder or not is entirely up to you as the end-user. The potential compatibility of the page builder with these new Gutenberg updates is entirely dependent on the third party that develops your page builder. If you do run into issues we recommend you reach out directly to them so they can help advise you.


### Q. What’s the block pattern for?
A. The block patterns are ready-to-use blocks that you can add to your page. It can be a button, header, or any commonly used block. More patterns will be added with time. To understand the difference between blocks, patterns, and layouts, visit: https://make.wordpress.org/design/2019/11/14/blocks-patterns-and-layouts/


### Q. Can I use my page builder and the new block editor together?
A. It depends on which page builder you are using or want to use. We recommend you check the documentation for the page builder you use.


### Q. Will I still need the Gutenberg plugin?
A. You do not need to use the Gutenberg plugin in order to use the Block Editor. However, if you do use the plugin, you will have access to newer features that are under development, and not yet included in the WordPress core.

***

## Additional Question and Answers specifically for developers  

### Q. Full Site Editing is an exciting new feature. How does the 5.6 release move us towards this?
A. The 5.6 release primarily focused on improving the Full Site Editing flows along with polishing the site editor and its navigation panel.


### Q. Has 5.6 merged Full site editing into Core?
A. Full Site Editing remains an experimental feature in 5.6 that site administrators need to opt into with the Gutenberg plugin. Work on these areas helps set the groundwork for future functionality.

More details about this work can be found under the heading ‘Experiments’ in this Gutenberg post. https://make.wordpress.org/core/2020/11/04/whats-new-in-gutenberg-4-november/

### Q. How do I enable and try Full Site Editing?
A. You need to:

1. Have Gutenberg installed as a way to “opt-in” to the experiment
2. Install a compatible theme


### Q. How do I know that my theme supports Full Site Editing?
A. Make sure you have Gutenberg installed and then go to the WordPress admin (dashboard). If you can see “Site Editor” on the menu that means your theme supports the experimental feature.


### Q. Will blocks be accessible within the website’s header and footer?
A. Blocks will only be accessible within the site header and footer if you are using a block-based theme and the Full Site Editing experiment is enabled through the Gutenberg plugin. For more context, if you have block templates in a theme, they won’t be used until the Full Site Editing experiment is enabled. For now, developers are able to create block-based themes including theme template files that are block enabled. 


### Q. Where are the Customizer and Widget screens?
A. If you can not view your Customizer and Widget screens, this means you have Full-Screen Editing (FSE) experiment enabled.

FSE themes do not have widget areas and the “Site Editor” offers similar capabilities to the “Customizer” screen.

In FSE Theme there is no longer a “sidebar”. The concept of theme-options that modify structure/layout no longer applies since users can create their own layout and page structure from the editor itself.


### Q. Should I update my theme to be compatible with Full Site Editing? Will old features that my theme use such as Customizer and Widgets be phased out?
A. The old feature will still be there for traditional themes to use side-by-side with the new Full Site Editing feature. As of November 2020, there is no plan to phase out the support for old themes therefore updating your theme for now is optional. 


### Q. How do I enable Full Site Editing on my theme?
A. You need to create a Block-based theme as described on this document: 
https://github.com/WordPress/gutenberg/blob/master/docs/designers-developers/developers/themes/block-based-themes.md

Since the feature is an experimental feature you also need to detect the existence of Gutenberg prior to enabling Full Site Editing.


### Q. Will there be documentation released for theme developers so we can react accordingly?

Yes, there is a WordPress tutorial on how to create a block-based theme — https://developer.wordpress.org/block-editor/tutorials/block-based-themes/ .

The original GitHub documentation on what a block is based on the readme found in GitHub which details the structure layout and suggest functionality of a block-based theme — https://github.com/WordPress/gutenberg/blob/master/docs/designers-developers/developers/themes/block-based-themes.md


### Q. What is the difference between a block pattern and a reusable block?
A. Reusable blocks are meant to co-exist with regular blocks as a way for the user to make snippets of content that are globally synchronized. This is helpful if you find yourself repeatedly adding the same content to the same block or group of blocks. For example, if you’re writing a series of posts, you can use a reusable block to link to all posts in the series with each new post you share. Generally speaking, they are primarily user content and can be thought of as custom user blocks.

Block patterns offer an entirely different approach both in behavior and presentation to reusable blocks. Block patterns are saved locally upon insertion and don’t exist globally. They are just blocks that the user can insert with starter content that is meant to be customized and updated by the user.

Block patterns in the Block Directory Handbook
https://developer.wordpress.org/block-editor/developers/block-api/block-patterns/ 

Block patterns were introduced in WordPress Release 5.5. More on the block pattern registration and core block patterns
https://make.wordpress.org/core/2020/07/16/block-patterns-in-wordpress-5-5/ 


***


#### Thanks to [Dika Fei](https://profiles.wordpress.org/jellypixel/), [Christopher Churchill](https://profiles.wordpress.org/vimes1984/), [Olga Glekler](https://profiles.wordpress.org/oglekler/), [Abha Thakor](https://profiles.wordpress.org/webcommsat/) and [Meher Bala](https://profiles.wordpress.org/meher/), for researching and working on this document, and to the teams that provided assistance. 




