1. install Obsidian Git plugin
2. Enable Obsidin Git plugin
3. create a folder for remote repo in Obsidian Vault
4. run command (command-P): "Git: Clone an existing repo"
5. enter repo URL: "https://GithubAccessToken@github.com/username/reponame.git"
6. 4. set environment variable to you Github email (MacOS):
```shell
% git config --global user.email "okopylov@gmail.com"
```
6. restart Obsidian
7. to sync with Github run command (command-P) "Git: Create Backup"