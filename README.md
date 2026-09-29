**NetworkWalks Week 3 – Password Cracking with JTR & NetworkWalks Tools**

**Project Overview**

This project documents my Week 3 hands-on cybersecurity lab focused on password cracking. The objective was to recover the password of a protected PDF file (`My Locked PDF1.pdf`) using two different sets of tools: John the Ripper (JTR) with Johnny GUI, and the NetworkWalks Hash Calculator/Password Cracker.

**Tools Used**

- John the Ripper (JTR)
- Johnny (GUI for John the Ripper)
- NetworkWalks Hash Calculator
- NetworkWalks Password Cracker
- Online PDF hash extractor (pdf2john)

**Module 1: Password Cracking with JTR**

Tasks Completed

1. Downloaded and extracted John the Ripper on Windows.
2. Downloaded and installed Johnny GUI.
3. Linked Johnny to the John the Ripper executable (john.exe).
4. Extracted the password hash from the protected PDF using an online pdf2john tool.
5. Saved the hash in a text file (hash1.txt).
6. Loaded the hash file into Johnny and started the attack.
7. Successfully cracked the password and opened the PDF.

**Module 2: Password Cracking with NetworkWalks Tools**

Tasks Completed

1. Uploaded the protected PDF to the NetworkWalks Hash Calculator to extract its hash.
2. Copied the extracted `$pdf$...` hash.
3. Pasted the hash into the NetworkWalks Password Cracker.
4. Ran a dictionary attack against the hash.
5. Successfully cracked the password and opened the PDF.

**Password Cracked**

```
good-luck
```

**Flag Captured**

```
Nw{cybersecurity_flag_captured_2608}
```

**What I Learned**

Through this exercise, I gained practical experience with:

- Extracting password hashes from protected PDF files.
- Using John the Ripper and its Johnny GUI for offline password cracking.
- Using browser-based cracking tools as an alternative to command-line tools.
- Understanding dictionary attacks and wordlists.
- Recognizing how weak or common passwords can be cracked quickly.

**Evidence**

This repository contains screenshots showing the hash extraction, the cracking process, and the successfully unlocked PDF for both modules.

**Conclusion**

The Week 3 lab was successfully completed. The password of the protected PDF was recovered using both John the Ripper/Johnny and the NetworkWalks Hash Calculator/Password Cracker, confirming the same weak password in both cases and reinforcing the importance of strong password practices.

#Cybersecurity #PasswordCracking #JohnTheRipper #NetworkWalks #EthicalHacking

