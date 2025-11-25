## 📁 General Wordlists

| Category              | Wordlist                                                                                                                                               |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Directory Bruteforce  | [https://raw.githubusercontent.com/maurosoria/dirsearch/master/db/dicc.txt](https://raw.githubusercontent.com/maurosoria/dirsearch/master/db/dicc.txt) |
| General Wordlists Hub | [https://wordlists.assetnote.io/](https://wordlists.assetnote.io/)                                                                                     |

---

## 🧩 Language-Specific Wordlists

| Language / Stack                     | Wordlist                                                                                                                                                                                                           |
| ------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| PHP                                  | [https://wordlists-cdn.assetnote.io/data/automated/httparchive_php_2020_11_18.txt](https://wordlists-cdn.assetnote.io/data/automated/httparchive_php_2020_11_18.txt)                                               |
| ASP / ASPX / CFM / SVC / ASHX / ASMX | [https://wordlists-cdn.assetnote.io/data/automated/httparchive_aspx_asp_cfm_svc_ashx_asmx_2020_11_18.txt](https://wordlists-cdn.assetnote.io/data/automated/httparchive_aspx_asp_cfm_svc_ashx_asmx_2020_11_18.txt) |
| Java                                 | [https://wordlists-cdn.assetnote.io/data/automated/httparchive_jsp_jspa_do_action_2022_08_28.txt](https://wordlists-cdn.assetnote.io/data/automated/httparchive_jsp_jspa_do_action_2022_08_28.txt)                 |

---

## 🔧 Parameters Wordlists

| Description                     | Wordlist                                                                                                                                                                                         |
| ------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Top Parameters from 1M Websites | [https://wordlists-cdn.assetnote.io/data/automated/httparchive_parameters_top_1m_2020_11_21.txt](https://wordlists-cdn.assetnote.io/data/automated/httparchive_parameters_top_1m_2020_11_21.txt) |

---

## 🌐 Subdomain Enumeration

| Category                                 | Wordlist                                                                                                                                                                           |
| ---------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Subdomain Brute-Force                    | [https://wordlists-cdn.assetnote.io/data/automated/httparchive_subdomains_2020_11_18.txt](https://wordlists-cdn.assetnote.io/data/automated/httparchive_subdomains_2020_11_18.txt) |
| Best DNS Wordlist                        | [https://wordlists-cdn.assetnote.io/data/manual/best-dns-wordlist.txt](https://wordlists-cdn.assetnote.io/data/manual/best-dns-wordlist.txt)                                       |
| SAML / Subdomain Dictionaries Collection | [https://github.com/the-xentropy/samlists](https://github.com/the-xentropy/samlists)                                                                                               |

---

## ⭐ ffuf Example

```bash
ffuf -w wordlists/dicc.txt -u https://target/FUZZ -mc 200,302,401,403 -c
```
