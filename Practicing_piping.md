# cryptonite_taskphase1_anna
## Module 6 : Practicing Piping

- ### Redirecting output
![image](https://github.com/user-attachments/assets/6f13fac0-a217-48cd-8e27-4710f7b7312d)
Using `>` to redirect the output **PWN** to the **COLLEGE** file

- ### Redirecting more output
![image](https://github.com/user-attachments/assets/6650a0c5-b550-4151-8cbd-5736e40b985d)
Here, we redirect the output of `/challenge/run` which is the flag, to the file **myflag**

- ### Appending output
![image](https://github.com/user-attachments/assets/e4638333-e19f-442b-a058-c93dd36e825f)
![image](https://github.com/user-attachments/assets/fbfd5395-6ec2-4bbe-a157-da03fdaaae3d)
Here, `/challenge/run` writes the first half of the flag directly to the file when using `>`. For the second half, we need to use `>>` to append the second half into the same file.

- ### Redirecting errors
![image](https://github.com/user-attachments/assets/97fbcbee-b675-42e3-9452-f171224a1b63)
In this challenge, we redirected the instructions of the `/challenge/run` command to the **instructions** file and the output to the **myflag** file, giving us the flag.

- ### Redirecting input
![image](https://github.com/user-attachments/assets/8013893d-5668-40cd-9725-3291ad9ac07f)
First we redirect the ouput **CHALLENGE** into the **PWN** file. This file input is then redirected to `/challenge/run` by using `<`

- ### Grepping stored results
