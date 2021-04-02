append 'spotify' to modules and

[module/spotify]
type = custom/script
interval = 1
format-prefix = " "
format-foreground = #b8beca
format = <label>
exec = python /home/euro/.spotify.py -f '{artist}: {song}'

to ~/.config/polybar/config
