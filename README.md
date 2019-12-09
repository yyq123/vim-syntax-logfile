# vim-syntax-logfile

Based on [MTDL9/vim-log-highlighting] (https://github.com/MTDL9/vim-log-highlighting)

![Log highlighting example](doc/Syntax_logfile.png)

## Overview

Provides syntax highlighting for generic log files in VIM.

Some of the highlighted elements are:
- Dates and times
- Common log level keywords like ERROR, INFO, DEBUG
- Numbers, booleans and strings
- URLs and file paths
- IP and MAC addresses
- SysLog format columns
- XML Tags



## Installation

### [VimPlug](https://github.com/junegunn/vim-plug)

Add `Plug 'yyq123/vim-syntax-logfile'` to your `~/.vimrc` and run `PlugInstall`.

### [Vundle](https://github.com/gmarik/Vundle.vim)

Add `Plugin 'yyq123/vim-syntax-logfile'` to your `~/.vimrc` and run `PluginInstall`.

### [Pathogen](https://github.com/tpope/vim-pathogen)

    $ git clone https://github.com/yyq123/vim-syntax-logfile ~/.vim/bundle/vim-log-highlighting

### Manual Install

Copy the contents of the `syntax` folders in their respective ~/.vim/\* counterparts.



## Configuration

Once installed, the syntax highlighting will be enabled by default for files ending with `.log` suffixes.


## Related Projects

* VIM Built-in /var/log/messages highlighting
* [vim-log-syntax](https://github.com/dzeban/vim-log-syntax) by dzeban
* [vim-log4j](https://github.com/tetsuo13/Vim-log4j) by tetsuo13
* [ccze](https://github.com/cornet/ccze) by cornet
