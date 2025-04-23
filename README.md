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
- Create an txt file 

![alt text](<Screenshot 2025-04-23 110209.png>)

- Create a Password-Protected ZIP File 
```
zip -e messag.zip hidden.txt
```
![alt text](<Screenshot 2025-04-23 105801.png>)

![alt text](<Screenshot 2025-04-23 110235.png>)


- Open John-The-Ripper Tool

![alt text](<Screenshot 2025-04-23 111002.png>)

![alt text](<Screenshot 2025-04-23 105016.png>)

- Generate Hash Using zip2john
 
![alt text](<Screenshot 2025-04-23 105715.png>)

- cat hash.txt

![alt text](<Screenshot 2025-04-23 105722.png>)

![alt text](<Screenshot 2025-04-23 105744.png>)


## RESULT:
The password hashes were successfully cracked using John the Ripper.
