# Magic-Git-Kurs
Eine repo fuer den Git-Good Kurs

## Commands zum kopieren

nur für mac user
```bash
echo .DS_Store >> ~/.gitignore_global
git config --global core.excludesfile ~/.gitignore_global
```

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
git config --global core.editor "code"
```

nano
```bash
git config --global core.editor "nano"
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
