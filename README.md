emms-player-mpv.el --- mpv support for EMMS
===========================================

This library provides a player that uses [mpv] for [EMMS].  It
supports pause and seeking.  For loading subtitles automatically, try
adding `autosub-match=fuzzy` to your `~/.mpv/config`, see mpv manual
for more.

This library is based on `emms-player-mplayer.el' in EMMS.

[mpv]: http://mpv.io/
[EMMS]: https://www.gnu.org/software/emms/

Installation
------------

Put `emms-player-mpv.el` in your load path.

Usage
-----

Add the following into your `.emacs`:

``` elisp
(require 'emms-player-mpv)
(add-to-list 'emms-player-list 'emms-player-mpv)
```
