# cryptonite_taskphase1_anna
## Module 9: Perceiving Permissions

- ### Changing File Ownership
![image](https://github.com/user-attachments/assets/db98912b-b0cb-45a6-b49d-a854087f826a)
![image](https://github.com/user-attachments/assets/923d8ea6-5d5a-4dd2-aea2-2cebb12d251b)
`chown` lets u change the ownership of a file so that a user other than **root** can access it, just like we did with the flag file here

- ### Groups and Files
![image](https://github.com/user-attachments/assets/c103393e-672f-4a7e-9c5a-1cea9b62126d)
`chgrp` similar to `chown` but changes group instead of owner

- ### Fun with Groups Names
![image](https://github.com/user-attachments/assets/700a33eb-b85d-42c5-a929-fc2821eb69c4)

- ### Changing Permissions
![image](https://github.com/user-attachments/assets/edac932c-2bdd-4f05-a9b4-4d30f126b268)
This was a bit confusing to understand, mainly the multiple combinations of modes. `u,g,o` stand for `user,group,other` or the **WHO** while `r,w,x` stand for `read,write,execute` or the **WHAT**.

- ### Executable Files
![image](https://github.com/user-attachments/assets/741502af-0138-43ff-b381-8af9b58df942)
Changing the execution permission on the `/challenge/run` program.

- ### Permission Tweaking Practice
![image](https://github.com/user-attachments/assets/90715bca-1d96-4b60-9367-6e82edca5d13)
![image](https://github.com/user-attachments/assets/db7afcfb-819b-4a69-9b1a-b64b93691d99)
![image](https://github.com/user-attachments/assets/27b0277a-a092-4cb7-aa18-56f5727db066)
![image](https://github.com/user-attachments/assets/2014597b-70b1-4590-81f6-a54922f68013)
![image](https://github.com/user-attachments/assets/42de4de3-d9f5-43ff-946f-c513126e7625)
![image](https://github.com/user-attachments/assets/7540aeae-54fe-4f48-9043-47f3948ae332)
![image](https://github.com/user-attachments/assets/98180083-c4ff-4b8a-ace5-5c6928a87fd8)
![image](https://github.com/user-attachments/assets/7016ccd1-49ab-4727-a93a-b4e3a702e31d)
![image](https://github.com/user-attachments/assets/edf7047e-5fd3-4759-b4bf-754037b1564f)
![image](https://github.com/user-attachments/assets/3e3d1c4d-feb1-4587-873e-df4dbcb001d4)

- ### Permissions Setting Practice
![image](https://github.com/user-attachments/assets/bcac0cb9-9c96-40dd-9e4a-ce9a5a68bc75)
![image](https://github.com/user-attachments/assets/3fa668d8-0fda-4c8a-b34a-a84a728ef27a)
![image](https://github.com/user-attachments/assets/cba79a5b-4a2c-4edf-a4dd-4208b70b18bd)
![image](https://github.com/user-attachments/assets/c1d8557f-55b1-47b9-afef-6908ab4c98fe)
![image](https://github.com/user-attachments/assets/b2d29082-8c7e-453c-a088-e886067c2278)
![image](https://github.com/user-attachments/assets/bde63aca-ebc4-44ee-8e2b-c5e09c8a6949)
![image](https://github.com/user-attachments/assets/21292d4f-8357-4b4a-8620-3ea3ab724b22)
![image](https://github.com/user-attachments/assets/27c21778-c501-416c-9b6d-623e48760eea)
![image](https://github.com/user-attachments/assets/b8a94508-9643-40b0-817a-00d8b102de19)
Using `=` to overwrite the existing permissions

- ### The SUID Bit
![image](https://github.com/user-attachments/assets/8d53783d-8355-4541-82e8-e84b1e02428e)
