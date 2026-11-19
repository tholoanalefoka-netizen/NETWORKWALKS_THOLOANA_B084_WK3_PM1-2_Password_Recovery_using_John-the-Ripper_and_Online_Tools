# NETWORKWALKS_Password_Recovery_using_John-the-Ripper_and_Online_Tools

##  Intern Details

| Field | Value |
|---|---|
| **Name** |Tholoana Jeanet Lefoka |
| **Intern ID** |NW-084-2RV |
| **Batch** | B084 |
| **Modules** | W3-PM1 (John the Ripper) · W3-PM2 (Free Online Tools) |
| **Topic** | Password Recovery / Password Cracking |

## Disclaimer

The contents of this repository, including all files, demonstrations, and documentation related to password recovery and cracking, are provided **strictly for educational and research purposes**.

* **Authorized Use Only:** All tools and techniques demonstrated in this project were performed in a controlled environment on files for which explicit and full permission was granted by the owner.
  
* **No Malicious Intent:** There was absolutely no intent to cause harm, exploit vulnerabilities, or compromise any systems, networks, or personal data.
  
* **Limitation of Liability:** Neither the author nor **Network Walks** accept any responsibility or liability for any misuse, damage, or illegal activities that may arise from the application of the information or tools provided in this repository.

By reading or using the contents of this repository, you agree that you are solely responsible for your own actions and must always obtain proper, legal authorization before attempting any security testing or password recovery on systems or files you do not own.

## Tools used
1. John The Ripper
2. Online Hash Crack
3. Networkwalks Hash Calculator
4. Networkwalks Password Cracker

## Tasks Performed

### Task 1: Installation and Configuration of John the Ripper (Johnny GUI)
I used Kali Linux for this task and discovered that John The Ripper exists as CLI so I had to install the GUI using the command  -> sudo apt udpate && sudo apt install johnny -y. 

### Task 2: Password Hash Identification and Cracking (Johnny)
1. I first extracted the hash values for the pdf files, My Locked PDF1.pdf and My Locked PD2.pdf.
2. I then created the hash files named hash_value.txt and hash_value2.txt and saved the hash values for each file accordingly.
3. Uploaded the each hash file into Johnny and initiated the password recovery.
4. To verify that the passwords "good-luck" and "password1" are correct, I used them on the files and captured the flags "  
nw{networkwalks_persistence_jtr_270521}" and "nw{cybersecurity_flag_captured_2608}".

### Task 3: Password Cracking Using Networkwalks Tools
1. I used the **Networkwalks Hash Calculator** to parse the encrypted PDF locally and extract the crackable hash.

2. I ran **Networkwalks Password Cracker** to perform dictionary-based password recovery.
   
3. I used the password to capture the flags " nw{networkwalks_flag1_jtr_270521_1}" and "nw{networkwalks_flag_260821_1}".

## Lesson Outcome
i learned how to use different password recovery tools, gained hands-on experience in distinguishing between file decryption and password hash cracking and understood how weak passwords leave sensitive documents vulnerable and why robust password policies are essential.
