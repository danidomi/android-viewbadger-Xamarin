Android ViewBadger Xamarin C#
==================

A simple way to add a badge value to a Android view.

![Demos](http://www.jeffgilfelt.com/viewbadger/vb-1a.png "Demos")&nbsp;
![ListAdapter](http://www.jeffgilfelt.com/viewbadger/vb-2a.png "ListAdapter")

Note: If your aim is to replicate the iOS icon and TabBar badge UI for notifications, consider using Android UI conventions such as the number field of the [Notification](http://developer.android.com/reference/android/app/Notification.html "Notification") class rather than this method.

Usage
-----

Simple example:

    View target = FindViewById(Resource.id.target_view);
    BadgeView badge = new BadgeView(this, target);
    badge.SetText("1");
    badge.Show();


To use ViewBadger in your own Android project, simply build this project and add the reference to your project.

Current Limitations
-------------------

- Badging Action Bar items is currently not supported [#2](https://github.com/jgilfelt/android-viewbadger/issues/2)
- Badging views inside RelativeLayout with dependencies may break alignment [#1](https://github.com/jgilfelt/android-viewbadger/issues/1)

Credits
-------

Author:  Daniel Domingues

Based on [this](https://github.com/jgilfelt/android-viewbadger).

The code in this project is licensed under the Apache Software License 2.0.
<br />
Copyright (c) 2011 readyState Software Ltd.
