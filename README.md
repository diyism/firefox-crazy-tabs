# Simplest firefox multi-row tabs with tab-group seperator(type "about:unloads" get a 5px hight black line seperator):

    in firefox open "about:config"      set     toolkit.legacyUserProfileCustomizations.stylesheets=true
    open "about:support"     Profile Directory  > Open Directory,    get <profile directory>
    $ cd /home/<user>/.mozilla/firefox/<profile directory>
    $ mkdir ./chrome
    $ sublime ./chrome/userChrome.css
    copy https://github.com/diyism/firefox-multi-row-tabs-userchrome-css/blob/main/userChrome.css into <profile directory>
    restart firefox:
    $ killall firefox-bin
