---
layout: archive
title: "Collecting user data in Django"
permalink: /django-gathering/
author_profile: true
redirect_from:
---

{% include base_path %}

======

So you want to let your user add some data? Maybe submit their email address so they can get updates? Or add a suggested datasource or idea or whatever to a database you're already running?

This post is simply about how to get the various parts up and running in Django, but there are plenty of security issues to address (post on this to follow!). Users interacting with databases is a scenario much loved by hackers.

The basic outline is as follows:

- models.py     Build a model with some fields (and register it in admin.py)

- forms.py      Import the model and write a form which corresponds to it

- views.py      Import the form and write a view which integrates the form and calls a .html template

- urls.py       Import the view and assign the view function to the url

- page.html     Include html for a form, specifying the url which points back through all of this

- thanks.html   Build a 'thanks for your suggestion' page which your submission page can move to

So what does this look like in the files?
