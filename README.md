# New Hackbar
[![addons.mozilla.org/](https://addons.cdn.mozilla.net/static/img/addons-buttons/AMO-button_2.png)](https://addons.mozilla.org/firefox/addon/new-hackbar/)

A sitebar that helps pentesters to perform manual web security testing inside their browser. This addon is written in webextension and alternatives to the XUL version of original Hackbar.

There will definitely be some of bugs, please give me any bugs and comments to improve it.

* Deverloper: mxcx
* Email: mxcxvn@gmail.com
* Blog: http://fosec.vn

The original add-on (XUL-based) at https://addons.mozilla.org/firefox/addon/hackbar/

## Some features now:
1. Almost of features and gui in this version is based on the original addon (hackbar).
2. The importance changes are this version is written in webextension technology in stead of the XUL technology in the original version. The original version is best but if you want to use the hackbar in firefox > 57 (Quantum), you must use this version. The XUL addon is not supported anymore.
3. I tried to make this version as similar as possible to the original. However, due to the new policy of firefox version, the position of the new hackbar must move to sidebar (left or right).
4. Most of core functions is completed. However, due to the limited size in menu bar, some string functions are temporary not have in this version. I am trying to port all of them. If anyone who have any idea about the layout, please contact me.
5. Shortcut:
+ Toggle on/off New Hackbar: F9
+ Load Url: Alt + A or Alt + Z and Control + Z on Mac
+ Execute: Alt + X and Control + X on Mac
+ Split Url: Alt + S and Control + S on Mac

## Log changes:
### 07 January 2018: Update 1.0.3
+ Add shortcut for LoadUrl, Execute, Split Url
+ Fix bug when post raw data
+ Fix bug when post in new tab