# git-dl

A tiny Bash script to download files from Git repositories.

```
$ ./git-dl
usage: git-dl <git-repo-url> <file-path> [git-clone-args...]

$ ./git-dl https://github.com/kevin-hanselman/git-dl git-dl
Cloning into 'git-dl-70RZj'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (5/5), done.
remote: Total 6 (delta 0), reused 6 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.
cp: overwrite './git-dl'? n
```
