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
