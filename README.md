# vim
This is my .vim directory.  It is a version of https://github.com/farazdagi/vim-go-ide
using vim-plug instead of an install script.

```
git clone git@github.com:emeka/dotvim.git ~/.vim
```

The repository also contains the .vimrc.  You can either link/copy it to your
home directory or create an alias if you are using a unix flavour.  My alias
says:

```
alias vim='vim -u ~/.vim/.vimrc'
```

Then run vim:

```
vim
```

and in vim, use the following commands to update your bundles:

```
:PlugInstall
```

That's it.
