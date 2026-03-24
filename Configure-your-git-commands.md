## Configure your git fast

> [!WARNING]
> 
> For macOS Users
> 
>Run these two commands to tell Git to ignore .DS\_Store files, which are automatically created when you use Finder to look into a folder. .DS\_Store files are invisible to the user and hold custom attributes or metadata (like thumbnails) for the folder, and if you don’t configure Git to ignore them, pesky .DS\_Store files will show up in your commits. Remember to copy and paste each of these commands into your terminal.
>
>```bash
>echo .DS_Store >> ~/.gitignore_global
>```
>```bash
>git config --global core.excludesfile ~/.gitignore_global
>```
>


**add  name**
```bash
git config --global user.name "Your Name"
```

**add eamil**
```bash
git config --global user.email yourname@example.com
```

**rename master default to main**
```bash
git config --global init.defaultBranch main
```

**pull behaivior**
```bash
git config --global pull.rebase false
```

**set commit editor to vscode**
```bash
git config --global core.editor "code"
```

**or nano**
```bash
git config --global core.editor "nano"
```

**check configs**
```bash
git config --list
```
or
```bash
git config --get user.name
git config --get user.email
```

### ssh

**check for ssh key**
```bash
ls ~/.ssh/id_ed25519.pub
```

**create key**
```bash
ssh-keygen -t ed25519
```

**get public key**
```bash
cat ~/.ssh/id_ed25519.pub
```
