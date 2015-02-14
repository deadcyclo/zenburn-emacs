[![License GPL 3][badge-license]](http://www.gnu.org/licenses/gpl-3.0.txt)

## About

Zenburn for Emacs is a direct port of the popular
[Zenburn](http://slinky.imukuppi.org/zenburnpage/) theme for vim,
developed by Jani Nurminen. It's my personal belief (and
that of its many users I presume) that it's one of the best low
contrast color themes out there and that it is exceptionally easy on
the eyes.

This theme uses the new built-in theming support available starting
with Emacs 24.

This is a clone of the original repository with my own added customizations
and some host specific customizations. Unless you know what you are doing
you probably want the original repository.

## Installation

### Manual

Download `zenburn-theme.el` to the directory `~/.emacs.d/themes/`. Add this to your
`.emacs`:

```lisp
(add-to-list 'custom-theme-load-path "~/.emacs.d/themes/")
```

Now you can load the theme with the interactive function `load-theme` like this:

`M-x load-theme RET zenburn`


Cheers,<br\>
[Brendan](http://brendan.is)

