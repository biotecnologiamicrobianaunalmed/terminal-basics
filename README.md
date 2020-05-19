# terminal-basics

## Windows

When you open the terminal or command prompt you usually find the following:

```sh
C:\Users\Name>
```

Everything before the symbol > indicates the place where you are located. The first basic command allows you to see a list of the elements and/or folders that are in the current path (C:\Users\Name). This command is **dir**, if you type it and press enter you will find something like this:

```sh
C:\Users\Name>dir

Directory of C:\Users\Name

dd/mm/aaaa    hh:mm   <DIR>   Desktop
dd/mm/aaaa    hh:mm   <DIR>   Documents
dd/mm/aaaa    hh:mm   <DIR>   Downloads
```
The order of the list depends on each computer and its content.

If you want to change folder, for example to the desktop, you can use the **cd** command and copy the respective name. 

<ins>Tip:</ins> In many cases you can use the tab key to autocomplete what you are copying.

Try to change to desktop folder as follows:

```sh
C:\Users\Name>cd Desktop
```

Remember that you must be sure that the folder is in the current path. If the command worked you should see that the path changed, as follows:

```sh
C:\Users\Name\Desktop>
```

In case you want to go back to the previous folder use the command **cd ..**

```sh
C:\Users\Name\Desktop>cd ..
```

```sh
C:\Users\Name>
```

With these three basic commands you can use the PVDP platform.

## Linux

In this operating system the **cd** and **cd ..** commands work the same way. However the command to see the folders and/or files of the present path is **ls**.


# Summary

- **dir**  : Displays a list of the contents of a directory or folder. In Linux its equivalent is **ls**.
- **cd**  : Used to move through folders and subfolders.
- **cd ..**  : Used to go back one level of folders and subfolders.
