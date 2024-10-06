# cryptonite_taskphase1_anna
## Module 2 : Pondering Paths

- ### The Root
![image](https://github.com/user-attachments/assets/5247c72e-4b92-4b2e-9a28-8c75e34b314d)
Teaches the concept of 'absolute path'. The `/` command indicates the 'root directory' in which the 'pwn' program is, so the command `/pwn` runs the pwn program in the root directory, giving us the flag

- ### Program and absolute paths
![image](https://github.com/user-attachments/assets/01f6fd66-2be1-43f4-88c4-052d889495db)
Applying the concept of 'absolute path' to access the program 'run' which is in the 'challenge' directory which in turn is in the root directory. 

- ### Position thy self
![image](https://github.com/user-attachments/assets/f9e98095-47b6-42d2-860d-277681aa6163)
When `/challenge/run` is first invoked here, it gives us an error and a directory to go into. Using the `cd` command, we enter the directory and invoke the program again

- ### Position elsewhere
![image](https://github.com/user-attachments/assets/efc23a52-2b44-4369-b113-45bbeac59afe)
Same process and outcome as before

- ### Position yet elsewhere
![image](https://github.com/user-attachments/assets/0fa1f414-03f7-4111-b3a9-7341e81c82d6)
Same process and outcome as before

- ### Implicit relative paths, from /
- ### Explicit relative paths, from /
- ### Implicit relative path

- ### Home Sweet Home
![image](https://github.com/user-attachments/assets/c0de8bc6-a36d-4d35-bbd5-91c00a5acba6)
Here, we are required to write the flag into a file in the `~` which stands for `/home/hacker`. Hence by `~/a` we're giving the place for where the flag should be written and `/challenge/run` writes a copy of the flag in the required destination.
