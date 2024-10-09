# cryptonite_taskphase_anna
## Module 3: Comprehending Commands

- ### Cat: not the pet, but the command
![image](https://github.com/user-attachments/assets/153d3092-e7cd-4f4b-a862-58263d65a76e)
New function `cat` used to read the argument file from the respective directory

- ### Catting absolute paths
![image](https://github.com/user-attachments/assets/fda3e477-e643-4679-a2bd-b7373ece3812)
Same process as previous challenge but argument is the absolute path of the file

- ### More catting practice
![image](https://github.com/user-attachments/assets/553cf65d-b4dd-4316-afcd-5626fbcf0af3)
Using cat with absolute path but without using `cd` to go into the directory.

- ### Grepping for a needle in a haystack
![image](https://github.com/user-attachments/assets/b7bfc414-28f5-4c26-bf2f-b23902c007ba)
New function `grep` introduced. Used to read the required lines from the file and print it onto the console.

- ### Listing files
![image](https://github.com/user-attachments/assets/e8813e40-860d-4909-a1d0-6a58d098ba1b)
The `ls` command lists all the files/directories in a given directory. It can be used to find a specific file like the renamed run file that we found here

- ### Touching files
![image](https://github.com/user-attachments/assets/b08a7037-6620-406b-844b-85ebb628a959)
The `touch` command allows us to create a file in the chosen directory.

- ### Removing files
![image](https://github.com/user-attachments/assets/1ecde67e-57c7-43b3-a3ba-936ba7738445)
The `rm` command removes the chosen file in the respective directory.

- ### Hidden files
![image](https://github.com/user-attachments/assets/1fd3ef8a-98e0-43de-89ff-532d19e9ffda)
By using `ls` with an `-a` flag, we can access any 'hidden' files that start with a '.' and use cat to read the content of that specific file.

- ### An Epic Filesystem Quest
![image](https://github.com/user-attachments/assets/90ab2f8a-56da-4335-bd0f-f9d2157977d3)
![image](https://github.com/user-attachments/assets/c54b3822-9eba-448e-891b-31b417fdf554)
![image](https://github.com/user-attachments/assets/15e03cbf-0483-41cc-8341-62aecf553f79)
![image](https://github.com/user-attachments/assets/03cbba31-6732-4280-bcc6-ecad82c990de)
Quest was super lengthy, requiring us to use cat,ls,ls -a, cd to go into various directories and also get contents of the directory without going into it, to read hidden files and finally get the flag.

- ### Making Directories
![image](https://github.com/user-attachments/assets/67ca398c-039a-4bcd-8afc-b21265bfc55b)
The `mkdir` command can be used to make directories within a directory. Then we created a file in it and checked it.

- ### Finding files
![image](https://github.com/user-attachments/assets/59851f7b-f5e1-40f4-ab97-ef53526ccf8c)
![image](https://github.com/user-attachments/assets/cb66fa06-acba-4cd4-a7e6-e3616633b8fc)
Using `find` command in the '/' directory to look for a file with the name 'flag'.

- ### Linking files
![image](https://github.com/user-attachments/assets/7117ad10-59d8-4de9-8a4c-352e6da1effc)
Here we had to make `/home/hacker/not-the-flag` a symlink for `/flag` so when we accessed it through `/challenge/catflag` it gives us the flag file instead.
