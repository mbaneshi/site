Culling the GitHub notification spam
====================================

Long ago, I set up an email filter to make GitHub notifications skip my inbox.
This made it easy to ignore the volume of irrelevant notifications that I was
getting, and I only noticed them when they got in the way of a search for the
one or two useful emails that GitHub sends. 

However, it also means that I won't find out if something legitimately
notification-worthy happens, such as a new contributor opening a pull request
to one of the handful of projects I actually care about. 

Here are the steps one can take to improve that signal-to-noise ratio.

.. more::

Quit Auto-Subscribing
---------------------

Go to your `notification settings`_ and un-check the **automatically watch
repositories** box. 

.. figure:: /_static/autowatch.png
    :align: center

This will prevent you from automatically getting added to as a watcher to new
repositories when you're given access to them. It's especially important to my
GitHub workflow because I'm in several organizations that grant all members
access to new repositories by default, and most of those repos are irrelevant
to me. 

Assess the Damage
-----------------

Head over to the `watching repos list`_ to see how many repositories you're
automatically getting notifications for. In my case, there are too many to
sort through by hand, so the best solution is going to be to bulk
unsubscribe. 

.. figure:: /_static/stopwatching.png
    :align: center

Declare Notification Bankrupcy
------------------------------

.. figure:: /_static/notifications.png
    :align: center

While you're thinning your watch list, head on over to the `notifications
list`_ and take action on any notifications that need it, or just use the
magical ``Mark all as read`` button in the upper right. 

It's important to get rid of all the spurious notifications generated by repos
you shouldn't have been watching in the first place, so that in the future,
having unread notifications will mean "something interesting happened" rather
than "there's still background noise". 

.. figure:: /_static/no_new_notifications.png
    :align: center

Re-watch selectively
--------------------

There are only about half a dozen repos where I need to take immediate action
when an event such as a new PR occurrs. 

For each such repo, switch your status to "watching" on its home page. 

.. figure:: /_static/rewatch.png
    :align: center

Remove those email filters
--------------------------

The whole point of this exercise was to extract signal from the noise, and to
complete that goal, we have to make the signal visible somewhere. For gmail,
the filter ignoring everything from github will be somewhere in the `filters
list`_. 

Maintenance
-----------

To keep seeing only the relevant notifications, respond to irrelevant
notification emails by un-watching the repo that they came from. 

.. _notifications list: https://github.com/notifications
.. _watching repos list: https://github.com/watching
.. _notification settings: https://github.com/settings/notifications
.. _filters list: https://mail.google.com/mail/u/0/#settings/filters

.. author:: E. Dunham
.. categories:: none
.. tags:: workflow, github
.. comments::
