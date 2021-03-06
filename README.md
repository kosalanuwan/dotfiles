# dotfiles
> WARNING! Make sure you know what you are doing and use at your own risk!

This repo includes a shell script for executing the bulk of the configuration I follow to set up my Mac's development environment to get me up-to-speed with the tools et al. so I can more quickly get back to coding.

## Contents

| File | Description
| --- | ---
| `.zshrc` | Customizes the default Terminal.app prompt.
| `.bash_profile` | Customizes the bash Terminal.app prompt.
| `.gitconfig` | Global Git configuration to specify my name and email, shortcuts, colors, and more.
| `.gitignore` | The ignores from [@github/gitignore](https://github.com/github/gitignore) that I use everywhere.
| `brew.sh` | Install some of the core tools I use.
| `macos.sh` | Configure Terminal to be smarter.

## Shell Script

```bash
curl https://raw.githubusercontent.com/kosalanuwan/dotfiles/main/install.sh > ~/.dotfiles/install.sh && bash ~/.dotfiles/install.sh
```

### Rename `master` to `main`:
```bash
git branch -m master main
git fetch origin
git branch -u origin/main main
git remote set-head origin -a
```

## Credit

Many of the customizations are taken from:
- [@mathiasbynens/dotfiles](https://github.com/mathiasbynens/dotfiles)
- [@pawelgrzybek/dotfiles](https://github.com/pawelgrzybek/dotfiles), and 
- [@mdo/config](https://github.com/mdo/config)
## WOMM

Yep, it works on my machine and hopefully it does on your's as well but please don't hate me if it doesn't.
