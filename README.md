To start a git repo locally follow the following steps:-

1. go to the folder where you want to start a repo.
2. open cmd prompt.
3. type "git init" this will initialize the git repo.
4. now create a "file" or "folder" and to add follow next steps.
5. type "git add <file name>" or to add all type "git add .".
6. type "git commit -m "<commit message>"".
7. at the same time go to github.com and loggedin with your id and create a public repo there and copy the repo url.
8. Now we have to push the added file and to do it first we have to add a remote repo so to do type "git remote add <username> <repo url>"
 e.g.-- "git remote add kumarrishavpandey https://github.com/kumarrishavpandey/gitinitialize.git".
9. we'll go for git push type "git push --force <repo url>"
  e.g.-- "git push --force  https://github.com/kumarrishavpandey/gitinitialize.git".