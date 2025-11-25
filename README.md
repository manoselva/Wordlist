# 🗂️ Wordlists Collection

A curated collection of high-quality wordlists for **directory brute-forcing**, **parameter fuzzing**, and **subdomain enumeration**.
Useful for tools like `dirsearch`, `ffuf`, `gobuster`, `feroxbuster`, `subfinder`, and others.

---

## 📁 General Wordlists

### 🔹 General Directory Bruteforce

*[https://raw.githubusercontent.com/maurosoria/dirsearch/master/db/dicc.txt](https://raw.githubusercontent.com/maurosoria/dirsearch/master/db/dicc.txt)

---

## 🧩 Language-Specific Wordlists

### 🟦 PHP Applications

*   [https://wordlists-cdn.assetnote.io/data/automated/httparchive_php_2020_11_18.txt](https://wordlists-cdn.assetnote.io/data/automated/httparchive_php_2020_11_18.txt)

### 🟩 ASP / ASPX / CFM / SVC / ASHX / ASMX

* [https://wordlists-cdn.assetnote.io/data/automated/httparchive_aspx_asp_cfm_svc_ashx_asmx_2020_11_18.txt](https://wordlists-cdn.assetnote.io/data/automated/httparchive_aspx_asp_cfm_svc_ashx_asmx_2020_11_18.txt)

### ☕ Java Applications

* [https://wordlists-cdn.assetnote.io/data/automated/httparchive_jsp_jspa_do_action_2022_08_28.txt](https://wordlists-cdn.assetnote.io/data/automated/httparchive_jsp_jspa_do_action_2022_08_28.txt)

---

## 🔧 Parameters Wordlists

### 🏷️ Top Parameters from 1M Websites

*[https://wordlists-cdn.assetnote.io/data/automated/httparchive_parameters_top_1m_2020_11_21.txt](https://wordlists-cdn.assetnote.io/data/automated/httparchive_parameters_top_1m_2020_11_21.txt)

---

## 🌐 Subdomain Enumeration

### 🧭 Subdomain Brute-Force

* [https://wordlists-cdn.assetnote.io/data/automated/httparchive_subdomains_2020_11_18.txt](https://wordlists-cdn.assetnote.io/data/automated/httparchive_subdomains_2020_11_18.txt)

---

## ⭐ Usage Example (ffuf)

```bash
ffuf -w wordlists/dicc.txt -u https://target/FUZZ -mc 200,302,401,403 -c
```

