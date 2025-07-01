1. Install `scoop`
```
PS D:\obsidian-mondee> Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
PS D:\obsidian-mondee> Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression
```

2. Install `neovim`
`scoop install neovim`

3. Create a symbolic link via Powershell (requires admin privileges)
`cmd /c mklink /D "%LOCALAPPDATA%\nvim" "D:\obsidian-mondee\nvim"`