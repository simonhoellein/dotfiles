# Contributions

Contributions and pull requests are welcome.  Please take note of the following guidelines:

*  Adhere to the existing style as much as possible; notably, 2 space indents and long-form keywords.
*  Keep the history clean!  Squash your branches before you submit a pull request.  `pull --rebase` is your friend.
*  Any changes to the core should be tested against Vim 7.4.

# Testing

Contributors should install [thinca/vim-themis](https://github.com/thinca/vim-themis) to run tests before sending a PR if they applied some modification to the code. PRs which do not pass tests won't be accepted.

## 1. Installation

```
$ cd /path/to/vim-airline
$ git submodule add https://github.com/thinca/vim-themis ./.themis-bin
```

## 2. Running tests

```
$ ./path/to/themis-bin/bin/themis path/to/vim-airline/test --reporter spec
```

# Bugs

Tracking down bugs can take a very long time due to different configurations, versions, and operating systems.  To ensure a timely response, please help me out by doing the following:

* the `:version` of vim
* the commit of vim-airline you're using
* the OS that you're using, including terminal emulator, GUI vs non-GUI

# Themes

*  If you submit a theme, please create a screenshot so it can be added to the [Wiki][14].
*  In the majority of cases, modifications to colors of existing themes will likely be rejected.  Themes are a subjective thing, so while you may prefer that a particular color be darker, another user will prefer it to be lighter, or something entirely different.  The more popular the theme, the more unlikely the change will be accepted.  However, it's pretty simple to create your own theme; copy the theme to `~/.vim/autoload/airline/themes` under a new name with your modifications, and it can be used.

# Maintenance

If you would like to take a more active role in improving vim-airline, please consider [becoming a maintainer][43].


[14]: https://github.com/vim-airline/vim-airline/wiki/Screenshots
[43]: https://github.com/vim-airline/vim-airline/wiki/Becoming-a-Maintainer
