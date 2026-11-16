🛡️ Password Cracking & Hash Extraction Lab (W3-PM2)

Author Details

- Author: Relebogile Majatladi
- Role: Cybersecurity Intern
- Programme: Networkwalks Academy
- Task Batch: B084
- Lab: Week 3 – W3-PM2
- LinkedIn: https://www.linkedin.com/in/bethuel-ntsetse-majatladi

📌 Project Overview

This project documents my completion of the Networkwalks Academy Week 3 Password Cracking Lab.

The objective was to understand how password-protected PDF files can be assessed by extracting cryptographic hashes and performing dictionary-based password attacks in an authorised training environment.

The exercise also demonstrated the importance of using strong passwords to protect sensitive information.

🛠️ Tools & Technologies Used

- Networkwalks Hash Calculator: Used to extract PDF password hashes.
- Networkwalks Password Cracker: Used to perform dictionary-based password testing.
- 7-Zip: Used to extract compressed wordlist files.
- Notepad: Used to create a custom wordlist.
- RockYou Wordlist: Used to understand dictionary-based password testing.

🔍 Methodology

1. Hash Extraction

- Uploaded the provided encrypted PDF files to the Networkwalks Hash Calculator.
- Extracted the password hashes beginning with "$pdf$".
- Prepared the hashes for dictionary-based password testing.

2. Dictionary Attack

- Tested the default wordlist against the first PDF.
- Explored the RockYou wordlist containing millions of password entries.
- Experienced performance limitations when processing a large wordlist in the browser.
- Created a smaller custom wordlist to improve testing efficiency.

3. Password Recovery

The following passwords were successfully recovered during the authorised lab exercise:

Target File| Recovered Password
My Locked PDF1.pdf| "good-luck"
My Locked PDF1 (for NW Tools Lab WK3-PM2).pdf| "password1"

4. Verification

Successfully unlocked the first PDF and retrieved the lab verification flag.

Flag 1:
"nw{networkwalks_flag1_jtr_270521_1}"

The second PDF was also successfully unlocked to complete the verification exercise.

💡 Key Learnings

Through this practical exercise, I learned:

- How password hashes are extracted from encrypted PDF documents.
- How dictionary attacks work.
- How wordlists such as RockYou are used in password security testing.
- How to create custom wordlists.
- Why large-scale password testing can be resource-intensive.
- Why weak and predictable passwords create security risks.

🔐 Security Recommendations

- Use long, unique passwords or passphrases.
- Avoid common passwords and predictable patterns.
- Use strong encryption when protecting sensitive documents.
- Apply additional security controls when sharing confidential files.

📸 Screenshots

Screenshots of the lab setup, hash extraction, password testing and successful verification will be added to document the practical work.

⚠️ Disclaimer

This exercise was completed in an authorised cybersecurity training environment as part of the Networkwalks Academy internship. All testing was conducted on provided lab materials for educational purposes.

---

Week 3 Completed | Networkwalks Academy | B084
