##### 1. Backup your old .vim directory
mv ~/.vim ~/vim_old                                           

##### 2. Create a blank .vim directory
mkdir .vim 

##### 3. Clone the pathogen repo
git clone git://github.com/tpope/vim-pathogen.git pathogen    

##### 4. Move pathogen to .vim directory
mv pathogen/autoload ~/.vim/autoload

##### 5. Install
git submodule init && git submodule update

```git submodule init``` and ```git submodule update``` need to be run every time a new submodule is added. 
```git submodule foreach git pull``` is used to pull latest upstream changes.

