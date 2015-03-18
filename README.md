# archive
Bash function to extract and compress in unified style

# how to
cd ~ && wget https://raw.githubusercontent.com/cojack/archive/master/archive.sh

Edit your .bashrc file and add at the end:

```
if [ -f ~/archive.sh ]; then
    source ~/archive.sh
fi

reload .bashrc

```
source ~/.bashrc

# usage

archive [OPTIONS]

-e extract
-c compress
-h help

@TODO compress

example:

archive -e ~/path/to/the/file.tar.gz
