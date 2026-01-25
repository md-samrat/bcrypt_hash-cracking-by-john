# bcrypt Password Cracking Practice (John the Ripper)

This repository demonstrates a **learning lab** focused on cracking **bcrypt** password hashes using **John the Ripper** with the **RockYou wordlist** and rules.

**Ethical Use Only**  
All techniques shown here are strictly for:
- Personal practice labs
- Educational purposes
- CTF and authorized environments  

Do NOT use these techniques on real systems without permission.

---

## Usage

```bash
git clone https://github.com/samrat-xyz/bcrypt_hash-cracking.git
cd bcrypt_hash-cracking
john --format=bcrypt --wordlist=/usr/share/wordlists/rockyou.txt --rules bcrypt_hash.txt
john --format=bcrypt --show bcrypt_hash.txt


