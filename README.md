<img src="https://cdn.rawgit.com/oh-my-fish/oh-my-fish/e4f1c2e0219a17e2c748b824004c8d0b38055c16/docs/logo.svg" align="left" width="144px" height="144px"/>

#### Gentoo fish theme
> A theme for [Oh My Fish][omf-link].

[![MIT License](https://img.shields.io/badge/license-MIT-007EC7.svg?style=flat-square)](/LICENSE)
[![Fish Shell Version](https://img.shields.io/badge/fish-v2.2.0-007EC7.svg?style=flat-square)](https://fishshell.com)
[![Oh My Fish Framework](https://img.shields.io/badge/Oh%20My%20Fish-Framework-007EC7.svg?style=flat-square)](https://www.github.com/oh-my-fish/oh-my-fish)

<br/>


## Install

```fish
$ omf install gentoo
```


## Features

Unofficial Gentoo fish prompt theme which tries to follow Gentoo default bash $PS1.

* Left-hand side:
	* user@host for regular user, green color
	* host for root user, red color
	* full cwd for regular user, short cwd for root, home dir is replaced by ~
	* EXTRA: git branch with state info (if applicable)

* Right-hand side:
	* last error code (if applicable)
	* [timestamp]

## Screenshot

<p align="center">
<img src="http://i.imgur.com/kNvOfd6.png">
</p>

# Credits:

* Forked from https://github.com/oh-my-fish/theme-godfather and modified to follow Gentoo default bash $PS1
* Colors and git functions taken from [amio](https://github.com/amio)'s [edan](https://github.com/oh-my-fish/oh-my-fish/blob/master/db/themes/edan) theme.
* "Gentoo" is a trademark of Gentoo Foundation, Inc.


# License

[MIT][mit] ©


[mit]:            https://opensource.org/licenses/MIT
[author]:         https://github.com/ribugent
[contributors]:   https://github.com/ribugent/theme-gentoo/graphs/contributors
[omf-link]:       https://www.github.com/oh-my-fish/oh-my-fish

[license-badge]:  https://img.shields.io/badge/license-MIT-007EC7.svg?style=flat-square
