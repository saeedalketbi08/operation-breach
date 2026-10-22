# Linux Cheat Sheet

- **SSH**: lets you connect and control another computer remotely by typing commands. Example: `ssh bandit0@bandit.labs.overthewire.org -p 2220`
- **ls**: shows you the files in the folder youre in right now. example typing the command `ls` will show you the files in the folder 
- **file**: tells you what type of file. Example: typing `file readme` will show you the type of file it is
- **cat**: prints whatever is in the file. example: typing `cat readme` will show you whats in the file
- **exit**: it logs you out of the server. typing `exit` will make you log out of the page or window.
- **./**: . means the folder youre at right now, / means inside the folder, youll need it when theres a dash (-). Example: `cat ./-`, the - is the file name without the ./ the linux will think the dash is an option.
- **" "**: means that theres a name that has spaces using the quote will make the linux know that its the file name. Example `cat ./"--space in the filename--"`
- **find**: searches for files that match their label size or owner. example: `find . -size 1033c`
- **du -b**: shows how much space the files takes up in bytes. example: `du -b`
- **-size**: an option that tells find to match the files by their size. example: `find . -size 1033c`
- **cd**: lets you go into a directory. example `cd inhere`
- **-a**: shows all files including hidden files. example: `ls -a`
- ** `*`**: shows every file name. example: `file ./*`
- **..**: lets you get back to the previous folder. example `cd ..`
