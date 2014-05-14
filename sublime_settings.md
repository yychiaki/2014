sublime 3 text editor implements
================================

## Download
- [Download Site](http://www.sublimetext.com/3)
- [Ubuntu 64 bit](http://c758482.r82.cf2.rackcdn.com/sublime-text_build-3059_amd64.deb)

## Install
- $ sudo dpkg -i sublime-text_build-XXXX_amd64.deb (Or sudo apt-get install sublime-text)

## Settings

### [Add Package Control](https://sublime.wbond.net/installation)
- open sublime 
    - view  -> show console [or ctrl + `]
    - paste -> 

import urllib.request,os,hashlib; h = '7183a2d3e96f11eeadd761d777e62404' + 'e330c659d4bb41d3bdf022e94cab3cd0'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://sublime.wbond.net/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by))


### [Install Japanize](http://kwsktr.hatenablog.com/entry/2014/01/08/064300)
- open sublime
    - tool -> commandPalette (Or control + shift + p)
    - type install
        - type japanize
- $ cd ~/.config/sublime-text-3/Packages/Japanize/
- $ cp Main.sublime-menu ../User/
- $ mkdir ../Default
- $ cp *.jp ../Default
- $ cd ../Default
- $ rename "s/.jp$//" *.jp

### [Install Sublime Mozc Input](http://blog.livedoor.jp/hetianchang/archives/1892258.html)
- $ sudo apt-get install emacs-mozc
- open sublime
    - tool -> commandPalette (Or control + shift + p)
    - type Add Repository
        - paste https://github.com/yasuyuky/SublimeMozcInput
    - type install
        - type SublimeMozcInput


### [Install other plugin](http://scotch.io/bar-talk/best-of-sublime-text-3-features-plugins-and-settings)

#### [Install emmet](http://emmet.io)
- open sublime
- tool -> commandPalette (Or control + shift + p)
    - type install
        - type emmet
#### [Install other]
- HTML5
- HTML5Attribute




