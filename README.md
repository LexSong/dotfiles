### How to use

In the home directory:

    git init --bare .dotfiles
    git --git-dir=.dotfiles remote add origin https://github.com/LexSong/dotfiles
    git --git-dir=.dotfiles fetch
    git --git-dir=.dotfiles --work-tree=. checkout [<branch>]
