# tree

tree is a "ls" like utility for printing the contents of directories as trees
of variable depth. Save time examining downloads and projects by peeking at >1
node at once. [LuaJIT](http://luajit.org/download.html) is the only dependency.

Create an alias in ~/.bashrc to install

    alias t="/home/user/bin/tree"

Change MAXCOLS to set your desired word wrap width
    
    local MAXCOLS = 100

Usage

    tree -h                 Print help
    tree                    Graph path '.' depth 1
    tree [#depth]           Graph path '.' depth [#depth]
    tree [path]             Graph path [path] depth 1
    tree [path] [#depth]    Graph path [path] depth [#depth]

![Example](http://i.imgur.com/bRZ1J.png)
