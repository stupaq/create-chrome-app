Create a Mac OSX app from a website (using Google Chrome)
=========================================================

Usage
-----

    ./create-app <name> <url> <icon_path

Note that attached `MasterPreferences` file overrides Chrome defaults in order
to reduce profile directory footprint and speed up startup process.

There are a few (possibly unwanted by some users) limitation deliberately
imposed on created instance of Chrome -- after creating the instance you can
customize everything in the settings `command ,`:
* no on-disk caching
* no cookies -- I strongly advise add exceptions for particular sites only
* no plugins -- same as above
* no protocol handles and other Chrome-specific shit
* no url verification

The app starts up very fast and takes around `2 MB` including
high-resolution icon and created profile.

Enjoy!

