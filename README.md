# OS X screenshot-renamer

I take a lot of screenshots. By default, in OS X, the screenshot format looks
something like this:

```
Screen Shot 2020-05-05 at 11.16.00 PM.png
Screen Shot 2020-05-05 at 12.38.26 PM.png
Screen Shot 2020-05-05 at 12.42.39 PM.png
Screen Shot 2020-05-05 at 12.46.26 PM.png
Screen Shot 2020-05-05 at 5.27.05 PM.png
```

It's sorted numerically, instead of by the time the screenshot was taken. I
could change my system time to 24-hour format, but I prefer seeing time with
AM/PM. I also like my screenshots to be ordered alphabetically. This program
automatically watches for screenshots that get created and renames them so that
they're sorted properly:

```
screenshot_2020-05-05_12-38-32.png
screenshot_2020-05-05_12-42-45.png
screenshot_2020-05-05_12-46-32.png
screenshot_2020-05-05_17-27-11.png
screenshot_2020-05-05_23-16-00.png
```

To set this up, run `setup`. It assumes `$HOME/bin` is in your path.
You'll also need to authorize `/bin/bash` full disk access for this to work,
as explained in this [Stack Overflow answer][stack-overflow-answer].

[stack-overflow-answer]: https://stackoverflow.com/a/60500021
