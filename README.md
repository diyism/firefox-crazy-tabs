# The simplest firefox multi-row tabs solution in the world:
tab-group seperator, type "about:unloads" get a 5px hight black line seperator

mouse-over to show 16 rows of tabs, mouse-out only show 2 rows

![](./scrot.png)

# How to install:
    in firefox open "about:config"      set     toolkit.legacyUserProfileCustomizations.stylesheets=true
    open "about:support"     Profile Directory  > Open Directory,    get <profile directory>
    $ cd /home/<user>/.mozilla/firefox/<profile directory>
    $ mkdir ./chrome
    $ sublime ./chrome/userChrome.css
    copy https://github.com/diyism/firefox-multi-row-tabs-userchrome-css/blob/main/userChrome.css into <profile directory>
    restart firefox:
    $ killall firefox-bin
