# cryptonite_taskphase1_anna
## Module 5: File Globbing

- ### Matching with *
![image](https://github.com/user-attachments/assets/c02f587b-0ae7-472a-99b2-7df0efcde368)
New concept of using `*` instead of the whole argument name. Here we replace '/challenge' with just '/*ge' while changing directories. Once it successfully goes to the right directory, run the correct command to get the flag.

- ### Matching with ?
![image](https://github.com/user-attachments/assets/41915b46-7c95-42c4-b270-5aa5bb851b49)
The `?` can be used in a similar way as `*` but instead it only matches one character. Hence we have used one ? for every missing character in `/challenge` to get into the right directory and get the flag.

- ### Matching with []
![image](https://github.com/user-attachments/assets/b76d8d55-8b8c-493c-9ac9-da1572882d04)
Using `[]` to glob multiple file names by using it as `file_[required characters]`

- ### Matching paths with []
![image](https://github.com/user-attachments/assets/46bc5df1-61eb-4131-b613-0f0d240bb8c6)
Same as before but using absolute paths while globbing with `[]`.

- ### Mixing globs
![image](https://github.com/user-attachments/assets/20db9050-22e6-470e-a549-648dd34ede45)
Using `[]` and `*` glob to get the file names.

- ### Exclusionary globbing
![image](https://github.com/user-attachments/assets/243ba81a-4604-4f0d-8dfb-1ec4ec297fd2)
Using `^` in the front of the characters in the `[]` glob to exclude those characters while looking in the file names.
