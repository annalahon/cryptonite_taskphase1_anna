# cryptonite_taskphase1_anna
## Module 7: Shell Variables

- ### Printing Variables
![image](https://github.com/user-attachments/assets/48b71dc9-1ff2-4762-8dd7-9a1daf352798)
The `echo` command just prints out the argument while `echo $` prints out the variable data, in this case the flag.

- ### Setting Variables
![image](https://github.com/user-attachments/assets/6745cd1d-4c6e-4e8d-8d55-f87a86d0a308)
Here I used `=` to assign a value 'COLLEGE' to the variable 'PWN'. Need to make sure its just 'PWN' and not '$PWN' as prepending of $ is only used to access the variable.

- ### Multi-word Variables
![image](https://github.com/user-attachments/assets/7f139820-55ea-4222-86d3-8216aa83a07c)
While assigning multi-word values to variables, we need to quote it with `" "` to ensure that it reads it as a value and not a command

- ### Exporting Variables
![image](https://github.com/user-attachments/assets/3cbe455c-3e8b-4734-9180-f1e6112cc391)
New concept of child shell processes where variable values are not automatically sent to. However we can **export** values by using `export` either while assigning a value to the variable or later.

- ### Printing Exported Variables
![image](https://github.com/user-attachments/assets/06052c11-b372-425f-a134-d86f5d5ff105)
`env` gives all the exported variables available in the shell, here including FLAG which contains the flag required.

- ### Storing Command Output
![image](https://github.com/user-attachments/assets/1bd2cb16-2c3a-4040-a797-864a143c1934)
Here, we directly set the value of **PWN** as the output of `/challenge/run` by using `=$()`

- ### Reading Input
![image](https://github.com/user-attachments/assets/ed9797b7-47f3-4b3f-9fc1-521bdd5e1143)
In this challenge, using the `read` command we can input a value for the variable directly from the terminal.

- ### Reading Files
![image](https://github.com/user-attachments/assets/c5e500ae-be49-45ec-9b3c-7eef9b7a5d26)
Here we use `read` and `<` to directly input the value of `/challenge/run` into **PWN** .
