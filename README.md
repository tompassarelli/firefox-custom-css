for further conf:
https://firefox-source-docs.mozilla.org/devtools-user/browser_toolbox/index.html

userChrome symlinked to firefox user profile chrome folder
~/.mozilla/firefox/ijes0mzs.default-release-1669402644266/chrome/userChrome.css

How to edit firefox chrome settings

chrome folder doesn't exist by default, to make:

about:config -> change the value of toolkit.legacyUserProfileCustomizations.stylesheets to true.

about:support -> profile directory -> create chrome folder -> userChrome.css

