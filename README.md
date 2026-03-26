![](./attachments/wizzard.gif)
# Magic-Git-Course

*“Heeellooo, traveleeeer…*
*I seeee… you seek to git gud… heh heh…*
*If it is your quest… to install... and to configure some git...*
*then fret not, for fate has guided you to the right place.*
*~ hocusss… pocusss… do not loooose your focuuusss… ~"*

## install Vs-code
 
For this course, we strongly suggest using [Visual Studio Code](https://code.visualstudio.com/download) 

## Setting up git

follow the steps according to your operating system.

### For MacOS and Linux User

1. go to the Odin project and follow the instructions for setting up git
[here](https://www.theodinproject.com/lessons/foundations-setting-up-git).

2. After following the instructions change your default commit-editor to *VScode*.
```bash
git config --global core.editor "code --wait"
```

### For windows User

1. install [git for windows](https://gitforwindows.org/index.html)
   Once the installer has started, follow the instructions as provided in the **Git Setup** wizard screen until the installation is complete.
   alternatively you can follow this **YouTube tutorial** [here](https://www.youtube.com/watch?v=t2-l3WvWvqg)
2. after the Installation create a GitHub Account
3. connect an ssh key to the account [could be helpful](https://docs.github.com/en/authentication/connecting-to-github-with-ssh)
4. NEEED TO DOO MORE RESEARCH
   
> [!INFO]
> please make sure that the default branch name is set to main
> 

## After setting git up
 
 check if all of your setting are implemented.
```bash
git config --list
```
*(press q to quit)*

your output should be similar to this
```bash
user.name=your-name
user.email=your@email.com
init.defaultbranch=main
color.ui=auto
pull.rebase=false
core.editor=code
```


## if problem's arise

dont fret if something dose not work.
you can write or email us if you need help.
- Ali.Liske@haw-hamburg.de
- Gleb.nachname@haw-hamburg.de
We will be also be there to help 30 min before the course starts :)

---

> [!info] 
> 
> If you don't like the idea of using tools made by Microsoft or US tech companies, and you know what you're doing and want to use a different IDE or Git hosting platform, then go for it. Please note  that 
> the tasks and tutorials were created based on the assumption that you're using VSCode and GitHub.
>
