# Castor

**Category:** Misc  
**Points:** 100  

---

## 🧩 Description  
Decrypting this cipher has to do with the twin of the Greek God with the same name as the challenge title...

---

## 🎯 Approach  

This challenge uses **Pollux Cipher (Morse variant)**.

---

## 🛠️ Steps  

1. Map digits:
   - Odd primes → `.`
   - Perfect squares → `-`
   - Others → separator  

2. Convert to Morse  

📊 Conversion Table  

| Numeric Ciphertext | Morse Symbols | Separator |
|------------------|--------------|----------|
| 1345             | -.-.         | (x)      |
| 73579            | ....-        | (x)      |
| 357              | ...          | (x)      |
| 1                | -            | (x)      |
| 491              | ---          | (x)      |
| 543              | .-.          |          |

3. Decode Morse → text  

---

## 🏁 Flag
SHELL{c4stor}

---

## 🧠 Key Learning  

- Multi-layer ciphers require patience  
- Mathematical hints are important  

