$ mv ~/.vim ~/vim_old                                           # 1. Backup your old .vim directory
$ mkdir .vim                                                    # 2. Creat a blank .vim directory
$ git clone git://github.com/tpope/vim-pathogen.git pathogen    # 3. Clone the pathogen repo
$ mv pathogen/autoload ~/.vim/autoload                          # 4. Move pathogen to .vim directory

git submodule init and git submodule update need to be run every time a new submodule is added. git submodule foreach git pull command is used to pull latest upstream changes.

