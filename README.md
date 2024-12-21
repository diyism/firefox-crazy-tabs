# The simplest firefox multi-row tabs solution in the world:
tab-group seperator, type "about:unloads" get a 5px hight black line seperator

mouse-over to show 16 rows of tabs, mouse-out to show only 2 rows

![](./scrot.png)

# How to install:
    in firefox open "about:config":
    set     toolkit.legacyUserProfileCustomizations.stylesheets=true
    set     userchrome.multirowtabs.scrollbar-handle.enabled=true
    open "about:support"     Profile Directory  > Open Directory,    get <profile directory>
    $ cd /home/<user>/.mozilla/firefox/<profile directory>
    $ mkdir ./chrome
    $ sublime ./chrome/userChrome.css
    copy https://github.com/diyism/firefox-multi-row-tabs-userchrome-css/blob/main/userChrome.css into <profile directory>
    restart firefox:
    $ killall firefox-bin

# ref:
    https://stackoverflow.com/questions/47361535/how-can-i-have-multiple-rows-with-tabs-on-firefox-57-add-on-tab-mix-plus-no
