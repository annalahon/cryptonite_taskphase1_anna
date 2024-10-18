# cryptonite_taskphase1_anna
## Module 8: Processes and Jobs

- ### Listing Processes
![image](https://github.com/user-attachments/assets/ab20cbc0-4995-4308-b143-d81de520ae0a)
Using `ps -ef` or `ps aux` displays all the current running processes. From this we can figure out the challenge process required to get the flag.

- ### Killing Processes
![image](https://github.com/user-attachments/assets/46388078-e795-4d4a-a1c5-f685695f6f68)
The `kill` code is used to stop a running process. Here we used it to stop the `/challenge/dont_run` process before running the `/challenge/run` process.

- ### Interrupting Processes
![image](https://github.com/user-attachments/assets/c2bcd9c1-c749-4a60-b46d-5900184fee95)
`Ctrl-C` is used to interrupt processes, i.e. it is a way to easily exit an application

- ### Suspending Processes
![image](https://github.com/user-attachments/assets/4cc9e797-a9e6-41c5-ba3f-86d75e0d46c9)
Using  `Ctrl-Z` suspends a process and allows u to run it again.

- ### Resuming Processes
![image](https://github.com/user-attachments/assets/064402a6-288c-4551-9ab1-86d4a25c5eed)
Using `fg` resumes any suspended processes.

- ### Backgrounding Processes
![image](https://github.com/user-attachments/assets/ba598124-fa9e-4717-ab41-913403382414)
![image](https://github.com/user-attachments/assets/b42f802c-9cd1-4567-8bb6-ece3faa948d9)
As we did before, `fg` resumes a suspended process but in the foreground. Here we use `bg` to resume the suspended process in the background.

- ### Foregrounding Processes
![image](https://github.com/user-attachments/assets/259783ef-50d4-43f0-a0db-8c0d8c877310)
Multiple step process where we foreground a backgrounded process.

- ### Starting Backgrounded Processes
![image](https://github.com/user-attachments/assets/21ba300b-56d3-4c5d-ad78-5a6876cd2811)
New method of directly backgrounding processes without first suspending them by appending an `&` to the process.

- ### Process Exit Codes
![image](https://github.com/user-attachments/assets/5481f3c8-bc53-4aba-8e84-2be36d3d6cac)
Echoing `&?` gives the **exit value** of a process after it terminates. We used this exit value to get the flag.
