# foose
Ctrl-P like command line (bash) script.

Foose stands for Find chOOSE

Put foose file into your ~/bin directory or any other directory from you $PATH,
then you could call it like ```foose <part_of_file_name>```, it'll basically do
```find . | grep "<part_of_file_name>"``` and gives you list of matched files
as menu which you could navigate via arrow keys or vim-like hk, press Enter to
open file with your favorite editor from $EDITOR enviroment variable.

If only one file found, it'll be open right up

## Installation
```
curl https://raw.githubusercontent.com/hmepas/foose/master/foose > ~/bin/foose
chmod +x ~/bin/foose
echo 'export EDITOR=/usr/bin/vim' >> ~/.bashrc # or whatever your favorite text editor is
```
or give any other name which suits you, like ~/bin/p or ~/bin/ctrlp
