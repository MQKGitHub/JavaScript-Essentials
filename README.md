### 🛡️ JavaScript Essentials

**Room:** [JavaScript Essentials — TryHackMe](https://tryhackme.com/room/javascriptessentials)  
**Status:** ✅ Completed  
**Date:** *04 June 2025*  

### 🎯 Objective  
Learn the fundamentals of JavaScript, how it's integrated into HTML, how its functionality can be abused by attackers, and how to apply best practices to develop secure, interactive websites.  

---  

### 🗝️ Key Concepts  
- **JavaScript (JS)** — A scripting language used to make websites interactive (e.g. form validation, user interaction).  
- **Variables (var, let, const)** — Containers to store data, each with different scope behaviour.  
- **Data Types** — JS supports strings, numbers, booleans, null, undefined, and objects.  
- **Functions** — Blocks of code used to perform tasks and reduce repetition.  
- **Loops** — Used to repeat tasks (e.g. `for`, `while`).  
- **Control Flow** — Uses `if`, `else`, `switch`, etc., to make decisions in code.  
- **Dialogue Functions** — `alert`, `prompt`, and `confirm` used for basic user interaction.  
- **Minified & Obfuscated JS** — Techniques to compress and hide JS logic, used for performance and sometimes protection.  
- **Security Risks** — JS can be abused by attackers (e.g. XSS, bypassing login checks, malicious scripts in emails).  
- **Best Practices** — Avoid hardcoded secrets, validate on server-side, don't trust external libraries blindly.

---  

### 🛠️ Tools Used  
- **Google Chrome Console** — Used to test and run JavaScript interactively.  
- **Pluma** — Text editor for editing HTML and JS files.  
- **Browser Inspector (DevTools)** — Used to view internal/external JS and source code.  
- **Online JS Obfuscator/Deobfuscator** — Tools to test minifying and obfuscating JS code.  

---  

### ⚠️ Challenges Faced  
- Following the obfuscated JS flow was tricky until using the deobfuscator tool.  
- Understanding how attackers can bypass simple control flow using prompts and how poor login logic can be abused took a bit of experimentation.  

---  

### 🧠 What I Learned  
- How to write, run, and debug simple JavaScript programs.  
- The importance of separating JS logic using external files for maintainability.  
- How JavaScript functions like `alert`, `prompt`, and `confirm` can be misused.  
- The basics of obfuscating JS and how it impacts code readability.  
- Why relying on client-side validation alone is insecure.  

---  

### 🌐 Real-World Application  
> JavaScript is everywhere on the web. Understanding how it's used (and abused) helps penetration testers spot client-side vulnerabilities, including XSS, logic flaws, and poor coding practices. Obfuscated JS is common in malware and phishing — being able to read or decode it is essential for investigation.

---  

### 💭 Reflections  
- It was fun using Chrome DevTools to interact with JS live — seeing immediate results helps learning stick.  
- The login bypass section was an eye-opener for how easy it is to fool poorly designed front-end validation.  
