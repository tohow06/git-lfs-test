# git-lfs-test

## quick cheat

```bash
# install & init
$ curl -s https://packagecloud.io/install/repositories/github/git-lfs/script.deb.sh | sudo bash
$ sudo apt-get install git-lfs
$ git lfs install

# track large file
$ git lfs track 'cat.bin'
$ git add .gitattributes
$ git add cat.bin

# commit and push
$ git commit -m "added cat.bin"
$ git push
```

## Tutorial Reference
https://cyruschiu.github.io/2016/09/26/using-git-lfs/
