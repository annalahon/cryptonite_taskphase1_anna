# cryptonite_taskphase1_anna
## Module 4: Digesting Documentation

- ### Learning from Documentation
![image](https://github.com/user-attachments/assets/9da96eee-fc63-4cb8-94d9-ef40e0056945)
Requires reading from program documentation and using the given arguments to get the flag.

- ### Learning Complex Usage
![image](https://github.com/user-attachments/assets/a4e1080d-6bfc-4a79-b9ee-a776fafa9203)
Here the argument is `--printfile ` which prints arbitrary files to the terminal. When this argument is given with `/flag`, it prints the contents of the file, giving us the flag

- ### Reading Manuals
![image](https://github.com/user-attachments/assets/445569b1-c2bc-407c-b118-dfc975a35140)
![image](https://github.com/user-attachments/assets/ead37c8f-a196-4d8d-ac15-4bbcb300e69e)
Teaches the usage of `man` command to access the manual page for commands. Using the manual for challenge, we can specify the arguments required to get the flag.

- ### Searching Manuals
![image](https://github.com/user-attachments/assets/273525e4-2f72-471e-be79-8940dfaa53e8)
Using `/` to search for flag in the manual

- ### Searching for Manuals
![image](https://github.com/user-attachments/assets/0e742856-25a3-48a5-9b6b-6bf2d4a52fc1)
![image](https://github.com/user-attachments/assets/9f18e729-3010-418c-a828-dbedad6151ee)
![image](https://github.com/user-attachments/assets/47659784-0ded-471f-a7b7-8635fb8c8a86)
![image](https://github.com/user-attachments/assets/d0e47f10-9f48-4414-bf54-0d551cc62da4)
![image](https://github.com/user-attachments/assets/1d702c2e-66ee-42e3-8c5f-5808213c340d)
Used `man man` command to get manual for `man` command. Through that, we got the knowledge of using  `-k` to find the hidden file. Once we find the challenge file, we use the correct argument to get the flag.

- ### Helpful Programs
![image](https://github.com/user-attachments/assets/7e34663e-a9be-4e58-827e-1bbcb6de4310)
Using the `--help` argument to help us understand how to use the `/challenge/challenge` command and what arguments to put to get the flag.

- ### Help for Builtins
![image](https://github.com/user-attachments/assets/8009c730-89b0-4339-96fd-e41a4c085a44)
Here, the challenge command is a shell built-in and not a command. So we can use help to find the correct argument and value to input to get the flag.
