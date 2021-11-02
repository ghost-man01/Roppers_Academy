# Linux Filesystem

# Drive Layout

[ B ] [S] [Inode list] [Data Blocks] | | | | | |+—– Super Block |+ ————-Boot Area

**INode list** – Inode list is stored the information of file. OSes take the information from Inode list and we just open the file. Inode are pointers OSs use to give the location of a block of data. Inode stands for **Indexed Node**. [[Pasted image 20210905200301.png]]