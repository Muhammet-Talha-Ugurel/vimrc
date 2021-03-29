# Instalation
```
mkdir ~/.vim/undodir -p
```
```
git clone https://github.com/Muhammet-Talha-Ugurel/vimrc.git
```
```
curl -fLo ~/.vim/autoload/plug.vim --create-dirs  https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```
```
vim .vimrc
```
```
:source %
```
```
:PlugInstall
```
### For ubuntu 20.04
```
sudo apt install build-essential cmake vim-nox python3-dev
```
```
sudo apt install mono-complete golang nodejs default-jdk npm
```
```
cd .vim/plugged/YouCompleteMe/
```
```
python3 install.py --all
```
