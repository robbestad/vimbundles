##### 1. Backup your old .vim directory
```mv ~/.vim ~/vim_old```

##### 2. Clone this to .vim
```git clone git@github.com:svenanders/vimbundles.git ~/.vim```

##### 3. Install
```cd ~/.vim```
```git submodule init && git submodule update```

```git submodule init``` and ```git submodule update``` need to be run every time a new submodule is added. 

```git submodule foreach git pull``` is used to pull latest upstream changes.

