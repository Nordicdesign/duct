Front-end styleguide boilerplate
================================

This is a simple boilerplate to create front-end style guides using mixture. You should be able to import your styles, and quickly document how your website is built.

It's formed by four main elements:

* Strategy - You should document here like browser support, performance budget, etc. It's mainly a wiki area for you to write anything you want, so make it as brief or long-winded as you wish
* Elements - Typography, forms, grid, etc. 
* Blocks - Elements combined together in a reusable module
* Layouts - The different templates used in your website

# Style guides

*style.scss* is the main file, with includes to all the other SASS files. Any custom styling, not relevant to the live site, should go there

*_boilerplate.scss* includes the basic styling elements for the boilerplate. You shouldn't need to touch this, unless you want to make changes on how the guide looks. 

You can (and should) modify all the other files, as they serve only as an example:

* _config.scss - basic stuff like primary and secondary colours, grid colums or font stack
* _guide.scss - the majority of CSS should go here
* _layout.scss - grid and other layout elements go here
* _reset.scss - Self-explanatory
