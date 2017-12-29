# Emacs
Configuring Emacs for a complete Python IDE experience

Once you have Emacs set up on your machine, you can replace the existing init.el file with the one above or you can make the necessary additions given below if you wish to keep your existing config.

```
(require 'package)

(add-to-list 'package-archives '("org" . "http://orgmode.org/elpa/"))
(add-to-list 'package-archives '("melpa" . "http://melpa.org/packages/"))
(add-to-list 'package-archives '("melpa-stable" . "http://stable.melpa.org/packages/"))

(setq package-enable-at-startup nil)
(package-initialize)
```
