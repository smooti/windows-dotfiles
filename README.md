### Requirements

- [chezmoi](https://www.chezmoi.io/) (Dotfile management)
- [git](https://git-scm.com/install/windows) (Version Control)

### Checkout and Apply Dotfiles

```powershell
# Via ssh
chezmoi init --apply git@github.com:smooti/windows-dotfiles.git

# Via HTTPS
chezmoi init --apply https://github.com/smooti/windows-dotfiles.git
```

### Update Dotfiles

```powershell
chezmoi update
```
