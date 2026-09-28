---
layout: post
title: "Obtaining a Usable CSV File from Wordpress"
subtitle: "Tiddlywiki"
date: 2024-11-04 10:00:00 +1000
categories: [blog]        # only use one of the following: [blog], [writing], [editing], [publishing], [book-review], [author-interview], [gaming], [technology], [genealogy], [movies], [craft]
tags: [general]  # anything you want, e.g. [news], [reading], [general], 
---

<div style="background-color: #eee;border-left: 6px solid #ddd;padding: 10px;margin-bottom: 15px">
  <strong>Go to the first post in this series: [[How to build a Tiddlywiki website]]</strong>
</div>

If you are following these step-by-step instructions on building a Tiddlywiki website, you should have a copy of Tiddlywiki that you've been "playing" with and now you should be ready for the next step in the process of transferring your website from Wordpress to Tiddlywiki.

To continue, you need a usable CSV Wordpress file that can be used in Tiddlywiki to import your Wordpress posts. Please note that you cannot use the standard Wordpress exporter as the data received by using this method goes down the page, instead of in columns across the page.

The first step is to find a Wordpress plugin that provides an CSV file, i.e. has titled columns in a spreadsheet format. I tried many different plugins and most of them required an upgrade to a paid version to obtain the correct format. I didn't want to pay for this function and finally settled on a plugin called "WP All Export". 

To find the plugin, go to Plugins > Add New > search for "WP All Export" > Install Now and when the file has downloaded, click on Activate.

Now look in the left sidebar in the Wordpress Dashboard and you'll see "All Export" near the bottom of the list. Click on that and then click New Export.

With "Specific Post Type" chosen, click in the "choose a post type" area and a dropdown list will appear. Click on "Posts". If you want to apply filters then you'll need to purchase an upgrade, but if you wish to export all your current posts then you'll be okay to then click on "Migrate Posts".

The next screen has multiple options. Assuming you are trying to obtain a full list of posts, leave the boxes unchecked and click on "Save and Run Export".

You can sit back and watch the progress bar move from 0 to 100%. Mine took about 13 seconds, but yours might take a bit longer, depending on the number of posts you have.

When the next screen appears, the "Download" option should be highlighted. Click on CSV and save as whatever file name you wish in a folder where you'll be able to find it later. 

And that's it. You're done!

You can repeat the above process to obtain a CSV file with all your pages too. Just pick "Pages" instead of "Posts" but all the other instructions remain the same.

<div style="background-color: #eee;border-left: 6px solid #ddd;padding: 10px;margin-bottom: 15px">
  <strong>Go to the next post: Will be added soon</strong>
</div>