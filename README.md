This repository holds the source for our driving.stanford.edu website. This website is managed using <a href="http://getnikola.com/">Nikola</a>, a static site and blog generator.

<b>Nikola Installation</b>: follow <a href="http://getnikola.com/handbook.html#installing-nikola">these instructions</a>


Creating a new blog post
========================

Go to the root of this repo and run `nikola new_post`. This will ask some questions, such as the post title, and create a rst file. Then edit that file with your post content (don't touch the header).

Adding a paper
==============

Edit `pages/papers.rst` and follow the template. This is raw html, constructing a table with 2 columns, one row per paper. If you need to upload files (PDF, image, etc.) upload them in `files/papers` and link to them in `pages/papers.rst` as `href="/papers/name-of-file"`

Generating and testing
======================

Run `nikola auto`, which will generate the site, and serve it to port 8000. When satisfied, upload using the rsync script.
