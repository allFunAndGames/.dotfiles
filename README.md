# dotfiles repo to be used with GNU stow

## Installation
1. Clone the repo
```
git clone https://github.com/allFunAndGames/.dotfiles.git ~/.dotfiles
```
2. Change to the directory
```
cd ~/.dotfiles
```
3. Execute `stow`
```
stow .
```
## Update the repo
```
cd ~/.dotfiles
git add .
git commit -m 'my preferably meaningful, but brief, commit message'
git push origin main
```
## Update dotfiles from new version of repo
```
cd ~/.dotfiles
git pull
stow -R .
```
