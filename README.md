# Magic-Git-Kurs
Eine repo fuer den Git-Good Kurs

## Commads zum kopiren

nur fuer mac user
```bash
echo .DS_Store >> ~/.gitignore_global
git config --global core.excludesfile ~/.gitignore_global
```

### Git Einstellen

```bash
git config --global user.name "Your Name"
git config --global user.email yourname@example.com
```

```bash
git config --global init.defaultBranch main
```

```bash
git config --global pull.rebase false
```

```bash
git config --get user.name
git config --get user.email
```
