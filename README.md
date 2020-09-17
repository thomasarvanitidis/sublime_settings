# sublime_settings

Sublime Text 3 Settings. See steps in [post](https://stackoverflow.com/a/38726243)

## Setup repo

```bash
cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User
git init
git add <snipets & settings>
git commit -am "Track settings"
git remote add origin <url>
git push -u origin master
```

## Pulling to new machine

```bash
cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User/
git init
git remote add origin <url>
rm Package\ Control.sublime-settings
git fetch
git checkout -t origin/master
```
