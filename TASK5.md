recruit@recruit:~$ cd ~/Documents
recruit@recruit:~/Documents$ touch pad.md
recruit@recruit:~/Documents$ cd ~/Desktop
recruit@recruit:~/Desktop$ mkdir work
recruit@recruit:~/Desktop$ cd ~/Documents
recruit@recruit:~/Documents$ cp pad.md pad_copy.md
recruit@recruit:~/Documents$ mv pad_copy.md ~/Desktop/work
recruit@recruit:~/Documents$ sudo updatedb
[sudo] password for recruit:         
recruit@recruit:~/Documents$ (cd -)
/home/recruit/Desktop
recruit@recruit:~/Documents$ cd ~/Desktop
recruit@recruit:~/Desktop$ locate pad_copy.md
/home/recruit/.local/share/Trash/files/pad_copy.md
/home/recruit/.local/share/Trash/files/work/pad_copy.md
/home/recruit/.local/share/Trash/info/pad_copy.md.trashinfo
/home/recruit/Desktop/work/pad_copy.md
recruit@recruit:~/Desktop$ 

