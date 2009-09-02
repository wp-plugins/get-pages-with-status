=== Plugin Name ===
Contributors: mcinvale
Tags: pages, cms
Requires at least: 2.7
Tested up to: 2.8.4
Stable tag: trunk

Modify version of get_pages() function to allow the inclusion of pages with any status.

== Description ==

**Get Pages with Status** is a very simple plugin that allows you to get pages with any status.

This plugin gives you one new function, `get_pages_with_status($arguments)`.

This function adds 1 new option to the default [get_pages()](http://codex.wordpress.org/Function_Reference/get_pages) function. 

1. Define the `status` argument to select pages of any status type. 
1. Define status as 'all' to get all pages regardless of status.

That's it really, super simple.

[More documentation for Get Pages with Status on BinaryM.com](http://binarym.com/2009/get-pages-with-status/)

== Installation ==

1. Upload `get_pages_with_status.php` to the `/wp-content/plugins/` directory.
1. Activate the plugin through the 'Plugins' menu in WordPress.
1. Replace `get_pages()` with `get_pages_with_status()` in your templates to use the `status` argument.
1. See [our site](http://binarym.com/2009/get-pages-with-status/) for another example.

== Frequently Asked Questions ==

None at this point. [Contact me](http://binarym.com/contact/) if you have any and I'll add them here.
