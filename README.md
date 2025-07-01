# obsidian-mondee

- `scoop install starship`
- `scoop install gcc`
- `winget install nushell`

```
mkdir ($nu.data-dir | path join "vendor/autoload")
starship init nu | save -f ($nu.data-dir | path join "vendor/autoload/starship.nu")
```
