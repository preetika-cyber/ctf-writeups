# The Inner Circle
**Category:** Web  
**Points:** 400  

---

## 🧩 Description  
It prints exactly what you send… or at least, that’s what it looks like

---

## 🎯 Target  
- **URL:** https://chall5.shellpwn.tech  

---

## 🎯 Approach  

This challenge involves identifying and exploiting a **Server-Side Template Injection (SSTI)** vulnerability.

---

## 🛠️ Steps  

1. Interact with the input field on the website  
2. Send test inputs to observe response behavior  
3. Intercept requests using **Burp Suite**  
4. Identify that user input is being processed by a template engine  
5. Modify the input to execute server-side expressions  
6. Retrieve the flag from the server response  

---

## 🏁 Flag  
SH3LL{sst1_3x3cut10n_m4st3r}

---

## 🧠 Key Learning  

- SSTI can lead to remote code execution  
- Always validate and sanitize user input in templates  
