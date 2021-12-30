# my-screenrc
My screenrc settings

```
startup_message off
defscrollback 5000
termcapinfo xterm ti@:te@
termcapinfo xterm-color ti@:te@
hardstatus alwayslastline
hardstatus string '%{gk}[%{G}%H%{g}][%= %{wk}%?%-Lw%?%{=b kR}(%{W}%n*%f %t%?(%u)%?%{=b kR})%{= kw}%?%+Lw%?%?%= %{g}]%{=b C}[%m/%d/%y %C %A]%{W}'
vbell off
shell -$SHELL
logtstamp on
logtstamp after 1
```
## References
* https://thoughtbot.com/blog/migrating-from-screen-to-tmux
* https://hobo.house/2016/07/16/tmux-for-gnu-screen-refugees-and-vim-users/
