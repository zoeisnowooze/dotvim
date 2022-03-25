# .vim configuration

<img src="https://raw.githubusercontent.com/zoeisnowooze/dotvim/main/screenshot.png">

Clone this repository in a directory named `.vim` in your home directory (hence
the name "dotvim"). Create a symbolic link from the `vimrc` file to a file
named `.vimrc` in your home directory.

For example:

    zo@laptop:~$ cd
    zo@laptop:~$ git clone https://github.com/zoeisnowooze/dotvim.git .vim
    Cloning into '.vim'...
    ...
    zo@laptop:~$ ln -s .vim/vimrc .vimrc
    zo@laptop:~$ vim


When you're ready, launch Vim and use the `:PlugInstall` command to install all the plug-ins.
