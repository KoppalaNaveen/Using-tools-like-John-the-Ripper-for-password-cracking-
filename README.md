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
Password Cracking with John the Ripper

## OUTPUT:
Cracked Passwords from Hash File

* Create an Text file and name the text file(eg: srikrishna.txt).
 1. Right-click on the Desktop and choose Create Document → Empty Document.
 2. Name the file: krishna.txt.
<img width="353" alt="image" src="https://github.com/user-attachments/assets/fd1e2fa5-9b8d-4238-8dc4-4e1f3f457e49" />

3. Open it and right the below mentioned line in it.

  
![Screenshot 2025-04-26 151041](https://github.com/user-attachments/assets/37f92e8e-926f-4aca-80bc-06736f4f4799)

4. Save and close the file.




* Create a Password-Protected ZIP File
1. Right-click on krishna.txt → Create Archive.
<img width="419" alt="image" src="https://github.com/user-attachments/assets/5feaafe4-24b5-4865-b528-1b139154ab30" />

2. Select .zip format.
3. Click Other Options, set a password (e.g., 1234), then click Create.
4. A file named praveen.txt.zip will appear.



* Open the John-The-Ripper-Tool
1. Click on the Kali menu or press the Super (Windows) key.
2. Search for “john” and click it — this opens the terminal with John the
   Ripper installed.
![Screenshot 2025-04-26 132841](https://github.com/user-attachments/assets/a1fc6849-b94d-443b-94a8-19de902f53af)

3. Or simply open a Terminal from the dock or desktop.

* Navigate to the File Location:
1. In the terminal, switch to the Desktop where the ZIP file is located:
   <img width="474" alt="image" src="https://github.com/user-attachments/assets/0be0897f-7140-4c94-9a39-518232121bfc" />

* Confirm the ZIP File is Present
  1. Run: “ls” command
  2. You should see krishna.txt.zip listed.
  <img width="472" alt="image" src="https://github.com/user-attachments/assets/2ff463e8-c480-4321-af24-d24ae0d47d53" />

* Generate Hash Using zip2john:
 1. Execute:
  <img width="478" alt="image" src="https://github.com/user-attachments/assets/810412e0-a87b-4f44-8792-c23af58f4c9c" />

 * Verify the Hash File (Optional)
 1. Open hash.txt to ensure it contains the hash line.
 <img width="330" alt="image" src="https://github.com/user-attachments/assets/7a942acb-07e9-451a-addf-c31f3978aef1" />

* Start Cracking the Password:
1. Run:
<img width="473" alt="image" src="https://github.com/user-attachments/assets/05633d2a-3eb9-4f16-a880-8b1ce49fca8a" />

* View the Cracked Password:
1. After cracking is complete, reveal the password using:
<img width="476" alt="image" src="https://github.com/user-attachments/assets/c3f94eab-a8cb-4f34-b5aa-c21ae256a51c" />


## RESULT:
The password hashes were successfully cracked using John the Ripper.

