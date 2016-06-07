# Firefox win10tabs

UserChrome cascading style sheets to enable background colored title/tab bar in Firefox running on Windows 10 OS.

github repository <https://github.com/Gregory-K/firefox-win10tabs>  
relative bug [Firefox title bar should pick up the Windows 10 accent color when in the foreground](https://bugzilla.mozilla.org/show_bug.cgi?id=1196266)

## Requirements

* Windows 10 Operating System
* Windows 10 colored title bars enabled  
_(win+i > Personalization > Colors > check "Show color on Start, taskbar, action center, and title bar")_
* Mozilla Firefox  
_(I am not sure when and if Mozilla decides to correct this Firefox behaviour, follow the relative bug above.)_

## Apply

* Go to your Firefox Profile _([How do I find my profile?](https://support.mozilla.org/en-US/kb/profiles-where-firefox-stores-user-data#w_how-do-i-find-my-profile))_.
* If it doesn't exist, create a folder "chrome". cd inside it.
* Choose and copy one of the css files form this repo _(firefox.profile.chrome folder)_ inside the previous step folder. Rename it if required to "userChrome.css".
* If you already have a userChrome.css (guessing you know CSS) with custom styles, just merge the two files.
* Start / Restart Firefox.

_more about userChrome.css at [mozillaZine UserChrome.css](http://kb.mozillazine.org/index.php?title=UserChrome.css&printable=yes)_  
  
---
  
These css files are distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.