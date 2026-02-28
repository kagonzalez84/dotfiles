# Using chezmoi.io

https://www.chezmoi.io/quick-start/#start-using-chezmoi-on-your-current-machine

# Setting up a new machine

## Configure variables

Edit file `~/.config/chezmoi/chezmoi.toml` and set:

```toml
[data]
    email = "kgonzaleztorres@firstam.com"
```

```bash
chezmoi init --apply kagonzalez84
```

## Adding new updated files

```bash
chezmoi add ~/.bashrc
chezmoi cd
git add *
git commit -m "..."
git push origin -u main
```
