# This is a demo on using git and github

## Steps
### Setup
1. Create project
2. Convert the project into a local repository or initialize it as local repo
```bash
git init 
```
- Setup user name and email
```bash
git config --global user.name "dhncfrnndz" 
git config --global user.email "dhanicafearl.fernandez@lorma.edu"
```
3. Create a remote repo on GitHub
4. Connect local and remote so they'll in sync
```bash
git remote add origin <repo-link>
git remote show origin
```
5. Push or upload local changes to remote repo
```bash
git status                          # see current status
git add .                           # prepare to save all changes)
git commit -m "Description"         # save prepared changes locally, providing a message or description
git push -u origin main             # send commits to remote repo to update it
```
6. Logout of GitHub on shared computers
```bash
git credential-cache exit
git credential-manager github list
```
### Development
1. Stage > git add .
2. Commit > git commit -m "message
3. Push"> git push

