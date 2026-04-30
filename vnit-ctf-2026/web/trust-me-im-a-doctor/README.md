# Trust Me, I’m a Doctor

**Category:** Web  
**Points:** 400  

---

## 🧩 Description  
The clinic follows a strict policy: no unnecessary checks, no delays, no second opinions. Every injection goes straight through.

---

## 🎯 Target  
- **URL:** https://chall4.shellpwn.tech  

---

## 🎯 Approach  

This challenge involves **NoSQL injection** to bypass authentication.

---

## 🛠️ Steps  

1. Identify the login functionality  
2. Intercept the request using **Burp Suite**  
3. Analyze how input is processed  
4. Modify the request to bypass validation logic  
5. Forward the request  

   ![](trust-me-i-am-doctor.jpeg)

6. Gain access and retrieve the flag  

---

## 🏁 Flag  
SH3LL{n0sql_1nj3ct10n_byp4ss_f0r_th3_w1n}

---

## 🧠 Key Learning  

- NoSQL databases are vulnerable to injection if not sanitized  
- Authentication bypass is a critical issue  
