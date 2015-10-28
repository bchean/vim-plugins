### Syncing vim plugins

```
# Create .vim dir if necessary
mkdir -p ~/.vim

# Clone this repo
cd ~/.vim
git clone <this-repo>

# Activate pathogen in your vimrc
echo "execute pathogen#infect()" >> ~/.vimrc
```
