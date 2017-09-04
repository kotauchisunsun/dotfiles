# dotfiles
my_dotfiles

# install vim-plug
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
  https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim

# install vim plugins
:PlugInstall

# install syntax check by pep8
pip install pep8
pip install autopep8

# configure pep8
cp -R pep8/ ~/.config/
