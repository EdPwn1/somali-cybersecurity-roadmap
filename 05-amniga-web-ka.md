# Marxalad 4 · Amniga Web-ka (Web Security)

> Marxaladda ugu weyn! Web-ka ayaa ah barwaaqada ugu ballaaran ee dhaawacyada amniga. Halkan waxaad baranaysaa OWASP Top 10, Burp Suite, iyo dhammaan dhaawacyada web-ka — adigoo ku dhaqmayo lab-yada caalamka ugu fiican.

---

## 🎯 Hadaf
Hel, faham, iyo faaiidee dhaawacyada web-ka (SQLi, XSS, IDOR, iwm) — adigoo isticmaalaya Burp Suite.

## 📚 Waxa La Barta

### Aasaaska web-ka (marka hore)
- HTTP dib u fiiri: methods, status codes, headers, cookies, sessions
- HTML/JS aasaas: DOM, forms
- Sida web-ka uu u shaqeeyo: client (browser) → server → database

### OWASP Top 10 (dhaawacyada waaweyn)
| # | Dhaawaca | Waa maxay (hal sadar) |
|---|---|---|
| 1 | **Broken Access Control** (IDOR) | beddel ID → hel xogta qof kale |
| 2 | **Cryptographic Failures** | xog la aamini la'aan |
| 3 | **Injection** (SQLi, XSS) | input-ka oo query/koodh noqda |
| 4 | **Insecure Design** | naqshad dhaawac leh |
| 5 | **Security Misconfiguration** | hab habboon la'aan |
| 6 | **Vulnerable Components** | libs duq ah |
| 7 | **Auth Failures** | login/reset/MFA daciif |
| 8 | **Data Integrity** | xog la beddeli karo |
| 9 | **Logging Failures** | la soodegin khaladaadka |
| 10 | **SSRF** | server-ka oo URL-kaaga soo qaada |

### Qalabyada
- **Burp Suite** (Community, bilaash) — qalabka #1
- Browser DevTools (Network tab)
- DVWA, OWASP Juice Shop (lab-yada)

## 🔗 Agab (Bilaash)

| Agab | Waxa ay tahay | Link |
|---|---|---|
| **PortSwigger Web Security Academy** | **AH KHASAARA MA LIHI** — lab-yada ugu fiican dunida | [portswigger.net/web-security](https://portswigger.net/web-security) |
| **OWASP Top 10** | Liiska rasmiga ah | [owasp.org/Top10](https://owasp.org/Top10/) |
| **TryHackMe — Web Fundamentals** | Path buuxa | [tryhackme.com/path/outline/web](https://tryhackme.com/path/outline/web) |
| **DVWA** | Lab abka dhaawaca leh | [github.com/digininja/DVWA](https://github.com/digininja/DVWA) |
| **OWASP Juice Shop** | Lab casri ah | [owasp.org/www-project-juice-shop](https://owasp.org/www-project-juice-shop/) |
| **NahamSec — YouTube** | Bug bounty dhab ah | [youtube.com/@NahamSec](https://www.youtube.com/@NahamSec) |
| **STÖK — YouTube** | Fikirka bounty-ga | [youtube.com/@stokfredrik](https://www.youtube.com/@stokfredrik) |

**Habka shaqada:**
1. Fur Burp Suite → Proxy → Intercept (ku dar browser-ka)
2. Fur DVWA ama Juice Shop (`docker run --rm -p 3000:3000 bkimminich/juice-shop`)
3. PortSwigger lab-yada: bilow **SQL injection** pathway → kadib **XSS** → kadib **Access control**

## ✅ Liiska Hubinta

- [ ] Waan isticmaalay Burp Suite (Intercept + Repeater)
- [ ] Waan fahmay HTTP codsiyada iyo jawaabaha buuxa
- [ ] Waan dhammaystiray PortSwigger SQL injection labs (Apprentice, dhammaan)
- [ ] Waan dhammaystiray PortSwigger XSS labs
- [ ] Waan dhammaystiray Access control labs (IDOR!)
- [ ] Waan helay dhaawac hal ah lab-ka Juice Shop ama DVWA

## ⏱️ Waqti La Qiyaaso
8-12 toddobaad (hal saac maalintii) — marxaladda ugu dheer, sababtoo ah waa wadnaha xirfadda

## 🏁 Imtixaanka (Milestone)

**Dhammaystir PortSwigger pathways:** SQL injection + XSS + Access control + Authentication (Apprentice level, dhammaan lab-yada). Ka dib dhig lab-yada DVWA hal hal. Haddii aad karto — **waad noqotay qof web security aqoon u leh!**

→ Xig: [06-amniga-shabakadda.md](06-amniga-shabakadda.md)
