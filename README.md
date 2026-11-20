# Locked PDF Password-Cracking With John The Ripper and NetworkWalks cracking tool

# PDF Password Cracking Using John the Ripper (JTR) and Network Walks

## 1. Project Overview

This practical exercise focused on learning how password recovery works using two approaches: **John the Ripper (JTR)** and **Network Walks online password-cracking tools**.

I was provided with four password-protected PDF files to work on. I successfully used John the Ripper to recover passwords for three of the PDF files. I also explored Network Walks' Hash Calculator and Password Cracker to understand an alternative password recovery process.

## 2. Tools Used

- **John the Ripper (JTR):** Password recovery and auditing tool.
- **Johnny:** Graphical user interface for John the Ripper.
- **John Extension File:** John executable (`john.exe`), linked to Johnny.
- **Network Walks Hash Calculator:** https://networkwalks.com/hash-calculator/
- **Network Walks Password Cracker:** https://networkwalks.com/password-cracker/
- **Notepad:** Used to save extracted password hashes in a TXT file.

## 3. Method One: Password Recovery Using John the Ripper

I used the following workflow to recover passwords from three of the four PDF files.

### Step 1: Installation and Configuration

- Downloaded and installed John the Ripper and Johnny.
- Extracted the John extension files.
- Opened Johnny and navigated to its settings.
- Located and linked the `john.exe` executable file to Johnny to enable the password recovery functionality.

### Step 2: Extracting the PDF Hash

- Opened the Hash Calculator.
- Uploaded the password-protected PDF file.
- Extracted the hash associated with the PDF.
- Copied the extracted hash into a new TXT file using Notepad.

- https://github.com/Clairion17/Password-Cracking-/blob/main/HASH%20EXTRACTOR.png

### Step 3: Loading the Hash into JTR

- Opened Johnny (JTR).
- Selected the option to open a new password file.
- Uploaded the TXT file containing the extracted hash.
- Initiated the password recovery process.

### Step 4: Password Recovery

- Started the password recovery attack.
- Allowed John the Ripper to process the hash.
- Retrieved the recovered password when the process was successful.

### Step 5: Unlocking the PDF

- Copied the recovered password.
- Opened the corresponding password-protected PDF.
- Entered the recovered password to gain access to the document.

https://github.com/Clairion17/Password-Cracking-/blob/main/LOCKED%20PDF%201.png

I repeated this process for three PDF files and successfully recovered their passwords.

https://github.com/Clairion17/Password-Cracking-/blob/main/CRACKED%20PASSWORD%202.png

https://github.com/Clairion17/Password-Cracking-/blob/main/CRACKED%20PDF%203.png

## 4. Method Two: Using Network Walks

I also explored an online alternative using Network Walks.

**Step 1: Hash Extraction**

Website: https://networkwalks.com/hash-calculator/

- Accessed the Network Walks Hash Calculator.
- Uploaded the locked PDF file.
- Used the tool to generate/extract its password hash.

- https://github.com/Clairion17/Password-Cracking-/blob/main/HASH%20CALCULATOR%20NW.png

**Step 2: Password Recovery**

Website: https://networkwalks.com/password-cracker/

- Accessed the Network Walks Password Cracker.
- Used the extracted hash in the password recovery workflow.
- Reviewed the result returned by the tool.

- https://github.com/Clairion17/Password-Cracking-/blob/main/PASSWORD%20CRACKER%20NW.png

- https://github.com/Clairion17/Password-Cracking-/blob/main/UNLOCKED%20WITH%20NW.png

## 5. Results and Learning Outcomes

The practical exercise provided hands-on exposure to password hashing and password recovery techniques.

Key lessons learned:

- How password-protected PDF files use password-based protection.
- How to extract password hashes for authorized security testing.
- How to configure Johnny to work with the John the Ripper executable.
- How to load hash files into a password auditing tool.
- How password recovery tools attempt to identify matching passwords.
- How online hash calculators and password recovery tools work as an alternative approach.

**Outcome:** Successfully recovered passwords for all four assigned PDF files using John the Ripper and networkwalks password cracking tools.

## 6. Conclusion

This exercise improved my practical understanding of password security, hash extraction, and password auditing. It also helped me become familiar with both command-line-based security tools and graphical interfaces.

The exercise reinforced the importance of using strong passwords and understanding how password protection can be assessed during authorized cybersecurity testing.

# Author- AMARACHUKWU SOPHIA ANAGBOR

*Note: All activities were conducted on assigned files for educational and authorized security-learning purposes.*
