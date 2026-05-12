![](./attachments/wizzard.gif)
# Magic-Git-Course

*“Heeellooo, traveleeeer…*
*I seeee… you seek to git gud… heh heh…*
*If it is your quest… to install... and to configure some git...*
*then fret not, for fate has guided you to the right place.*
*~ hocusss… pocusss… do not loooose your focuuusss… ~"*

## Install VSCode
 
For this course, we strongly suggest using [Visual Studio Code](https://code.visualstudio.com/download).

## Setting up Git

Follow the steps according to your operating system.

### For MacOS and Linux users

1. Go to the Odin project and follow the instructions for setting up Git
[here](https://www.theodinproject.com/lessons/foundations-setting-up-git).

2. After following the instructions change your default commit-editor to *VSCode*:
```bash
git config --global core.editor "code --wait"
```

### For Windows users

1. Install [Git for Windows](https://gitforwindows.org/index.html).
   Once the installer has started, follow the instructions as provided in the **Git Setup** wizard screen until the installation is complete.
   Alternatively, you can follow this **YouTube tutorial** [here](https://www.youtube.com/watch?v=t2-l3WvWvqg).
2. After the installation create a GitHub account (if you haven't done so yet).
3. Connect an SSH key to the account. [This](https://docs.github.com/en/authentication/connecting-to-github-with-ssh) could be helpful.
4. If you have any problems with the configuration, don't worry — we will work through it together before the course starts with those using the university PCs, where you can join.

### For people without a portable device capable of using Git

1. Create a GitHub Account (if you haven't done so yet).
2. Please come 30 minutes before the course starts. We will then configure Git and add the SSH key together.
   
> [!IMPORTANT]
> Please make sure that the default branch name is set to `main`!
> 

## After setting up Git
 
Check if all of your settings are configured correctly:
```bash
git config --list
```
*(press `q` to quit)*

Your output should be similar to this:
```ini
user.name=your-name
user.email=your@email.com
init.defaultbranch=main
color.ui=auto
pull.rebase=false
core.editor=code
```


## If any problems arise

Don't fret if something does not work.
You can write us via Teams or email us if you need help:
- ali.liske@haw-hamburg.de
- gleb.kamnev@haw-hamburg.de

We will also be there to help 30 min before the course starts. :)

---

> [!NOTE] 
> 
> If you don't like the idea of using tools made by Microsoft or US tech companies, and you know what you're doing and want to use a different IDE or Git hosting platform, then go for it. Please note that 
> the tasks and tutorials were created based on the assumption that you're using VSCode and GitHub.
>

## Ressources

- [odin Foundations Course](https://www.theodinproject.com/paths/foundations/courses/foundations)
- [Git Book](https://git-scm.com/book/en/v2)
- [Git GUI Clients](https://git-scm.com/tools/guis)
- [Git Documentation](https://git-scm.com/docs)
- [GitHub Documentation](https://docs.github.com/en)
- [Git Cheat Sheat](https://git-scm.com/cheat-sheet)
- [freeCodeCamp git course](https://www.freecodecamp.org/news/git-and-github-crash-course/)
- [a small git refresher](https://gist.github.com/brandon1024/14b5f9fcfd982658d01811ee3045ff1e)
- [Linux Basics](https://labex.io/linuxjourney)
- [IntelliJ IDEA git](https://www.jetbrains.com/help/idea/using-git-integration.html)
- [VS Code git](https://code.visualstudio.com/docs/sourcecontrol/intro-to-git)
- [git fubar](https://gitfu.fyi/)
- [github git guide](https://github.com/git-guides)
