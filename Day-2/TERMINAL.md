# TERMINAL

Besides actual coding nothing will make you feel like a developer like the command line interface through the terminal. When was the last time you saw a coder on TV use windows explorer to access the 'mainframe'? Uh, never.

The terminal allows you to interact with your computer through commands or in other words through a command line interface. There is no drag and drop. There is only the prompt, text commands, execution and output.

## Open the Terminal on a Mac
Hold 'Command' then press the spacebar. Type in Terminal in spotlight and then simply click on the first item in the search results.

## The 10 Command Lines

Here are a few things you can do once you have the terminal up.

### _**ls**_  – List Content

You can’t do anything if you cannot ‘see’.  **_ls_**  (LS not is) allows you to ‘see’ what files and folders are in your current directory. It’s a uber popular and maybe the most used command.

### _**pwd**_  – Present/Print Working Directory

If  **_ls_**  is the what  **_pwd_**  is the where.  **_pwd_**  shows you where you are in the file system. It shows you the path to your current location.

### **_cd_**  – Change Directory

Sometimes we just need a change of scenery.  **_cd_**  allows you to change your current directory. The format is

Here are some examples of what you can do with cd

-   To move up one directory or move into the parent directory
    -   `cd ..`
-   To move into another directory in the current location
    -   `cd nameOfDirectory`
-   To move to the root directory (whatever that might be)
    -   `cd ~`
-   To move multiple levels
    -   `cd nameOfDirectory/nameOfAnotherDirectory`

### **_cat_**  – concatenate

What if you quickly wanted to see the content of the file without having to open it? Well,  **_cat_**  can be used for that. The syntax is:
```
cat filename
```

### **_touch_**  – Create new File

When you  **_touch_**  something you create it. So when you would like to create a file (a different command is used for folders) you simply run  **_touch_**  followed by the filename you would like to give it. So the syntax is:

```
touch New_File.java
```

### **_mkdir_**  – Make Directory

**mkdir**  is the touch of directories.  **mkdir**  creates an empty folder.

```
mkdir folderName
```

### **_rm -r_**  – Remove Folder

What about folders you ask? Simply add the -f flag. So…

```
rm -r folderName
```

### **_mv_**  – Move File/Folder

Not satisfied with where all your files and folders are? You can move them! The syntax is:

```
mv fileOrFolderName NewLocation
```

### **_sudo_**  – Super User Mode

Privilege issues is one of the most common problem when working within the command line. To overcome it run any command with the word  **_sudo_**  in front of it. You might have to enter your system/root password when executing the command.

```
sudo command
```

### Sources
https://avantutor.com/blog/10-command-lines/
