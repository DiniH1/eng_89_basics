# Steps to upload from a local save to github.
### Create a repo on github with appropriate naame
 
## Creating a key on the terminal
- open the terminal and create a `.ssh` save on the terminal
- direct to the created .ssh using cd `~/.ssh`
- to create your key insert the following `ssh-keygen -t rsa -b 4096 -C "your_email@example.com"` for windows users
- `ssh-keygen -t ed25519 -C "your_email@example.com" for mac users`
- use `cat id_ed25519.pub` to display the code on terminal
- copy and paste the code on the github (settings - SSH KEY)

## Uploading from a local save to github
- git init
- git add README.md
- git commit -m "first commit"
- git branch -M main
- git remote add origin git@github.com:<folder>.git
- git push -u origin main



