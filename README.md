# awesome-colorterm
A curated list of scripts, programs, and other functions for a colorful terminal environment.

### Info
You'll probably want to set your terminal type to xterm-256color or screen-256color.

### Contents
* [Colorful wrapper scripts & alternatives to common terminal commands](#colorful-wrapper-scripts--alternatives)
* [Parameters for common commands to enable colored output](#parameters)
* [Color definitions for GRC](#grc-definitions)
* [Color definitions for various terminal applications (PuTTY, xterm, etc)](#terminal-colors)
* [Color definitions for various shells](#shell-colors)
* [Other Resources](#other-resources)

### Colorful wrapper scripts & alternatives
* [`cdu`](http://arsunik.free.fr/prog/cdu.html) - (for Color `du`) is a perl script which call du and display a pretty histogram with optional colors which allow to imediatly see the directories which take disk space.
* [`grc`](http://kassiopeia.juls.savba.sk/~garabik/software/grc.html) - yet another colouriser (written in python) for beautifying your logfiles or output of commands.
* [`dfc`](http://projects.gw-computing.net/projects/dfc) - displays file system space usage using graphs and colors. Based on `df`. able to use colors, draw graphs and export to CSV, HTML.
* [nojhan/liquidprompt](https://github.com/nojhan/liquidprompt) - for bash and zsh
* [`colormake`](http://bre.klaki.net/programs/colormake/) - a perl wrapper for `make` that colorizes the output
* [`colormake`](https://github.com/dcjones/colormake) - a python wrapper for `make` that colorizes the output
* [trapd00r/File-LsColor](https://github.com/trapd00r/File-LsColor) - Colorize input filenames just like ls(1) does
* [`colorex`](https://bitbucket.org/linibou/colorex/wiki/Home) - display files or sdtin with pretty colors for matched patterns.
* [`rainbow`](https://github.com/nicoulaj/rainbow) - Colorize commands output or STDIN using patterns. (fork of colorex)
* [`tput`](http://tldp.org/HOWTO/Bash-Prompt-HOWTO/x405.html) - move the cursor around the screen, set colors. [examples](http://web.archive.org/web/20150516204328/http://wiki.bash-hackers.org/scripting/terminalcodes)
* [`tcolors`](https://github.com/mkoskar/tcolors)
* [colortest](https://launchpad.net/ubuntu/raring/+package/colortest) - utilities to test color capabilities of terminal
* [`multitail`](http://www.vanheusden.com/multitail/) - allows you to monitor logfiles and command output in multiple windows in a terminal, colorize, filter and merge

### Parameters
* `less` - use `-r` to include color (and other escapes)
* `grep` - use `--color=always` or `--color=auto`
* `ls` - use `--color=always` or `--color=auto`

### grc definitions
* [Apache/nginx logs](https://gist.github.com/vjt/1885569) `grc` definitions
* [seebi/dircolors-solarized](https://github.com/seebi/dircolors-solarized)

### Terminal colors
* [altercation/solarized](http://ethanschoonover.com/solarized) - Just solarized PuTTY colors ([homepage](https://github.com/altercation/solarized/tree/master/PuTTY-colors-solarized))
* [jblaine/solarized-and-modern-PuTTY](https://github.com/jblaine/solarized-and-modern-PuTTY) - Solarized Modern PuTTY Defaults
* [Monokai](https://gist.github.com/GDvalle/4187089) for PuTTY
* [Heavenly](https://github.com/soumyadipdm/Heavenly-PuTTY-color-scheme) for PuTTY
* [Igvita](https://www.igvita.com/2008/04/14/custom-PuTTY-color-themes/) for PuTTY (two themes)
* [Zenburn](http://looselytyped.blogspot.com/2013/02/zenburn-pleasant-color-scheme-for-putty.html) for PuTTY
* [Darekkay's theme@Ecletide](http://eclectide.com/blog/2015/03/21/my-putty-color-scheme/) for PuTTY
* [4bit Terminal Color Scheme Designer](http://ciembor.github.io/4bit/) - generate color definitions for multiple terminals, including PuTTY, xterm, gnome-terminal, mintty, and konsole
* [Terminal.sexy](https://terminal.sexy) - Similar to above 4bit designer, with different output formats (also including PuTTY

### Shell colors
* [zsh syntax highlighting](https://github.com/trapd00r/zsh-syntax-highlighting-filetypes)
* [TMux Solarized theme](https://github.com/seebi/tmux-colors-solarized)
* [oh-my-zsh themes](http://zshthem.es/all)
* [trapd00r/LS_COLORS](https://github.com/trapd00r/LS_COLORS) - a collection of extension:color mappings, suitable to use as your LS COLORS environment variable

### Other resources
* [A stylesheet author's guide to terminal colors](http://wynnnetherland.com/journal/a-stylesheet-author-s-guide-to-terminal-colors/)
* [Textmate to Vim, JEdit and Kate/KWrite color scheme converter](https://github.com/ciembor/coloration)
* [A collection of color themes for Geany](https://github.com/ciembor/geany-themes)
* [Color Bash Prompt](https://wiki.archlinux.org/index.php/Color_Bash_Prompt) from Arch Linux wiki.
* [Byobu](http://byobu.co) - a wrapper for `screen` and `tmux`, provides notifications and other info.
* [git-prompt.sh](http://git-prompt.sh/) - colorized git prompt. Included in liquidprompt.
* [Bash tips: Colors and formatting](http://misc.flogisoft.com/bash/tip_colors_and_formatting) - ANSI/VT100 Control sequences
* [Testcolor scripts](http://unix.stackexchange.com/questions/41563/how-to-create-a-testcolor-sh-like-the-following-screenshot)




[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the author has waived all copyright and related or neighboring rights to this work.
