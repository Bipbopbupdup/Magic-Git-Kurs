![](./attachments/wizzard.gif)
# Magic-Git-Kurs

hello traveler you came to the right place
if your quest i to configre some git.
## For windows User
if you heve installed git for windows you mabey have already configued git on your maschine.
please make shure that these configuration were made
- use the basj

## Configure your git

> [!WARNING] For macOS Users
>Run these two commands to tell Git to ignore .DS\_Store files, which are automatically created when you use Finder to look into a folder. .DS\_Store files are invisible to the user and hold custom attributes or metadata (like thumbnails) for the folder, and if you don’t configure Git to ignore them, pesky .DS\_Store files will show up in your commits. Remember to copy and paste each of these commands into your terminal.
>```bash
>echo .DS_Store >> ~/.gitignore_global
>```
>```bash
>git config --global core.excludesfile ~/.gitignore_global
>```
>

### Git Einstellen

add  name
```bash
git config --global user.name "Your Name"
```

add eamil
```bash
git config --global user.email "yourname@example.com"
```

rename master default to main
```bash
git config --global init.defaultBranch main
```

pull behaivior
```bash
git config --global pull.rebase false
```

vscode
```bash
git config --global core.editor "code --wait"
```

nano
```bash
git config --global core.editor "nano --wait"
```

check configs
```bash
git config --list
```
or
```bash
git config --get user.name
git config --get user.email
```

### ssh

chek for ssh key
```bash
ls ~/.ssh/id_ed25519.pub
```

create key
```bash
ssh-keygen -t ed25519
```

get public key
```bash
cat ~/.ssh/id_ed25519.pub
```
