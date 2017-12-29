# Emacs
Configuring Emacs for a complete Python IDE experience

Once you have Emacs set up on your machine, you can replace the existing init.el file with the one above or you can make the following necessary additions if you wish to keep your existing config.



The following code loads up the Emacs package manager and upadates the list of available packages with newer packages from the online repos.

```
(require 'package)

(add-to-list 'package-archives '("org" . "http://orgmode.org/elpa/"))
(add-to-list 'package-archives '("melpa" . "http://melpa.org/packages/"))
(add-to-list 'package-archives '("melpa-stable" . "http://stable.melpa.org/packages/"))

(setq package-enable-at-startup nil)
(package-initialize)
```
Now, save the changes and restart Emacs. Use the following command to see the updated packages list. 

`M+x and type package-list-packages`

Select the following packages for install. These packages corrosponds to various features of an IDE

1. Anaconda
2. Company Anaconda
3. Flycheck
4. Yapfify
5. Helm*
