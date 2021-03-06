## Remember the double dots?

When we executed the `ls -a` command, we noticed a set of single and double dots: `. ..`

As we previously mentioned these dots are utilities that _bash_ uses to help navigate the _file system_.

### Going back one directory level

Having entered the _dir1_ directory in the previous section, we may then want to get back out of it:

1. Execute the `pwd` command to confirm we are on the _dir1_ directory
2. Execute the `ls -a` command to confirm that we indeed have single and double dots available
2. Execute `cd ..` to exit the current directory and go back 1 directory (to the parent directory)
3. Execute `pwd` to confirm that we are back on the `/home/codio/workspace/` directory