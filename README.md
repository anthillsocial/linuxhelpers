myconfig
========

My configeration file for vim (and possibly other in the future) to 
enable easy switching between machines. I simpley backup, then create 
a sym link to the myconfig directory in order to start using this 
config on any machine I am logged into:
  $ mv .vimrc .vimrcOLD; ln -s myconfig/.vimrc .vimrc