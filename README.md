
# 🔐 Simple Hash Cracker

A basic Python script that attempts to crack hashed passwords using a wordlist and common hashing algorithms.

## 🛠 Supported Hash Types
- MD5
- SHA1
- SHA256

## 💻 How to Use

1. Clone the repository or download the script.
2. Run the script in your terminal:

```bash
python hash_cracker.py
```

3. Enter:
- The hash to crack
- The path to your wordlist (example: `wordlist.txt`)
- The hash type (md5/sha1/sha256)

## 📄 Example

```
Enter the hash to crack: 482c811da5d5b4bc6d497ffa98491e38
Enter path to wordlist: wordlist.txt
Enter hash type (md5/sha1/sha256): md5
[+] Password found: password123
```

## 📁 Files
- `hash_cracker.py`: The main cracking script
- `wordlist.txt`: A basic sample wordlist (for demo only)

## ⚠️ Disclaimer
This tool is for **educational purposes only**. Do not use against systems or data without permission.

## 🧠 What You Learn
- Basics of password hashing
- Brute-force cracking logic
- Ethical hacking principles
- Python scripting with `hashlib`
