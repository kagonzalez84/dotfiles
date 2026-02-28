# Using chezmoi.io
https://www.chezmoi.io/quick-start/#start-using-chezmoi-on-your-current-machine

# Setting up a new machine
chezmoi init --apply kagonzalez84

## Adding new updated files
chezmoi add ~/.bashrc
chezmoi cd
git add *
git commit -m "..."
git push origin -u main
