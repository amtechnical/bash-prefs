Shell Preferences
=================

Quick and easy way of adding some sensible default settings for the following programs:
* GNU Screen (Terminal Multiplexer)
* VIM (VI IMproved text editor)
* BASH (Bourne Again SHell)

These can be installed by running the following in a terminal:

```bash
cd
git clone https://github.com/91dave/bash-prefs.git
cd bash-prefs
cp bash_prefs ../.bash_prefs
echo "source ~/.bash_prefs" >> ~/.bashrc
cp dircolors ../.dircolors
cp screenrc ../.screenrc
cp vimrc ../.vimrc
cd ..
rm -rf bash-prefs
```
