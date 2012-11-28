Markdown Toolbar
================

Markdown Toolbar is an lightweight helper buttons that appear over textarea

![image](http://www.vitalik.com.ua/images/markdown-toolbar.png)

Try a demonstration [demonstration](http://www.vitalik.com.ua/markdown-toolbar/)


Installation
------------

In `Rails 3.1`, add this to your Gemfile and run the +bundle+ command.

    gem "markdown-toolbar"

Alternatively, you can install it as a plugin.

    rails plugin install git://github.com/fuksito/markdown-toolbar.git


Getting Started
---------------

Markdown Toolbar requires you to add such lines to your application.js

    //= require markdown-toolbar

and to application.css

    *= require markdown-toolbar
  
Then you can add toolbar to any textarea by adding a class +markdown-toolbar+ to it

    <%= f.text_area :text, :class => "markdown-toolbar" %>