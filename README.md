```
 █████╗ ██╗    ██╗███████╗███████╗ ██████╗ ███╗   ███╗███████╗
██╔══██╗██║    ██║██╔════╝██╔════╝██╔═══██╗████╗ ████║██╔════╝
███████║██║ █╗ ██║█████╗  ███████╗██║   ██║██╔████╔██║█████╗
██╔══██║██║███╗██║██╔══╝  ╚════██║██║   ██║██║╚██╔╝██║██╔══╝
██║  ██║╚███╔███╔╝███████╗███████║╚██████╔╝██║ ╚═╝ ██║███████╗
╚═╝  ╚═╝ ╚══╝╚══╝ ╚══════╝╚══════╝ ╚═════╝ ╚═╝     ╚═╝╚══════╝
███████╗██╗  ██╗███████╗██╗     ██╗
██╔════╝██║  ██║██╔════╝██║     ██║
███████╗███████║█████╗  ██║     ██║
╚════██║██╔══██║██╔══╝  ██║     ██║
███████║██║  ██║███████╗███████╗███████╗
╚══════╝╚═╝  ╚═╝╚══════╝╚══════╝╚══════╝
```

# Awesome Shell [![Awesome][awesome-badge]][awesome-link]

A curated list of awesome command-line frameworks, toolkits, guides and gizmos. Inspired by awesome-php. This awesome collection is also available on [Unix-Shell.ZEEF.com](https://unix-shell.zeef.com/caleb.xu).
- [Shells](#shells)
- [Command-Line Productivity](#command-line-productivity)
  - [Directory Navigation](#directory-navigation)
- [Customization](#customization)
- [For Developers](#for-developers)
- [System Utilities](#system-utilities)
- [Downloading and Serving](#downloading-and-serving)
- [Multimedia and File Formats](#multimedia-and-file-formats)
- [Applications](#applications)
- [Games](#games)
- [Shell Package Management](#shell-package-management)
- [Shell Script Development](#shell-script-development)
- [Guides](#guides)
- [**Awesome Zsh**][awesome-zsh]&nbsp; [![Awesome][awesome-badge]][awesome-zsh]
- [**Awesome Fish**][awesome-fish] [![Awesome][awesome-badge]][awesome-fish]
- [Other Awesome Lists](#other-awesome-lists)

## Shells

*Choose your base shell.*

* [bash](https://www.gnu.org/software/bash/) - GNU Project's shell (Bourne Again SHell)
* [elvish](https://elv.sh/) - Friendly, expressive shell features like anonymous functions and data structures
* [es](https://wryun.github.io/es-shell/) - The extensible shell, based on Plan 9's <code>&nbsp;&nbsp;&nbsp;187</code> ![](https://img.shields.io/github/last-commit/rakitzis/rc) [rc](https://github.com/rakitzis/rc) shell
* [fish](https://fishshell.com) - Smart and user-friendly command line shell
* <code>&nbsp;&nbsp;1246</code> ![](https://img.shields.io/github/last-commit/redox-os/ion) [ion](https://github.com/redox-os/ion) - A modern system shell that features a simple, yet powerful, syntax. It is written entirely in Rust.
* <code>&nbsp;&nbsp;&nbsp;429</code> ![](https://img.shields.io/github/last-commit/att/ast) [ksh93](https://github.com/att/ast) - Korn Shell
* <code>&nbsp;&nbsp;&nbsp;164</code> ![](https://img.shields.io/github/last-commit/MirBSD/mksh) [mksh](https://github.com/MirBSD/mksh) - MirBSD Korn Shell
* <code>&nbsp;&nbsp;1111</code> ![](https://img.shields.io/github/last-commit/ngs-lang/ngs) [ngs](https://github.com/ngs-lang/ngs) - Fully featured scripting language created specifically for Ops. REPL is being developed.
* <code>&nbsp;18379</code> ![](https://img.shields.io/github/last-commit/nushell/nushell) [nushell](https://github.com/nushell/nushell) - A modern shell written in Rust
* <code>&nbsp;&nbsp;&nbsp;209</code> ![](https://img.shields.io/github/last-commit/ibara/oksh) [oksh](https://github.com/ibara/oksh) - Portable OpenBSD ksh
* [osh](https://www.oilshell.org) - Bash compatible, with new/modern Unix shell language called Oil
* [pdksh](https://cvsweb.openbsd.org/cgi-bin/cvsweb/src/bin/ksh/) - Public domain Korn shell
* [powershell](https://docs.microsoft.com/en-us/powershell/scripting/overview) a cross-platform task automation and configuration management framework, consisting of a command-line shell and scripting language
* <code>&nbsp;&nbsp;&nbsp;&nbsp;97</code> ![](https://img.shields.io/github/last-commit/alexst07/shell-plus-plus) [shell++](https://github.com/alexst07/shell-plus-plus) - Friendly and modern functional and object oriented shell script language
* <code>&nbsp;&nbsp;&nbsp;&nbsp;27</code> ![](https://img.shields.io/github/last-commit/shenv/shenv) [shenv](https://github.com/shenv/shenv) - Simple shell version management
* [tcsh](https://www.tcsh.org/) - C shell with file name completion and command line editing
* [xonsh](https://xon.sh) - Python-ish, BASHwards-looking shell language and command prompt
* [yash](https://yash.osdn.jp/) - A POSIX-compliant command line shell with built-in support for completion and prediction based on command history
* [zsh](https://www.zsh.org) - Powerful shell with scripting language

## Command-Line Productivity

*Search, bookmarks, multiplexing, and other tools that make your terminal experience more productive.*

* <code>&nbsp;&nbsp;&nbsp;175</code> ![](https://img.shields.io/github/last-commit/tanrax/terminal-AdvancedNewFile) [AdvancedNewFile](https://github.com/tanrax/terminal-AdvancedNewFile) - Fast creation of files and directories in a recursive way. Inspired by the Vim plugin.
* <code>&nbsp;23516</code> ![](https://img.shields.io/github/last-commit/ggreer/the_silver_searcher) [ag](https://github.com/ggreer/the_silver_searcher) - Super fast string search through a directory hierarchy
* <code>&nbsp;&nbsp;&nbsp;418</code> ![](https://img.shields.io/github/last-commit/sebglazebrook/aliases) [aliases](https://github.com/sebglazebrook/aliases) - Contextual, dynamic, organized aliases for bash
* <code>&nbsp;&nbsp;4911</code> ![](https://img.shields.io/github/last-commit/inishchith/autoenv) [autoenv](https://github.com/inishchith/autoenv) - Directory-based environments
* <code>&nbsp;&nbsp;&nbsp;236</code> ![](https://img.shields.io/github/last-commit/nikolassv/bartib) [bartib](https://github.com/nikolassv/bartib) - A simple timetracker for the command line. It saves a log of all tracked activities as a plaintext file and allows you to create flexible reports.
* <code>&nbsp;&nbsp;&nbsp;967</code> ![](https://img.shields.io/github/last-commit/rcaloras/bashhub-client) [bashhub](https://github.com/rcaloras/bashhub-client) - :cloud: Bash history in the cloud. Indexed and searchable.
* <code>&nbsp;&nbsp;1452</code> ![](https://img.shields.io/github/last-commit/tmrts/boilr) [boilr](https://github.com/tmrts/boilr) - A blazingly fast CLI tool for creating projects from boilerplate templates.
* <code>&nbsp;&nbsp;1213</code> ![](https://img.shields.io/github/last-commit/holman/boom) [boom](https://github.com/holman/boom) - Store links and snippets in the command line
* <code>&nbsp;&nbsp;1540</code> ![](https://img.shields.io/github/last-commit/ok-borg/borg) [borg](https://github.com/ok-borg/borg) - A terminal based search engine for bash commands
* <code>&nbsp;14257</code> ![](https://img.shields.io/github/last-commit/browsh-org/browsh) [browsh](https://github.com/browsh-org/browsh) - The modern text-based browser
* <code>&nbsp;&nbsp;5046</code> ![](https://img.shields.io/github/last-commit/jarun/Buku) [Buku](https://github.com/jarun/Buku) - Powerful command-line bookmark manager
* [byobu](https://www.byobu.org) - Text-based window manager and terminal multiplexer
* <code>&nbsp;&nbsp;&nbsp;381</code> ![](https://img.shields.io/github/last-commit/dim-an/cod) [cod](https://github.com/dim-an/cod) — A completion daemon for shell that learns when you invoke `--help` commands
* <code>&nbsp;&nbsp;&nbsp;&nbsp;64</code> ![](https://img.shields.io/github/last-commit/skywind3000/CloudClip) [CloudClip](https://github.com/skywind3000/CloudClip) - Your own clipboard in the cloud, copy and paste text with gist between different systems
* <code>&nbsp;&nbsp;2332</code> ![](https://img.shields.io/github/last-commit/jarun/ddgr) [ddgr](https://github.com/jarun/ddgr) - DuckDuckGo from the terminal
* <code>&nbsp;&nbsp;2438</code> ![](https://img.shields.io/github/last-commit/jamesob/desk) [desk](https://github.com/jamesob/desk) - A lightweight workspace manager for the shell
* <code>&nbsp;&nbsp;8910</code> ![](https://img.shields.io/github/last-commit/direnv/direnv) [direnv](https://github.com/direnv/direnv) - An environment switcher for the shell, compare with autoenv
* <code>&nbsp;&nbsp;2271</code> ![](https://img.shields.io/github/last-commit/dnote/dnote) [dnote](https://github.com/dnote/dnote) - A simple command line notebook with multi-device sync and web interface
* <code>&nbsp;&nbsp;&nbsp;471</code> ![](https://img.shields.io/github/last-commit/simeg/eureka) [eureka](https://github.com/simeg/eureka/) - :bulb: CLI tool to input and store your ideas without leaving the terminal
* <code>&nbsp;&nbsp;5705</code> ![](https://img.shields.io/github/last-commit/clvv/fasd) [fasd](https://github.com/clvv/fasd) - Command-line productivity booster, offers quick access to files and directories
* <code>&nbsp;21710</code> ![](https://img.shields.io/github/last-commit/sharkdp/fd) [fd](https://github.com/sharkdp/fd) - A simple, fast and user-friendly alternative to find.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;37</code> ![](https://img.shields.io/github/last-commit/s-p-k/foxy) [foxy](https://github.com/s-p-k/foxy) - Plain text bookmarks for Firefox and surf browsers.
* <code>&nbsp;&nbsp;3217</code> ![](https://img.shields.io/github/last-commit/jhspetersson/fselect) [fselect](https://github.com/jhspetersson/fselect) - Find files with SQL-like queries.
* <code>&nbsp;&nbsp;&nbsp;586</code> ![](https://img.shields.io/github/last-commit/bbugyi200/funky) [funky](https://github.com/bbugyi200/funky) - Extends functionality of shell functions making them more powerful and flexible.
* <code>&nbsp;&nbsp;&nbsp;401</code> ![](https://img.shields.io/github/last-commit/changyuheng/fz) [fz](https://github.com/changyuheng/fz) - Seamless fuzzy tab completion for z
* <code>&nbsp;43643</code> ![](https://img.shields.io/github/last-commit/junegunn/fzf) [fzf](https://github.com/junegunn/fzf) - A command-line fuzzy finder
* <code>&nbsp;&nbsp;&nbsp;280</code> ![](https://img.shields.io/github/last-commit/arl/gitmux) [gitmux](https://github.com/arl/gitmux) - Show Git status in Tmux status bar
* <code>&nbsp;&nbsp;5734</code> ![](https://img.shields.io/github/last-commit/jarun/googler) [googler](https://github.com/jarun/googler) - Google Search, Google Site Search, Google News from the terminal
* <code>&nbsp;&nbsp;&nbsp;&nbsp;33</code> ![](https://img.shields.io/github/last-commit/Astranno/googlr) [googlr](https://github.com/Astranno/googlr) - Command line tool that lets you search Google from your terminal.
* <code>&nbsp;&nbsp;&nbsp;414</code> ![](https://img.shields.io/github/last-commit/kdabir/has) [has](https://github.com/kdabir/has) - `has` helps you check presence of various command line tools and their versions on path
* <code>&nbsp;&nbsp;5479</code> ![](https://img.shields.io/github/last-commit/santinic/how2) [how2](https://github.com/santinic/how2) - `how2` finds the simplest way to do something in a unix shell. It's like `man`, but you can query it in natural language.
* <code>&nbsp;10887</code> ![](https://img.shields.io/github/last-commit/denisidoro/navi) [navi](https://github.com/denisidoro/navi) - An interactive cheatsheet tool for the command-line
* <code>&nbsp;&nbsp;&nbsp;395</code> ![](https://img.shields.io/github/last-commit/paoloantinori/hhighlighter) [hhighlighter](https://github.com/paoloantinori/hhighlighter) - Colorize words in a command output
* <code>&nbsp;&nbsp;1214</code> ![](https://img.shields.io/github/last-commit/LuRsT/hr) [hr](https://github.com/LuRsT/hr) - `<hr />` for your terminal
* <code>&nbsp;&nbsp;&nbsp;295</code> ![](https://img.shields.io/github/last-commit/six-ddc/hss) [hss](https://github.com/six-ddc/hss) - An interactive parallel ssh client featuring autocomplete and asynchronous execution
* <code>&nbsp;&nbsp;3078</code> ![](https://img.shields.io/github/last-commit/dvorka/hstr) [hstr](https://github.com/dvorka/hstr) - Bash History Suggest Box
* <code>&nbsp;&nbsp;1618</code> ![](https://img.shields.io/github/last-commit/supercrabtree/k) [k](https://github.com/supercrabtree/k) - k is a Zsh script to make directory listings more readable, adding Git status, fileweight colors and rotting dates
* <code>&nbsp;&nbsp;&nbsp;&nbsp;16</code> ![](https://img.shields.io/github/last-commit/lingtalfi/k) [k alias](https://github.com/lingtalfi/k) - get kool aliases (and more) working with a simple one-liner
* <code>&nbsp;&nbsp;&nbsp;&nbsp;35</code> ![](https://img.shields.io/github/last-commit/suewonjp/lf.sh) [lf.sh](https://github.com/suewonjp/lf.sh) - Quickly search files with fewer typings and do many more (grepping, copying path to clipboard, etc)
* <code>&nbsp;&nbsp;&nbsp;&nbsp;80</code> ![](https://img.shields.io/github/last-commit/juan-leon/lowcharts) [lowcharts](https://github.com/juan-leon/lowcharts) - Draw low-resolution graphs in terminal
* [Lmod](https://lmod.readthedocs.io/en/latest/) - Lua-based Environment Modules that enhances Tcl-based modules while being backward compatible (compare to modules)
* <code>&nbsp;&nbsp;&nbsp;575</code> ![](https://img.shields.io/github/last-commit/Miserlou/Loop) [loop](https://github.com/Miserlou/Loop) - Write and control complex loops with as one-liners
* <code>&nbsp;&nbsp;1867</code> ![](https://img.shields.io/github/last-commit/pindexis/marker) [marker](https://github.com/pindexis/marker) - Bookmark your shell commands
* <code>&nbsp;11953</code> ![](https://img.shields.io/github/last-commit/lra/mackup) [mackup](https://github.com/lra/mackup/) - Keep your application settings in sync (OS X/Linux)
* <code>&nbsp;&nbsp;3934</code> ![](https://img.shields.io/github/last-commit/cantino/mcfly) [mcfly](https://github.com/cantino/mcfly) - Fly through your shell history. Great Scot!
* [modules](http://modules.sourceforge.net/) - Classical Tcl-based Environment Modules managing the shell environment (compare to Lmod, direnv, and autoenv)
* <code>&nbsp;13882</code> ![](https://img.shields.io/github/last-commit/jarun/nnn) [nnn](https://github.com/jarun/nnn) - File browser and disk usage analyzer with excellent desktop integration
* [parallel](https://www.gnu.org/software/parallel/) - Build and execute shell command lines from standard input in parallel
* [pass](https://www.passwordstore.org/) - Manage passwords from the command line with GPG encryption and optional git integration.
* <code>&nbsp;&nbsp;4731</code> ![](https://img.shields.io/github/last-commit/facebook/PathPicker) [pathpicker](https://github.com/facebook/PathPicker) - Accepts inputs like grep, searches, git etc; allows selecting files from the result of the input, which you can then open or provide as argument to a command.
* <code>&nbsp;&nbsp;&nbsp;258</code> ![](https://img.shields.io/github/last-commit/jarun/pdd) [pdd](https://github.com/jarun/pdd) - Tiny date, time diff calculator with timers
* <code>&nbsp;&nbsp;3111</code> ![](https://img.shields.io/github/last-commit/mooz/percol) [percol](https://github.com/mooz/percol) - Adds flavor of interactive filtering to the traditional pipe concept of UNIX shell
* <code>&nbsp;&nbsp;&nbsp;&nbsp;55</code> ![](https://img.shields.io/github/last-commit/cal2195/q) [q](https://github.com/cal2195/q) - Vim like macro registers for your Bash and Zsh Shell
* <code>&nbsp;&nbsp;&nbsp;528</code> ![](https://img.shields.io/github/last-commit/pindexis/qfc) [qfc](https://github.com/pindexis/qfc) - File-completion widget for Bash and Zsh
* <code>&nbsp;&nbsp;&nbsp;353</code> ![](https://img.shields.io/github/last-commit/curusarn/resh) [resh](https://github.com/curusarn/resh) - Contextual shell history for Zsh and Bash
* <code>&nbsp;30442</code> ![](https://img.shields.io/github/last-commit/BurntSushi/ripgrep) [rg](https://github.com/BurntSushi/ripgrep) - ripgrep is a line oriented search tool that combines the usability of The Silver Searcher with the raw speed of GNU grep
* [screen](https://www.gnu.org/software/screen/) - GNU terminal multiplexer
* <code>&nbsp;&nbsp;&nbsp;&nbsp;93</code> ![](https://img.shields.io/github/last-commit/pawamoy/shell-history) [shell-history](https://github.com/pawamoy/shell-history) - Visualize your shell usage with Highcharts
* <code>&nbsp;&nbsp;&nbsp;416</code> ![](https://img.shields.io/github/last-commit/odb/shml) [SHML](https://github.com/odb/shml) - Style framework for the terminal (Shell Markup Language)
* <code>&nbsp;&nbsp;&nbsp;272</code> ![](https://img.shields.io/github/last-commit/benlinton/slugify) [slugify](https://github.com/benlinton/slugify) - Command that converts filenames and directories to a web friendly format
* <code>&nbsp;&nbsp;&nbsp;262</code> ![](https://img.shields.io/github/last-commit/tokozedg/sman) [sman](https://github.com/tokozedg/sman) - :bug: A command-line snippet manager
* <code>&nbsp;&nbsp;5812</code> ![](https://img.shields.io/github/last-commit/holman/spark) [spark](https://github.com/holman/spark) - ▁▂▃▅▂▇ in your shell
* <code>&nbsp;&nbsp;&nbsp;268</code> ![](https://img.shields.io/github/last-commit/jorgebucaran/spark.fish) [spark.fish](https://github.com/jorgebucaran/spark.fish) - ▁▂▃▅ Sparkline Generator
* <code>&nbsp;&nbsp;&nbsp;246</code> ![](https://img.shields.io/github/last-commit/oscardelben/sheet) [sheet](https://github.com/oscardelben/sheet) -  Text snippets for the command line
* <code>&nbsp;&nbsp;&nbsp;887</code> ![](https://img.shields.io/github/last-commit/rauchg/spot) [spot](https://github.com/rauchg/spot) - Tiny file search utility
- <code>&nbsp;&nbsp;&nbsp;&nbsp;54</code> ![](https://img.shields.io/github/last-commit/srijanshetty/snips) [snips](https://github.com/srijanshetty/snips) - Command line tool to manage snippets of code.
* <code>&nbsp;&nbsp;&nbsp;502</code> ![](https://img.shields.io/github/last-commit/julianhyde/sqlline) [sqlline](https://github.com/julianhyde/sqlline) - Shell for issuing SQL to relational databases via JDBC (multiline, completion, highlighting, dialect support)
* <code>&nbsp;&nbsp;&nbsp;962</code> ![](https://img.shields.io/github/last-commit/osxfuse/sshfs) [sshfs](https://github.com/osxfuse/sshfs) - A tool for mounting remote file systems over SSH
* <code>&nbsp;&nbsp;&nbsp;143</code> ![](https://img.shields.io/github/last-commit/badarsh2/Sudocabulary) [sudocabulary](https://github.com/badarsh2/Sudocabulary) - Learn English Vocabulary from your terminal
* [surfraw](https://gitlab.com/surfraw/Surfraw) - browse specific site and search the web from your terminal without browser.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> ![](https://img.shields.io/github/last-commit/lingtalfi/task-manager) [task-manager](https://github.com/lingtalfi/task-manager) - Execute all your scripts with just two or three keystrokes.
* <code>&nbsp;&nbsp;&nbsp;144</code> ![](https://img.shields.io/github/last-commit/darrikonn/td-cli) [td-cli](https://github.com/darrikonn/td-cli) - A todo command line manager to organize and manage your todos across multiple projects.
* <code>&nbsp;70295</code> ![](https://img.shields.io/github/last-commit/nvbn/thefuck) [thefuck](https://github.com/nvbn/thefuck) - Fix common shell mistakes by using an easy to remember command
* <code>&nbsp;&nbsp;&nbsp;641</code> ![](https://img.shields.io/github/last-commit/raylee/tldr-sh-client) [tldr](https://github.com/raylee/tldr-sh-client) - A fully-functional bash client for tldr, simplified and community-driven man pages
* [tmux](https://tmux.github.io/) - Amazing terminal multiplexer
* <code>&nbsp;&nbsp;&nbsp;&nbsp;92</code> ![](https://img.shields.io/github/last-commit/xtyrrell/undollar) [undollar](https://github.com/xtyrrell/undollar) - undollar bites the dollar sign off the tip of the command you just pasted into your terminal
* <code>&nbsp;&nbsp;7151</code> ![](https://img.shields.io/github/last-commit/xo/usql) [usql](https://github.com/xo/usql) - Universal command-line interface for SQL databases.
* <code>&nbsp;&nbsp;&nbsp;418</code> ![](https://img.shields.io/github/last-commit/rupa/v) [v](https://github.com/rupa/v) - z for vim.
* <code>&nbsp;&nbsp;3509</code> ![](https://img.shields.io/github/last-commit/zolrath/wemux) [wemux](https://github.com/zolrath/wemux) - Multi-User Tmux Made Easy
* [xiki](https://xiki.org) - Makes the shell console more friendly and powerful
* <code>&nbsp;&nbsp;1732</code> ![](https://img.shields.io/github/last-commit/sayanarijit/xplr) [xplr](https://github.com/sayanarijit/xplr) -  A hackable, minimal, fast TUI file explorer
* <code>&nbsp;&nbsp;8215</code> ![](https://img.shields.io/github/last-commit/BurntSushi/xsv) [xsv](https://github.com/BurntSushi/xsv) - a fast CSV command line toolkit written in Rust
* <code>&nbsp;&nbsp;3243</code> ![](https://img.shields.io/github/last-commit/xxh/xxh) [xxh](https://github.com/xxh/xxh) - Bring your favorite shell wherever you go through the SSH.

### Directory Navigation

* <code>&nbsp;&nbsp;&nbsp;101</code> ![](https://img.shields.io/github/last-commit/Jintin/aliasme) [aliasme](https://github.com/Jintin/aliasme) - alias helper to change directory quickly
* <code>&nbsp;13638</code> ![](https://img.shields.io/github/last-commit/wting/autojump) [autojump](https://github.com/wting/autojump) - A cd command that learns - easily navigate directories from the command line
* <code>&nbsp;&nbsp;1731</code> ![](https://img.shields.io/github/last-commit/huyng/bashmarks) [bashmarks](https://github.com/huyng/bashmarks) - Directory bookmarks for the shell
* <code>&nbsp;&nbsp;&nbsp;865</code> ![](https://img.shields.io/github/last-commit/vigneshwaranr/bd) [bd](https://github.com/vigneshwaranr/bd) - Quickly go back to a parent directory
* <code>&nbsp;&nbsp;&nbsp;324</code> ![](https://img.shields.io/github/last-commit/shyiko/commacd) [commacd](https://github.com/shyiko/commacd) - A faster way to move around in Bash
* <code>&nbsp;&nbsp;2125</code> ![](https://img.shields.io/github/last-commit/b4b4r07/enhancd) [enhancd](https://github.com/b4b4r07/enhancd) - :rocket: A next-generation cd command with an interactive filter
* <code>&nbsp;&nbsp;&nbsp;800</code> ![](https://img.shields.io/github/last-commit/iridakos/goto) [goto](https://github.com/iridakos/goto) - A shell utility for navigation to aliased directories supporting auto-completion
* <code>&nbsp;&nbsp;1347</code> ![](https://img.shields.io/github/last-commit/gsamokovarov/jump) [jump](https://github.com/gsamokovarov/jump) - Jump helps you navigate your file system faster by learning your habits.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;20</code> ![](https://img.shields.io/github/last-commit/pedramamini/lazy-cd) [lazy-cd](https://github.com/pedramamini/lazy-cd) - Simple bash commands for bookmarked navigation of the file system, complete with bash-completion.
* <code>&nbsp;&nbsp;&nbsp;139</code> ![](https://img.shields.io/github/last-commit/shannonmoeller/up) [up](https://github.com/shannonmoeller/up) - Ascend directories by name or count; for bash, zsh, and fish.
* <code>&nbsp;14111</code> ![](https://img.shields.io/github/last-commit/rupa/z) [z](https://github.com/rupa/z) - z is the new j, yo
* <code>&nbsp;&nbsp;2257</code> ![](https://img.shields.io/github/last-commit/skywind3000/z.lua) [z.lua](https://github.com/skywind3000/z.lua) - A new cd command that helps you navigate faster by learning your habits
* <code>&nbsp;&nbsp;5894</code> ![](https://img.shields.io/github/last-commit/ajeetdsouza/zoxide) [zoxide](https://github.com/ajeetdsouza/zoxide) - A faster way to navigate your filesystem, written in Rust
* <code>&nbsp;&nbsp;&nbsp;&nbsp;91</code> ![](https://img.shields.io/github/last-commit/sakshamsharma/zpyi) [zpyi](https://github.com/sakshamsharma/zpyi) - Python in Zsh - Easy python scripting in shell

## Customization

*Custom prompts, color themes, etc.*

* <code>&nbsp;&nbsp;&nbsp;384</code> ![](https://img.shields.io/github/last-commit/base16-builder/base16-builder) [base16-builder](https://github.com/base16-builder/base16-builder) - Base16-Builder
* <code>&nbsp;&nbsp;&nbsp;145</code> ![](https://img.shields.io/github/last-commit/slomkowski/bash-full-of-colors) [bash-full-of-colors](https://github.com/slomkowski/bash-full-of-colors) - Powerful prompt with screen, tmux, git support and many more
* <code>&nbsp;&nbsp;6226</code> ![](https://img.shields.io/github/last-commit/magicmonty/bash-git-prompt) [bash-git-prompt](https://github.com/magicmonty/bash-git-prompt) - An informative and fancy Bash prompt for Git users
* <code>&nbsp;&nbsp;&nbsp;834</code> ![](https://img.shields.io/github/last-commit/riobard/bash-powerline) [bash-powerline](https://github.com/riobard/bash-powerline) - Powerline-style Bash prompt in pure Bash script
* <code>&nbsp;&nbsp;1563</code> ![](https://img.shields.io/github/last-commit/barryclark/bashstrap) [bashstrap](https://github.com/barryclark/bashstrap) - A quick way to spruce up OSX terminal
* <code>&nbsp;&nbsp;2658</code> ![](https://img.shields.io/github/last-commit/caiogondim/bullet-train.zsh) [bullet-train-oh-my-zsh-theme](https://github.com/caiogondim/bullet-train.zsh) - :bullettrain_side: An oh-my-zsh shell theme based on the Powerline Vim plugin
* <code>&nbsp;&nbsp;1484</code> ![](https://img.shields.io/github/last-commit/mrowa44/emojify) [emojify](https://github.com/mrowa44/emojify) Emoji on the command line :scream:
* [flatui-terminal-theme](https://dribbble.com/shots/1021755-Flat-UI-Terminal-Theme) - Nicer colors for terminal
* <code>&nbsp;&nbsp;&nbsp;826</code> ![](https://img.shields.io/github/last-commit/geometry-zsh/geometry) [geometry](https://github.com/geometry-zsh/geometry) - A minimal ZSH theme where any function can be added to the left prompt or (async) right prompt on the fly.
* <code>&nbsp;&nbsp;&nbsp;326</code> ![](https://img.shields.io/github/last-commit/lvv/git-prompt) [git-prompt](https://github.com/lvv/git-prompt) - Bash prompt with Git, SVN and HG modules
* <code>&nbsp;&nbsp;&nbsp;&nbsp;56</code> ![](https://img.shields.io/github/last-commit/momeni/gittify) [gittify](https://github.com/momeni/gittify) - A colorful Bash prompt + customized Git aliases
* <code>&nbsp;&nbsp;6783</code> ![](https://img.shields.io/github/last-commit/Mayccoll/Gogh) [Gogh - Color Scheme](https://github.com/Mayccoll/Gogh) - Color Scheme for Gnome Terminal
* <code>&nbsp;&nbsp;4158</code> ![](https://img.shields.io/github/last-commit/nojhan/liquidprompt) [liquidprompt](https://github.com/nojhan/liquidprompt) - A full-featured & carefully designed adaptive prompt for Bash & Zsh
* <code>&nbsp;&nbsp;&nbsp;&nbsp;88</code> ![](https://img.shields.io/github/last-commit/zpm-zsh/mysql-colorize) [mysql-colorize](https://github.com/zpm-zsh/mysql-colorize) -  Colorization for mysql comand-line client
* <code>&nbsp;&nbsp;3500</code> ![](https://img.shields.io/github/last-commit/arialdomartini/oh-my-git) [oh-my-git](https://github.com/arialdomartini/oh-my-git) - An opinionated git prompt for bash and zsh
* [oh-my-posh](https://ohmyposh.dev) - Prompt theme engine for any shell and platform written in go.
* <code>&nbsp;&nbsp;&nbsp;135</code> ![](https://img.shields.io/github/last-commit/agkozak/polyglot) [polyglot](https://github.com/agkozak/polyglot) - An informative Git prompt that works in bash, zsh, ksh, mksh, pdksh, dash, and busybox sh
* <code>&nbsp;27284</code> ![](https://img.shields.io/github/last-commit/romkatv/powerlevel10k) [powerlevel10k](https://github.com/romkatv/powerlevel10k) - Super flexible awesome powerline ZSH theme
* <code>&nbsp;&nbsp;1075</code> ![](https://img.shields.io/github/last-commit/twolfson/sexy-bash-prompt) [sexy-bash-prompt](https://github.com/twolfson/sexy-bash-prompt) - Bash prompt with colors, Git statuses, and Git branches
* [starship](https://starship.rs/) - Fast, customisable, cross-shell prompt written in rust
* <code>&nbsp;&nbsp;&nbsp;432</code> ![](https://img.shields.io/github/last-commit/andresgongora/synth-shell) [synth-shell](https://github.com/andresgongora/synth-shell) - Greeter with a customizable status report and a fancy bash prompt

## For Developers

*Command-line development, version control, and deployment.*

* [ack](https://beyondgrep.com/) - A grep-like search tool optimized for source code.
* <code>&nbsp;&nbsp;&nbsp;529</code> ![](https://img.shields.io/github/last-commit/TejasQ/add-gitignore) [add-gitignore](https://github.com/TejasQ/add-gitignore) - Interactive CLI that generates a .gitignore for your project based on your needs.
* <code>&nbsp;&nbsp;&nbsp;541</code> ![](https://img.shields.io/github/last-commit/jarun/bcal) [bcal](https://github.com/jarun/bcal) - Byte CALculator for storage conversions and calculations
* <code>&nbsp;&nbsp;&nbsp;448</code> ![](https://img.shields.io/github/last-commit/mellowcandle/bitwise) [bitwise](https://github.com/mellowcandle/bitwise) - Terminal based interactive bit manipulator in curses.
* <code>&nbsp;&nbsp;8606</code> ![](https://img.shields.io/github/last-commit/p8952/bocker) [bocker](https://github.com/p8952/bocker) - Docker implemented in 100 lines of bash
* <code>&nbsp;13880</code> ![](https://img.shields.io/github/last-commit/AlDanial/cloc) [cloc](https://github.com/AlDanial/cloc) - Count Lines of Code
* <code>&nbsp;&nbsp;&nbsp;&nbsp;43</code> ![](https://img.shields.io/github/last-commit/omgimanerd/doclt) [doclt](https://github.com/omgimanerd/doclt) - A command line interface to Digital Ocean
* <code>&nbsp;22637</code> ![](https://img.shields.io/github/last-commit/dokku/dokku) [dokku](https://github.com/dokku/dokku) - Docker powered mini-Heroku. The smallest PaaS implementation you've ever seen.
* <code>&nbsp;&nbsp;1968</code> ![](https://img.shields.io/github/last-commit/wfxr/forgit) [forgit](https://github.com/wfxr/forgit) - Utility tool for `git` taking advantage of fuzzy finder fzf.
* <code>&nbsp;&nbsp;&nbsp;752</code> ![](https://img.shields.io/github/last-commit/unixorn/git-extra-commands) [git-extra-commands](https://github.com/unixorn/git-extra-commands) - Many Git extra utilities. Churn, cut-branch, improved-merge and many more.
* <code>&nbsp;15531</code> ![](https://img.shields.io/github/last-commit/tj/git-extras) [git-extras](https://github.com/tj/git-extras) - Git utilities -- repo summary, repl, changelog population, author commit percentages and more
* <code>&nbsp;&nbsp;2765</code> ![](https://img.shields.io/github/last-commit/paulirish/git-open) [git-open](https://github.com/paulirish/git-open) - Type `git open` to open the GitHub page or website for a repository in your browser
* <code>&nbsp;&nbsp;5300</code> ![](https://img.shields.io/github/last-commit/arzzen/git-quick-stats) [git-quick-stats](https://github.com/arzzen/git-quick-stats) - Git quick statistics is a simple and efficient way to access various statistics in git repository.
* <code>&nbsp;&nbsp;&nbsp;340</code> ![](https://img.shields.io/github/last-commit/markchalloner/git-semver) [git-semver](https://github.com/markchalloner/git-semver) - Git plugin for easing semantic versioning and changelog validation
* <code>&nbsp;&nbsp;&nbsp;717</code> ![](https://img.shields.io/github/last-commit/rtomayko/git-sh) [git-sh](https://github.com/rtomayko/git-sh) - A customized Bash environment suitable for Git work
* <code>&nbsp;&nbsp;1116</code> ![](https://img.shields.io/github/last-commit/nosarthur/gita) [gita](https://github.com/nosarthur/gita) - A command-line tool to manage multiple git repos.
* <code>&nbsp;21690</code> ![](https://img.shields.io/github/last-commit/github/hub) [hub](https://github.com/github/hub) - hub helps you win at git.
* <code>&nbsp;&nbsp;5433</code> ![](https://img.shields.io/github/last-commit/casey/just) [just](https://github.com/casey/just) - Task runner for saving and running project-specific commands.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;18</code> ![](https://img.shields.io/github/last-commit/dogoncouch/licins) [licins](https://github.com/dogoncouch/licins) - Insert commented software licenses into source code.
* <code>&nbsp;&nbsp;&nbsp;282</code> ![](https://img.shields.io/github/last-commit/rosineygp/mkdkr) [mkdkr](https://github.com/rosineygp/mkdkr) - Makefile + Docker = CI Pipeline
* [mr](https://myrepos.branchable.com) - Multiple Repository management tool
* <code>&nbsp;&nbsp;3610</code> ![](https://img.shields.io/github/last-commit/sds/overcommit) [overcommit](https://github.com/sds/overcommit) - A fully configurable and extendable Git hook manager
* [pre-commit](https://pre-commit.com) - A framework for managing and maintaining multi-language pre-commit hooks
* <code>&nbsp;&nbsp;3834</code> ![](https://img.shields.io/github/last-commit/shobrook/rebound) [rebound](https://github.com/shobrook/rebound) - Instantly browse Stack Overflow results in your terminal when you get a compiler error
* <code>&nbsp;&nbsp;&nbsp;299</code> ![](https://img.shields.io/github/last-commit/jlevy/repren) [repren](https://github.com/jlevy/repren) - Command-line search-and-replace and file-renaming swiss army knife
* <code>&nbsp;&nbsp;6059</code> ![](https://img.shields.io/github/last-commit/slap-editor/slap) [slap](https://github.com/slap-editor/slap) - Sublime-like terminal-based text editor that runs on Node.js
* <code>&nbsp;&nbsp;&nbsp;555</code> ![](https://img.shields.io/github/last-commit/sapegin/shipit) [shipit](https://github.com/sapegin/shipit) - Minimalistic SSH deployment
* <code>&nbsp;&nbsp;&nbsp;155</code> ![](https://img.shields.io/github/last-commit/ritz078/starring) [starring](https://github.com/ritz078/starring) - Automatically star the npm-packages that you are using on GitHub.
* <code>&nbsp;&nbsp;&nbsp;579</code> ![](https://img.shields.io/github/last-commit/aykamko/tag) [tag](https://github.com/aykamko/tag) - Instantly jump to your ag matches.
* <code>&nbsp;&nbsp;&nbsp;317</code> ![](https://img.shields.io/github/last-commit/bntzio/wipe-modules) [wipe-modules](https://github.com/bntzio/wipe-modules) - A little agent that removes the node_modules folder of non-active projects

## System Utilities

*OS-related tools, including system administration, system debugging, and file and process management.*

* [atop](https://www.atoptool.nl) - ASCII full-screen performance monitor that is capable of reporting the activity of all processes
* <code>&nbsp;33741</code> ![](https://img.shields.io/github/last-commit/sharkdp/bat) [bat](https://github.com/sharkdp/bat) - A `cat` clone with wings
* <code>&nbsp;&nbsp;&nbsp;890</code> ![](https://img.shields.io/github/last-commit/tgraf/bmon) [bmon](https://github.com/tgraf/bmon) - Real-time network bandwidth monitor and rate estimator with human-friendly visual output
* <code>&nbsp;&nbsp;8454</code> ![](https://img.shields.io/github/last-commit/aristocratos/bpytop) [bpytop](https://github.com/aristocratos/bpytop) - Linux/OSX/FreeBSD resource monitor
* <code>&nbsp;&nbsp;&nbsp;114</code> ![](https://img.shields.io/github/last-commit/deadc0de6/catcli) [catcli](https://github.com/deadc0de6/catcli) -  The command line catalog tool for your offline data
* <code>&nbsp;&nbsp;2954</code> ![](https://img.shields.io/github/last-commit/owenthereal/ccat) [ccat](https://github.com/owenthereal/ccat) - ccat is the colorizing cat. It works similar to cat but displays content with syntax highlighting.
* <code>&nbsp;17387</code> ![](https://img.shields.io/github/last-commit/ogham/exa) [exa](https://github.com/ogham/exa) - A modern version of `ls`.
* <code>&nbsp;&nbsp;5693</code> ![](https://img.shields.io/github/last-commit/Xfennec/progress) [progress](https://github.com/Xfennec/progress) - Linux tool to show progress for `cp`, `rm`, `dd`, and more...
* <code>&nbsp;&nbsp;&nbsp;925</code> ![](https://img.shields.io/github/last-commit/alichtman/stronghold) [stronghold](https://github.com/alichtman/stronghold) - Easily configure MacOS security settings from the terminal.
* <code>&nbsp;20296</code> ![](https://img.shields.io/github/last-commit/nicolargo/glances) [glances](https://github.com/nicolargo/glances) - Glances an Eye on your system
* <code>&nbsp;14594</code> ![](https://img.shields.io/github/last-commit/allinurl/goaccess) [goaccess](https://github.com/allinurl/goaccess) - GoAccess is a real-time web log analyzer and interactive viewer that runs in a terminal in \*nix systems.
* <code>&nbsp;&nbsp;&nbsp;958</code> ![](https://img.shields.io/github/last-commit/hectorm/hblock) [hblock](https://github.com/hectorm/hblock) - Hosts-file based adblocker
* <code>&nbsp;&nbsp;&nbsp;&nbsp;85</code> ![](https://img.shields.io/github/last-commit/vesche/histstat) [histstat](https://github.com/vesche/histstat) - History for netstat
* <code>&nbsp;&nbsp;5670</code> ![](https://img.shields.io/github/last-commit/hishamhm/htop) [htop](https://github.com/hishamhm/htop) - A ncurses based interactive process viewer which aims to be a better `top`
* [lnav](https://lnav.org) - An advanced log file viewer for the small-scale
* <code>&nbsp;&nbsp;&nbsp;115</code> ![](https://img.shields.io/github/last-commit/dogoncouch/logdissect) [logdissect](https://github.com/dogoncouch/logdissect) - CLI utility and Python API for analyzing log files and other data.
* <code>&nbsp;&nbsp;&nbsp;479</code> ![](https://img.shields.io/github/last-commit/trapd00r/ls--) [ls++](https://github.com/trapd00r/ls--) - Colorized ls on steroids
* <code>&nbsp;&nbsp;&nbsp;507</code> ![](https://img.shields.io/github/last-commit/dborzov/lsp) [lsp](https://github.com/dborzov/lsp) - An improved `ls`, with file descriptions in plain language and intelligent file grouping
* <code>&nbsp;&nbsp;1573</code> ![](https://img.shields.io/github/last-commit/tanrax/maza-ad-blocking) [maza](https://github.com/tanrax/maza-ad-blocking) - Local ad blocker. Like Pi-hole but local and using your operating system.
* <code>&nbsp;&nbsp;1954</code> ![](https://img.shields.io/github/last-commit/traviscross/mtr) [mtr](https://github.com/traviscross/mtr) - The functionality of the 'traceroute' and 'ping' programs in a single network diagnostic tool.
* [ncdu](https://dev.yorhel.nl/ncdu) - NCurses Disk Usage
* <code>&nbsp;&nbsp;&nbsp;237</code> ![](https://img.shields.io/github/last-commit/NetworkManager/NetworkManager) [nmtui](https://github.com/NetworkManager/NetworkManager) - Text User Interface for controlling NetworkManager
* <code>&nbsp;&nbsp;&nbsp;601</code> ![](https://img.shields.io/github/last-commit/fenrus75/powertop) [powertop](https://github.com/fenrus75/powertop) - Battery/Power usage and device stats monitoring command-line tool, with tune-up options.
* <code>&nbsp;&nbsp;1020</code> ![](https://img.shields.io/github/last-commit/denilsonsa/prettyping) [prettyping](https://github.com/denilsonsa/prettyping) - Making the output of `ping` prettier, more colorful, more compact, and easier to read.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;71</code> ![](https://img.shields.io/github/last-commit/jlevy/procdog) [procdog](https://github.com/jlevy/procdog) - Lightweight command-line control of long-lived processes like servers
* <code>&nbsp;&nbsp;&nbsp;390</code> ![](https://img.shields.io/github/last-commit/marshyski/quick-secure) [quick-secure](https://github.com/marshyski/quick-secure) - Quickly secure and harden UNIX/Linux systems
* <code>&nbsp;&nbsp;&nbsp;&nbsp;24</code> ![](https://img.shields.io/github/last-commit/nickolasburr/rng) [rng](https://github.com/nickolasburr/rng) - Copy range of lines from file or stdin to stdout.
* <code>&nbsp;&nbsp;&nbsp;951</code> ![](https://img.shields.io/github/last-commit/nschloe/tiptop) [tiptop](https://github.com/nschloe/tiptop) - Graphical command-line system monitor.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;59</code> ![](https://img.shields.io/github/last-commit/keithrbennett/wifiwand) [wifi-wand](https://github.com/keithrbennett/wifiwand) - a Ruby command line application for managing WiFi on MacOS (install by `gem install wifi-wand`)
* <code>&nbsp;&nbsp;1019</code> ![](https://img.shields.io/github/last-commit/ivanilves/xiringuito) [xiringuito](https://github.com/ivanilves/xiringuito) - SSH-based "VPN for poors"

## Downloading and Serving

*Self-hosted, lightweight servers and networking tools written in shell scripts.*

* <code>&nbsp;26124</code> ![](https://img.shields.io/github/last-commit/aria2/aria2) [aria2](https://github.com/aria2/aria2) - aria2 is a lightweight multi-protocol & multi-source, cross platform download utility operated in command-line. It supports HTTP/HTTPS, FTP, BitTorrent and Metalink
* <code>&nbsp;&nbsp;&nbsp;823</code> ![](https://img.shields.io/github/last-commit/jneen/balls) [balls](https://github.com/jneen/balls) - Bash on Balls
* <code>&nbsp;&nbsp;1386</code> ![](https://img.shields.io/github/last-commit/avleen/bashttpd) [bashttpd](https://github.com/avleen/bashttpd) - A web server written in Bash
* <code>&nbsp;&nbsp;&nbsp;223</code> ![](https://img.shields.io/github/last-commit/nicksherron/bashhub-server) [bashhub-server](https://github.com/nicksherron/bashhub-server) - Private cloud shell history. Open source server for bashhub
* <code>&nbsp;&nbsp;1006</code> ![](https://img.shields.io/github/last-commit/sickill/bitpocket) [bitpocket](https://github.com/sickill/bitpocket) - "DIY Dropbox" or "2-way directory (r)sync with proper deletion"
* <code>&nbsp;&nbsp;6387</code> ![](https://img.shields.io/github/last-commit/andreafabrizi/Dropbox-Uploader) [Dropbox-Uploader](https://github.com/andreafabrizi/Dropbox-Uploader) - Dropbox Uploader is a Bash script which can be used to upload, download, list or delete files from Dropbox
* <code>&nbsp;13920</code> ![](https://img.shields.io/github/last-commit/httpie/httpie) [httpie](https://github.com/httpie/httpie) - HTTPie is a command line HTTP client, a user-friendly cURL replacement
* <code>&nbsp;&nbsp;3796</code> ![](https://img.shields.io/github/last-commit/gchaincl/httplab) [HTTPLab](https://github.com/gchaincl/httplab) - The interactive web server, let you inspect HTTP requests and forge responses.
* <code>&nbsp;&nbsp;&nbsp;162</code> ![](https://img.shields.io/github/last-commit/jaburns/ngincat) [ngincat](https://github.com/jaburns/ngincat) - Tiny Bash HTTP server using netcat
* <code>&nbsp;&nbsp;2607</code> ![](https://img.shields.io/github/last-commit/micha/resty) [resty](https://github.com/micha/resty) - Little command line REST client that you can use in pipelines
* <code>&nbsp;&nbsp;&nbsp;915</code> ![](https://img.shields.io/github/last-commit/msoap/shell2http) [shell2http](https://github.com/msoap/shell2http) - HTTP-server to execute shell commands. Designed for development, prototyping or remote control
* <code>&nbsp;&nbsp;&nbsp;187</code> ![](https://img.shields.io/github/last-commit/chris-rock/vesper) [vesper](https://github.com/chris-rock/vesper) - 🍸Vesper is a HTTP framework for Bash/Unix Shell
* <code>&nbsp;&nbsp;2778</code> ![](https://img.shields.io/github/last-commit/ducaale/xh) [xh](https://github.com/ducaale/xh) - Friendly and fast tool for sending HTTP requests
* [youtube-dl](https://yt-dl.org/) - Small command-line program to download videos from YouTube.com and other video sites

## Multimedia and File Formats

*Tools for handling video and audio files.*

* <code>&nbsp;&nbsp;&nbsp;&nbsp;87</code> ![](https://img.shields.io/github/last-commit/sromku/adb-export) [adb-export](https://github.com/sromku/adb-export) - Export Android content providers to CSV format
* <code>&nbsp;&nbsp;&nbsp;952</code> ![](https://img.shields.io/github/last-commit/dsixda/Android-Kitchen) [Android-Kitchen](https://github.com/dsixda/Android-Kitchen) - A text-based kitchen for Android ROM customization. Uses shell scripts and works with Cygwin/OS X/Linux
* <code>&nbsp;10836</code> ![](https://img.shields.io/github/last-commit/beetbox/beets) [Beets](https://github.com/beetbox/beets) - Music library manager and MusicBrainz tagger
* <code>&nbsp;&nbsp;4588</code> ![](https://img.shields.io/github/last-commit/cmus/cmus) [cmus](https://github.com/cmus/cmus) - Cross-platform cli audio player.
* <code>&nbsp;&nbsp;3021</code> ![](https://img.shields.io/github/last-commit/tomwright/dasel) [dasel](https://github.com/tomwright/dasel) - Query and update data structures using selectors from the command line. Comparable to <code>&nbsp;21819</code> ![](https://img.shields.io/github/last-commit/stedolan/jq) [jq](https://github.com/stedolan/jq) / <code>&nbsp;&nbsp;1835</code> ![](https://img.shields.io/github/last-commit/kislyuk/yq) [yq](https://github.com/kislyuk/yq) but supports JSON, YAML, TOML and XML with zero runtime dependencies.
* <code>&nbsp;13395</code> ![](https://img.shields.io/github/last-commit/antonmedv/fx) [fx](https://github.com/antonmedv/fx) - Command-line JSON processing tool by anononymus JavaScript functions
* <code>&nbsp;&nbsp;&nbsp;438</code> ![](https://img.shields.io/github/last-commit/lukechilds/gifgen) [gifgen](https://github.com/lukechilds/gifgen) - Simple high quality GIF encoding
* <code>&nbsp;&nbsp;&nbsp;689</code> ![](https://img.shields.io/github/last-commit/sananth12/ImageScraper) [image-scraper](https://github.com/sananth12/ImageScraper) - A cool command line image scraper with a lot of features.
* <code>&nbsp;&nbsp;&nbsp;871</code> ![](https://img.shields.io/github/last-commit/jarun/imgp) [imgp](https://github.com/jarun/imgp) - Blazing fast batch image resizer and rotator
* <code>&nbsp;&nbsp;4091</code> ![](https://img.shields.io/github/last-commit/jpmens/jo) [jo](https://github.com/jpmens/jo) - A small utility to create JSON objects from command-line arguments.
* <code>&nbsp;21819</code> ![](https://img.shields.io/github/last-commit/stedolan/jq) [jq](https://github.com/stedolan/jq) - Sed for json data. You can use it to slice and filter and map and transform structured data
* <code>&nbsp;&nbsp;&nbsp;342</code> ![](https://img.shields.io/github/last-commit/oguzhaninan/korkut) [korkut](https://github.com/oguzhaninan/korkut) - Quick and simple image processing at the command line.
* [mpv](https://mpv.io/) - Lets you play most audio and video formats (using ASCII characters) in the shell as well as in a GUI.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;83</code> ![](https://img.shields.io/github/last-commit/bogem/nehm) [nehm](https://github.com/bogem/nehm) - Console tool, which downloads, sets IDv3 tags and adds to your iTunes (if you use it) your SoundCloud likes in convenient way
* <code>&nbsp;&nbsp;1716</code> ![](https://img.shields.io/github/last-commit/lanceseidman/PiCAST) [PiCAST](https://github.com/lanceseidman/PiCAST) - PiCAST turns your $35 Raspberry Pi in to a Chromecast like Device
* <code>&nbsp;&nbsp;&nbsp;390</code> ![](https://img.shields.io/github/last-commit/torakiki/sejda) [sejda](https://github.com/torakiki/sejda/) - Command line manipulation of PDF documents (split, merge, rotate, convert to jpg, extract text, etc)
* <code>&nbsp;&nbsp;5319</code> ![](https://img.shields.io/github/last-commit/saulpw/visidata) [visidata](https://github.com/saulpw/visidata) - A terminal spreadsheet multitool for exploring and arranging data (csv/json/xml/xls/yaml/etc)
* <code>&nbsp;&nbsp;&nbsp;462</code> ![](https://img.shields.io/github/last-commit/benibela/xidel) [xidel](https://github.com/benibela/xidel/) - Cli tool to filter, map and create HTML/XML/JSON data with (Turing-complete) XPath and XQuery.
* [xmlstarlet](http://xmlstar.sourceforge.net/) - Old but powerful tool for command-line XML formatting, filtering, and manipulation.
* <code>&nbsp;&nbsp;5452</code> ![](https://img.shields.io/github/last-commit/mikefarah/yq) [yq](https://github.com/mikefarah/yq) - yq is a portable command-line YAML processor

## Applications

*Command line-based applications or command line access to existing services.*

* <code>&nbsp;&nbsp;1693</code> ![](https://img.shields.io/github/last-commit/fcambus/ansiweather) [ansiweather](https://github.com/fcambus/ansiweather) - Weather in your terminal, with ANSI colors and Unicode symbols
* <code>&nbsp;&nbsp;4833</code> ![](https://img.shields.io/github/last-commit/wallix/awless) [awless](https://github.com/wallix/awless) - A powerful, innovative and small surface CLI to manage AWS.
* <code>&nbsp;&nbsp;1316</code> ![](https://img.shields.io/github/last-commit/cfenollosa/bashblog) [bashblog](https://github.com/cfenollosa/bashblog) - A Bash script that handles blog posting
* <code>&nbsp;&nbsp;5262</code> ![](https://img.shields.io/github/last-commit/mixn/carbon-now-cli) [carbon-now-cli](https://github.com/mixn/carbon-now-cli) - 🎨 Beautiful images of your code — from right inside your terminal.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;62</code> ![](https://img.shields.io/github/last-commit/lord63/choosealicense-cli) [choosealicense-cli](https://github.com/lord63/choosealicense-cli) - Choose an OSS license from the comfort of your terminal
* <code>&nbsp;&nbsp;3141</code> ![](https://img.shields.io/github/last-commit/miguelmota/cointop) [cointop](https://github.com/miguelmota/cointop) - The fastest and most interactive terminal based UI application for tracking cryptocurrencies
* <code>&nbsp;&nbsp;&nbsp;566</code> ![](https://img.shields.io/github/last-commit/naggie/dstask) [dstask](https://github.com/naggie/dstask) - Single binary terminal-based TODO manager with git-based sync + markdown notes per task
* <code>&nbsp;&nbsp;3331</code> ![](https://img.shields.io/github/last-commit/mifi/editly) [editly](https://github.com/mifi/editly) - Command line video editor
* <code>&nbsp;&nbsp;&nbsp;366</code> ![](https://img.shields.io/github/last-commit/specious/facebook-cli) [facebook-cli](https://github.com/specious/facebook-cli) - Facebook command line tool
* <code>&nbsp;&nbsp;1145</code> ![](https://img.shields.io/github/last-commit/afc163/fanyi) [fanyi](https://github.com/afc163/fanyi) - Translate English to Chinese in terminal
* <code>&nbsp;&nbsp;2755</code> ![](https://img.shields.io/github/last-commit/insanum/gcalcli) [gcalcli](https://github.com/insanum/gcalcli) - Google Calendar command line interface
* <code>&nbsp;&nbsp;2097</code> ![](https://img.shields.io/github/last-commit/VitaliyRodnenko/geeknote) [geeknote](https://github.com/VitaliyRodnenko/geeknote) - Command line evernote client
* <code>&nbsp;&nbsp;3716</code> ![](https://img.shields.io/github/last-commit/donnemartin/haxor-news) [haxor-news](https://github.com/donnemartin/haxor-news) - Browse Hacker News like a haxor
* <code>&nbsp;&nbsp;&nbsp;453</code> ![](https://img.shields.io/github/last-commit/rafaelrinaldi/hn-cli) [hn-cli](https://github.com/rafaelrinaldi/hn-cli) - Browse Hacker News from the comfort of your Terminal
* <code>&nbsp;&nbsp;&nbsp;274</code> ![](https://img.shields.io/github/last-commit/nogizhopaboroda/iponmap) [iponmap](https://github.com/nogizhopaboroda/iponmap) - Draw point on world map using ip address
* <code>&nbsp;&nbsp;&nbsp;&nbsp;51</code> ![](https://img.shields.io/github/last-commit/lord63/isitup) [isitup](https://github.com/lord63/isitup) - Check whether a website is up or down
* <code>&nbsp;&nbsp;5349</code> ![](https://img.shields.io/github/last-commit/jrnl-org/jrnl) [jrnl](https://github.com/jrnl-org/jrnl) - A simple command line journal application that stores your journal in a plain text file
* <code>&nbsp;&nbsp;&nbsp;369</code> ![](https://img.shields.io/github/last-commit/coderofsalvation/kanban.bash) [kanban.bash](https://github.com/coderofsalvation/kanban.bash) - commandline asciii kanban board for minimalist productivity bash hackers (csv-based)
* <code>&nbsp;&nbsp;4208</code> ![](https://img.shields.io/github/last-commit/ledger/ledger) [ledger](https://github.com/ledger/ledger) - Command line accounting
* <code>&nbsp;&nbsp;&nbsp;&nbsp;33</code> ![](https://img.shields.io/github/last-commit/lord63/licen) [licen](https://github.com/lord63/licen) - Generate your license. Yet another lice, but implement with Jinja2 and docopt
* <code>&nbsp;&nbsp;&nbsp;&nbsp;22</code> ![](https://img.shields.io/github/last-commit/weaming/md2png) [md2png](https://github.com/weaming/md2png) - Convert markdown to PNG image
* <code>&nbsp;&nbsp;&nbsp;182</code> ![](https://img.shields.io/github/last-commit/iCHAIT/moviemon) [moviemon](https://github.com/iCHAIT/moviemon) - Everything about your movies within the command line.
* <code>&nbsp;&nbsp;&nbsp;384</code> ![](https://img.shields.io/github/last-commit/yaa110/nomino) [nomino](https://github.com/yaa110/nomino) - Batch rename utility using regex, sort and map file options.
* <code>&nbsp;&nbsp;&nbsp;163</code> ![](https://img.shields.io/github/last-commit/alt-romes/programmer-calculator) [pcalc](https://github.com/alt-romes/programmer-calculator) - Calculator made for programmers working with multiple number representations, sizes, and overall close to the bits.
* <code>&nbsp;&nbsp;&nbsp;461</code> ![](https://img.shields.io/github/last-commit/achembarpu/pockyt) [pockyt](https://github.com/achembarpu/pockyt) - Read, Manage, and Automate your [Pocket](https://getpocket.com) collection.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;93</code> ![](https://img.shields.io/github/last-commit/alebcay/pushblast) [pushblast](https://github.com/alebcay/pushblast) - Get PushBullet notifications when a shell program exits
* <code>&nbsp;&nbsp;&nbsp;226</code> ![](https://img.shields.io/github/last-commit/Red5d/pushbullet-bash) [pushbullet-bash](https://github.com/Red5d/pushbullet-bash) - Bash interface to the PushBullet API
* <code>&nbsp;11367</code> ![](https://img.shields.io/github/last-commit/ranger/ranger) [ranger](https://github.com/ranger/ranger) - A console file manager with VI key bindings.
* <code>&nbsp;&nbsp;4573</code> ![](https://img.shields.io/github/last-commit/michael-lazar/rtv) [Reddit Terminal Viewer](https://github.com/michael-lazar/rtv) - Browse Reddit from your terminal
* <code>&nbsp;&nbsp;4934</code> ![](https://img.shields.io/github/last-commit/donnemartin/saws) [SAWS](https://github.com/donnemartin/saws) - A Supercharged AWS CLI
* <code>&nbsp;&nbsp;8407</code> ![](https://img.shields.io/github/last-commit/klaussinani/taskbook) [taskbook](https://github.com/klaussinani/taskbook) - Tasks, boards & notes for the command-line habitat
* [taskwarrior](https://taskwarrior.org/) - A command-line TODO list manager
* <code>&nbsp;&nbsp;&nbsp;779</code> ![](https://img.shields.io/github/last-commit/keepcosmos/terjira) [terjira](https://github.com/keepcosmos/terjira) - Command line power tool for Jira
* <code>&nbsp;&nbsp;4203</code> ![](https://img.shields.io/github/last-commit/achannarasappa/ticker) [ticker](https://github.com/achannarasappa/ticker) — Terminal stock ticker with live updates and position tracking
* [transfer.sh](https://transfer.sh/) — Quickly upload and share files from your shell
* <code>&nbsp;&nbsp;&nbsp;&nbsp;14</code> ![](https://img.shields.io/github/last-commit/ellisonleao/vl) [vl](https://github.com/ellisonleao/vl) - URL link checker on text documents
* <code>&nbsp;&nbsp;7026</code> ![](https://img.shields.io/github/last-commit/schachmat/wego) [wego](https://github.com/schachmat/wego) - Weather app for the terminal
* <code>&nbsp;&nbsp;&nbsp;335</code> ![](https://img.shields.io/github/last-commit/Gueils/whales) [whales](https://github.com/Gueils/whales) - A tool to automatically dockerize your applications
* <code>&nbsp;&nbsp;&nbsp;149</code> ![](https://img.shields.io/github/last-commit/rafaelrinaldi/whereami) [whereami](https://github.com/rafaelrinaldi/whereami) - Get your geolocation information from the CLI
* <code>&nbsp;17496</code> ![](https://img.shields.io/github/last-commit/chubin/wttr.in) [wttr.in](https://github.com/chubin/wttr.in) - :partly_sunny: The right way to check the weather (curl wttr.in)

## Games

*All work and no play is a cruddy way to spend your day.*

* <code>&nbsp;&nbsp;&nbsp;830</code> ![](https://img.shields.io/github/last-commit/mydzor/bash2048) [bash2048](https://github.com/mydzor/bash2048) - Bash implementation of 2048 game
* <code>&nbsp;&nbsp;&nbsp;&nbsp;45</code> ![](https://img.shields.io/github/last-commit/feherke/Bash-script) [minesweeper](https://github.com/feherke/Bash-script/tree/master/minesweeper) - Bash implementation of minesweeper
* <code>&nbsp;&nbsp;&nbsp;229</code> ![](https://img.shields.io/github/last-commit/jubalh/nudoku) [nudoku](https://github.com/jubalh/nudoku) - ncurses based sudoku game written in C
* <code>&nbsp;&nbsp;&nbsp;674</code> ![](https://img.shields.io/github/last-commit/vaniacer/piu-piu-SH) [piu-piu](https://github.com/vaniacer/piu-piu-SH) - Horizontal scroller game in bash with multiplayer mode!
* <code>&nbsp;&nbsp;&nbsp;426</code> ![](https://img.shields.io/github/last-commit/uuner/sedtris) [sedtris](https://github.com/uuner/sedtris) - Tetris in sed
* <code>&nbsp;&nbsp;&nbsp;&nbsp;38</code> ![](https://img.shields.io/github/last-commit/aureliojargas/sed-scripts) [sed-scripts](https://github.com/aureliojargas/sed-scripts) - Arkanoid and Sokoban written using sed
* [SHTAP](https://notimetoplay.org/engines/shtap/) - Reusable text adventure engine for Bash 4
* <code>&nbsp;&nbsp;&nbsp;218</code> ![](https://img.shields.io/github/last-commit/mpereira/tty-solitaire) [tty-solitaire](https://github.com/mpereira/tty-solitaire) - Play solitaire in your terminal!

## Shell Package Management

*Tools for managing multiple shell configurations. For zsh-specific tools, see the Zsh section.*

* <code>&nbsp;12899</code> ![](https://img.shields.io/github/last-commit/Bash-it/bash-it) [bash-it](https://github.com/Bash-it/bash-it) - A community Bash framework
* <code>&nbsp;&nbsp;&nbsp;909</code> ![](https://img.shields.io/github/last-commit/basherpm/basher) [basher](https://github.com/basherpm/basher) - A package manager for shell scripts
* <code>&nbsp;&nbsp;&nbsp;&nbsp;61</code> ![](https://img.shields.io/github/last-commit/xsc/bashing) [bashing](https://github.com/xsc/bashing) - Smashing Bash into Pieces
* [bpkg](https://www.bpkg.sh/) - JavaScript has npm, Ruby has Gems, Python has pip and now Shell has bpkg
* <code>&nbsp;&nbsp;1088</code> ![](https://img.shields.io/github/last-commit/deadc0de6/dotdrop) [dotdrop](https://github.com/deadc0de6/dotdrop) - Save your dotfiles once, deploy them everywhere
* <code>&nbsp;&nbsp;&nbsp;225</code> ![](https://img.shields.io/github/last-commit/svetlyak40wt/dotfiler) [dotfiler](https://github.com/svetlyak40wt/dotfiler) – Shell agnostic git based dotfiles package manager, written in Python.
* <code>&nbsp;&nbsp;1085</code> ![](https://img.shields.io/github/last-commit/freshshell/fresh) [fresh](https://github.com/freshshell/fresh) - Keep your dotfiles fresh
* <code>&nbsp;&nbsp;1831</code> ![](https://img.shields.io/github/last-commit/andsens/homeshick) [homeshick](https://github.com/andsens/homeshick) - Git dotfile synchronizer written in Bash
* <code>&nbsp;&nbsp;&nbsp;883</code> ![](https://img.shields.io/github/last-commit/alichtman/shallow-backup) [shallow-backup](https://github.com/alichtman/shallow-backup) - Easily create lightweight documentation of installed packages, dotfiles, and more
* <code>&nbsp;&nbsp;&nbsp;&nbsp;78</code> ![](https://img.shields.io/github/last-commit/javier-lopez/shundle) [shundle](https://github.com/javier-lopez/shundle) - Plugin manager for shell scripts
* <code>&nbsp;&nbsp;1950</code> ![](https://img.shields.io/github/last-commit/RichiH/vcsh) [vcsh](https://github.com/RichiH/vcsh) - Config manager based on Git
* [yadm](https://yadm.io/) - Git-based dotfiles manager supporting encryption, alternates, and bootstrapping

## Shell Script Development

*Tools for writing, improving, or organizing Bash or other shell scripts*

* <code>&nbsp;&nbsp;&nbsp;393</code> ![](https://img.shields.io/github/last-commit/fidian/ansi) [ansi](https://github.com/fidian/ansi) - ANSI escape codes in pure bash - change text color, position the cursor, much more
* <code>&nbsp;&nbsp;&nbsp;455</code> ![](https://img.shields.io/github/last-commit/lehmannro/assert.sh) [assert.sh](https://github.com/lehmannro/assert.sh) - Bash unit testing framework
* <code>&nbsp;&nbsp;&nbsp;125</code> ![](https://img.shields.io/github/last-commit/pforret/bashew) [bashew](https://github.com/pforret/bashew) - bash script creator - from small stand-alone script to complex projects with CI/CD and testing
* <code>&nbsp;&nbsp;&nbsp;550</code> ![](https://img.shields.io/github/last-commit/jmcantrell/bashful) [bashful](https://github.com/jmcantrell/bashful) - A collection of libraries to simplify writing Bash scripts
* <code>&nbsp;&nbsp;&nbsp;&nbsp;66</code> ![](https://img.shields.io/github/last-commit/reale/bashlets) [Bashlets](https://github.com/reale/bashlets) - A modular extensible toolbox for Bash
* [bashly](https://bashly.dannyb.co/) - Bash command line framework and CLI generator
* <code>&nbsp;&nbsp;&nbsp;&nbsp;83</code> ![](https://img.shields.io/github/last-commit/lingtalfi/bashmanager) [bashmanager](https://github.com/lingtalfi/bashmanager) - mini bash framework for creating command line tools
* <code>&nbsp;&nbsp;&nbsp;&nbsp;26</code> ![](https://img.shields.io/github/last-commit/mindaugasbarysas/bashwithnails) [bashwithnails](https://github.com/mindaugasbarysas/bashwithnails) - a Bash framework written just for fun with testing, dependency management & packaging
* <code>&nbsp;&nbsp;1234</code> ![](https://img.shields.io/github/last-commit/bash-lsp/bash-language-server) [bash-language-server](https://github.com/bash-lsp/bash-language-server) - [LSP](https://microsoft.github.io/language-server-protocol/)-based Bash language server
* <code>&nbsp;&nbsp;&nbsp;&nbsp;88</code> ![](https://img.shields.io/github/last-commit/vlisivka/bash-modules) [bash-modules](https://github.com/vlisivka/bash-modules) - functions for developing with [unofficial strict mode](http://redsymbol.net/articles/unofficial-bash-strict-mode/) enabled.
* <code>&nbsp;&nbsp;3091</code> ![](https://img.shields.io/github/last-commit/bats-core/bats-core) [bats](https://github.com/bats-core/bats-core) - Bash Automated Testing System
* <code>&nbsp;&nbsp;&nbsp;300</code> ![](https://img.shields.io/github/last-commit/erichs/composure) [composure](https://github.com/erichs/composure) - Compose, document, version and organize your shell functions
* <code>&nbsp;&nbsp;&nbsp;&nbsp;51</code> ![](https://img.shields.io/github/last-commit/molovo/crash) [crash](https://github.com/molovo/crash) - Proper error handling, exceptions and try/catch for ZSH
* <code>&nbsp;&nbsp;&nbsp;445</code> ![](https://img.shields.io/github/last-commit/Checksum/critic.sh) [critic.sh](https://github.com/Checksum/critic.sh) - Dead simple testing framework for Bash with coverage reporting
* <code>&nbsp;&nbsp;&nbsp;&nbsp;88</code> ![](https://img.shields.io/github/last-commit/Mosai/workshop) [dispatch](https://github.com/Mosai/workshop/blob/master/doc/dispatch.md) - A command line argument parser in 50 lines of portable shell script.
* <code>&nbsp;&nbsp;&nbsp;147</code> ![](https://img.shields.io/github/last-commit/jirutka/esh) [esh](https://github.com/jirutka/esh) - A simple templating engine based on shell, implemented in ~290 lines of POSIX shell and awk.
* <code>&nbsp;&nbsp;&nbsp;297</code> ![](https://img.shields.io/github/last-commit/jorgebucaran/fishtape) [Fishtape](https://github.com/jorgebucaran/fishtape) - TAP producer and test harness for fish
* <code>&nbsp;&nbsp;&nbsp;200</code> ![](https://img.shields.io/github/last-commit/ko1nksm/getoptions) [getoptions](https://github.com/ko1nksm/getoptions) - An elegant option parser for shell scripts (sh, bash and all POSIX shells)
* <code>&nbsp;&nbsp;&nbsp;189</code> ![](https://img.shields.io/github/last-commit/jorgebucaran/getopts.fish) [getopts.fish](https://github.com/jorgebucaran/getopts.fish) - CLI parser for fish
* <code>&nbsp;&nbsp;&nbsp;143</code> ![](https://img.shields.io/github/last-commit/qzb/is.sh) [is.sh](https://github.com/qzb/is.sh) - An alternative for builtin test command, it will make your "if" statements pretty
* <code>&nbsp;&nbsp;&nbsp;&nbsp;36</code> ![](https://img.shields.io/github/last-commit/molovo/lumberjack) [lumberjack](https://github.com/molovo/lumberjack) - A logging interface for shell scripts
* <code>&nbsp;&nbsp;&nbsp;436</code> ![](https://img.shields.io/github/last-commit/tests-always-included/mo) [mo](https://github.com/tests-always-included/mo) - Mustache templates in pure bash
* <code>&nbsp;&nbsp;&nbsp;138</code> ![](https://img.shields.io/github/last-commit/nk412/optparse) [optparse](https://github.com/nk412/optparse) - A BASH wrapper for getopts, for simple command line arguments.
* <code>&nbsp;&nbsp;&nbsp;421</code> ![](https://img.shields.io/github/last-commit/rerun/rerun) [rerun](https://github.com/rerun/rerun) - A modular shell automation framework to organize your keeper scripts
* <code>&nbsp;&nbsp;&nbsp;124</code> ![](https://img.shields.io/github/last-commit/molovo/revolver) [revolver](https://github.com/molovo/revolver) - A reusable progress spinner for shell scripts
* <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> ![](https://img.shields.io/github/last-commit/sorokine/phases) [phases](https://github.com/sorokine/phases) - Minimally invasive bash preprocessor, select sections of your script to run
* <code>&nbsp;&nbsp;&nbsp;113</code> ![](https://img.shields.io/github/last-commit/coderofsalvation/powscript) [powscript](https://github.com/coderofsalvation/powscript) - bash transpiler written in bash (coffeescript for bash)
* <code>&nbsp;&nbsp;&nbsp;220</code> ![](https://img.shields.io/github/last-commit/cloudflare/semver_bash) [semver_bash](https://github.com/cloudflare/semver_bash) - Semantic Versioning in Bash
* <code>&nbsp;&nbsp;&nbsp;&nbsp;28</code> ![](https://img.shields.io/github/last-commit/qzb/sh-semver) [sh-semver](https://github.com/qzb/sh-semver) - Semver tool for bash - finds versions matching to specified rules
* <code>&nbsp;28457</code> ![](https://img.shields.io/github/last-commit/koalaman/shellcheck) [shellcheck](https://github.com/koalaman/shellcheck) - Static analysis tool for shell scripts
* <code>&nbsp;&nbsp;1168</code> ![](https://img.shields.io/github/last-commit/shellfire-dev/shellfire) [shellfire](https://github.com/shellfire-dev/shellfire) -  A repository of namespaced, composable shell (bash, sh and dash) function libraries
* <code>&nbsp;&nbsp;&nbsp;642</code> ![](https://img.shields.io/github/last-commit/shellspec/shellspec) [shellspec](https://github.com/shellspec/shellspec) - A full-featured BDD unit testing framework for dash, bash, ksh, zsh and all POSIX shells
* <code>&nbsp;&nbsp;4662</code> ![](https://img.shields.io/github/last-commit/mvdan/sh) [shfmt](https://github.com/mvdan/sh) - A shell parser, formatter, and interpreter with bash support; includes shfmt
* <code>&nbsp;&nbsp;&nbsp;363</code> ![](https://img.shields.io/github/last-commit/rylnd/shpec) [shpec](https://github.com/rylnd/shpec) - A shell testing framework
* [shutit](https://ianmiell.github.io/shutit/) - Automation framework based on bash and pexpect
* <code>&nbsp;&nbsp;1666</code> ![](https://img.shields.io/github/last-commit/basecamp/sub) [sub](https://github.com/basecamp/sub) - A delicious way to organize programs
* <code>&nbsp;&nbsp;&nbsp;&nbsp;50</code> ![](https://img.shields.io/github/last-commit/thinkerbot/ts) [ts](https://github.com/thinkerbot/ts) - A shell test script
* <code>&nbsp;&nbsp;&nbsp;203</code> ![](https://img.shields.io/github/last-commit/tlevine/urchin) [urchin](https://github.com/tlevine/urchin) - An idiomatic shell testing framework that uses only shell commands
* <code>&nbsp;&nbsp;1295</code> ![](https://img.shields.io/github/last-commit/kward/shunit2) [shunit2](https://github.com/kward/shunit2) - A unit test framework for Bash scripts with a flavour of JUnit/PyUnit.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;60</code> ![](https://img.shields.io/github/last-commit/jandob/rebash) [rebash](https://github.com/jandob/rebash) - Scripting library/framework. Features: imports, exceptions, doc-tests ...
* <code>&nbsp;&nbsp;&nbsp;162</code> ![](https://img.shields.io/github/last-commit/zunit-zsh/zunit) [zunit](https://github.com/zunit-zsh/zunit) - A powerful unit testing framework for ZSH

# Guides

* [Bash Official Reference Manual](https://www.gnu.org/savannah-checkouts/gnu/bash/manual/bash.html)
* [Bash Hackers Wiki](https://wiki.bash-hackers.org/)
* [Greg Wooledge's (aka "greycat") wiki](https://mywiki.wooledge.org).
  Specifically [Bash Guide](https://mywiki.wooledge.org/BashGuide), [Bash FAQ](https://mywiki.wooledge.org/BashFAQ) and [Bash Pitfalls](https://mywiki.wooledge.org/BashPitfalls)
* [Google's Shell Style Guide](https://google.github.io/styleguide/shell.xml)
* [The Linux Documentation Project: Bash Programming - Intro/How-to](https://tldp.org/HOWTO/Bash-Prog-Intro-HOWTO.html)
* [The Linux Documentation Project: Advanced Bash Scripting Guide](https://tldp.org/LDP/abs/html/)
* [WikiBooks: Bash Shell Scripting](https://en.wikibooks.org/wiki/Bash_Shell_Scripting)
* [Use the Unofficial Bash Strict Mode (Unless You Looove Debugging)](http://redsymbol.net/articles/unofficial-bash-strict-mode/)
* <code>105156</code> ![](https://img.shields.io/github/last-commit/jlevy/the-art-of-command-line) [The Art of Command Line](https://github.com/jlevy/the-art-of-command-line)
* [Learn Enough Command Line to Be Dangerous](https://www.learnenough.com/command-line-tutorial/basics)
* <code>&nbsp;10695</code> ![](https://img.shields.io/github/last-commit/Idnan/bash-guide) [A guide to learn bash](https://github.com/Idnan/bash-guide)
* [Shell Field Guide](https://raimonster.com/scripting-field-guide/)

# Other Awesome Lists

Other amazingly awesome lists can be found in <code>&nbsp;&nbsp;2045</code> ![](https://img.shields.io/github/last-commit/emijrp/awesome-awesome) [awesome-awesome](https://github.com/emijrp/awesome-awesome) and <code>&nbsp;28786</code> ![](https://img.shields.io/github/last-commit/bayandin/awesome-awesomeness) [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness).

### See also

* <code>&nbsp;&nbsp;9154</code> ![](https://img.shields.io/github/last-commit/agarrharr/awesome-cli-apps) [awesome-cli-apps](https://github.com/agarrharr/awesome-cli-apps)
* [awesome-fish][awesome-fish]
* [awesome-zsh][awesome-zsh]
* <code>&nbsp;10473</code> ![](https://img.shields.io/github/last-commit/k4m4/terminals-are-sexy) [terminals-are-sexy](https://github.com/k4m4/terminals-are-sexy)

[awesome-badge]: https://raw.githubusercontent.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg
[awesome-fish]: https://github.com/jorgebucaran/awsm.fish
[awesome-link]: https://github.com/sindresorhus/awesome
[awesome-zsh]: https://github.com/unixorn/awesome-zsh-plugins
