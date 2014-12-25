 UltiSnip Snippets for Angular
===============================

This repository contains advanced snippet files for [AngularJS](http://angularjs.org/) including Javascript and HTML.

It's a fork of [matthewsimo/angular-vim-snippets](https://github.com/matthewsimo/angular-vim-snippets).

## Installation

### Git Submodule
 - `git submodule add git@github.com:rummik/vim-ng-snippets.git /path/you/want/it/`
 - add `./UltiSnip` it do your list of `g:UltiSnipsSnippetDirectories` and you should be set

### Vundle
Place this in your `.vimrc`:

```
Plugin 'rummik/vim-ng-snippets'
```

… then run the following in Vim:

```
:source %
:PluginInstall
```

For Vundle version < 0.10.2, replace `Plugin` with `Bundle` above.
