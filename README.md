# starship

Configuration of starship and wezterm.

Configutation file ('starship.toml') standard location:

```
~/.config # Unix-like systems and Windows
```

If fish shell is used, change the initialization command to:

```
starship init fish --print-full-init | sed 's/"$(commandline)"/(commandline | string collect)/' | source
```
