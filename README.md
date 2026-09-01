# Using-tools-like-John-the-Ripper-for-password-cracking

## AIM:
To crack password hashes using John the Ripper in Kali Linux.

## DESIGN STEPS:
### Step 1:
Install John the Ripper using the command:

### Step 2:
Prepare the password hash file (e.g., using unshadow for Linux password and shadow files).

### Step 3:
Use John the Ripper to crack the hashes:

## PROGRAM:

- **Install the John Ripper**
  ```bash
  sudo apt install john
  ```
- **Create a Password-Protected ZIP File**
   Archive a normal file (secret.txt) into a password-protected ZIP file
   ```bash
   zip --password 123abc secret.txt.zip secret.txt
   ```
 - **Extract the Hash from the ZIP File**
   ```bash
   zip2john secret.txt.zip > zip_hash.txt
   ```
- **Crack the ZIP Password using John**
  ```bash
  john --format=zip zip_hash.txt
  ```
- **Show the Cracked Password**
  ```bash
  john --show zip_hash.txt
  ```


## OUTPUT:

### Create a Password-Protected ZIP File
![image](https://github.com/user-attachments/assets/38aafaf5-1e19-437e-b081-e65d7b87faaf)


### Extract the Hash from the ZIP File
![1](https://github.com/user-attachments/assets/f56d14b3-308b-46d1-a881-2949f3130fbf)

### Crack the ZIP Password using John
![2](https://github.com/user-attachments/assets/b5150b03-086b-4a42-b23c-6f6c2e19dea4)

![Screenshot 2025-04-25 130110](https://github.com/user-attachments/assets/e6726360-d5ea-44d2-8564-0e428a49a5d8)

### Show the Cracked Password
![Screenshot 2025-04-25 130116](https://github.com/user-attachments/assets/e212ed80-74a0-4532-ba3e-6bd015cde111)


## RESULT:
The password hashes were successfully cracked using John the Ripper.

