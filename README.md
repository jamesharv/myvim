#myvim

My vim configuration.

##Setup
This directory should be recursively cloned into ~/.vim. Eg.

```
git clone --recursive git@github.com:jamesharv/myvim.git ~/.vim
```

Then symlinks should be created for .vimrc and .gvimrc as follows

```
ln -s ~/.vim/vimrc ~/.vimrc
ln -s ~/.vim/gvimrc ~/.gvimrc
```

##Help docs

After installing or updating any bundles, execute :Helptags (capitalisation important) to regenerate help tags.

