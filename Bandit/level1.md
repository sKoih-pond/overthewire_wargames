# Bandit Level 1

### Level Goal

The password for the next level is stored in a file called **readme** located in the **home directory**. Use this password to log into bandit1 using SSH. Whenever you find a password for a level, use SSH (on port 2220) to log into that level and continue the game.


## Walkthrough

Logging into the [bandit0 lab](https://github.com/sKoih-pond/overthewire_wargames/blob/main/Bandit/level0.md) ends at the home directory. 

![Command breakdown](/Bandit/BanditAssets/level1.png)

The `ls` command will list a single readable file called "readme". 

** The `-al` option will list all hidden files and directories in long format, displaying full information such as file type, Read + Write + Special + Alernative access modes, Link count, Owner, Group, File size and Time of last modification.

`cat readme` will output the contents of the "readme" file to the terminal, which contains the password for accessing the next lab, [bandit 2](https://github.com/sKoih-pond/overthewire_wargames/blob/main/Bandit/level2.md).