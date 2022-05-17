tmux
=====

Self-contained, pretty and versatile `.tmux.conf` configuration file.

Installation
------------

Requirements:

  - tmux **`>= 2.3`** (soon `>= 2.4`) running inside Linux, Mac, OpenBSD, Cygwin
    or WSL
  - awk, perl and sed
  - outside of tmux, `$TERM` must be set to `xterm-256color`

To install, run the following from your terminal: (you may want to backup your
existing `~/.tmux.conf` first)

```
$ cd
$ git clone https://github.com/cozyviking/tmux/
$ cp tmux/.tmux.conf.local .
$ cp tmux/.tmux.conf .
```

