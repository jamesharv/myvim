
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

##Plugin Setup

###YouCompleteMe

See [http://vimawesome.com/plugin/youcompleteme#mac-os-x](http://vimawesome.com/plugin/youcompleteme#mac-os-x).

```
# For JavaScript support, ensure node / npm are installed.

# For typescript support, if not already installed.
npm install -g typescript

# Change to youcompleteme dir.
cd ~/.vim/bundle/youcompleteme

# Install all git submodules.
git submodule update --init --recursive

# Install cmake
brew install cmake

# Install with JavaScript support.
./install.py --tern-completer 
```

##Help docs

After installing or updating any bundles, execute :Helptags (capitalisation important) to regenerate help tags.

