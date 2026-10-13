# Marxalad 3 · Barnaamijyada — Python & Bash

> Cybersecurity-ga koodhka waa luuqadda labaad. Adigoo qoraya scripts-yar, waxaad otomaatig ka dhigi kartaa hawsha aad gacanta ku qaban lahayd saacado. Python ayaa ah luuqadda ugu isticmaalka badan amniga.

---

## 🎯 Hadaf
Baro aasaaska Python (iyo Bash) si aad u qorto scripts hubinta iyo otomaatiga.

## 📚 Waxa La Barta

| Mawduuc | Waxa aad baranaysaa |
|---|---|
| Python aasaas | Variables, types (`int`, `str`, `list`, `dict`), input/output |
| Xakamaynta socodka | `if/else`, `for`, `while` |
| Hawlaha (functions) | `def`, arguments, return |
| Faylasha | Akhriska iyo qorista faylasha (`open`) |
| Modules | `import`, standard library |
| Hawlaha security-ga | `requests` (HTTP codsiyada), `socket` (shabakadda), `os`/`subprocess` |
| Bash scripting | Sheeko-yar, loops, cron basics |
| JavaScript (hoos) | HTML/JS basics — arag Marxalad 4 |

**Tusaale — port scanner yar (Python):**
```python
import socket

host = "example.com"
for port in [80, 443, 22, 8080]:
    s = socket.socket()
    s.settimeout(1)
    result = s.connect_ex((host, port))
    if result == 0:
        print(f"Port {port}: FURAN")
    s.close()
```
Kan waa hawsha ugu horeysa ee aad ku baranayso!

## 🔗 Agab (Bilaash)

| Agab | Waxa ay tahay | Link |
|---|---|---|
| **freeCodeCamp — Python** | Kursus buuxa (4 saac) | [youtube.com/watch?v=rfscVS0vtbw](https://www.youtube.com/watch?v=rfscVS0vtbw) |
| **Automate the Boring Stuff** | Buug bilaash online | [automatetheboringstuff.com](https://automatetheboringstuff.com) |
| **Python.org — Tutorial** | Buug rasmiga ah | [docs.python.org/3/tutorial](https://docs.python.org/3/tutorial/) |
| **Codecademy — Python** | Interactive (bilaash aasaas) | [codecademy.com/learn/learn-python-3](https://www.codecademy.com/learn/learn-python-3) |
| **CS50 (Harvard)** | Kursus jaamacad bilaash (optional) | [cs50.harvard.edu/x](https://cs50.harvard.edu/x/) |

## ✅ Liiska Hubinta

- [ ] Waan qoray script Python ah oo variables, loops, iyo functions isticmaasho
- [ ] Waan akhriyay oo qoray fayl Python ah
- [ ] Waan isticmaalay `requests` oo aan soo dhigay bog web
- [ ] Waan qoray **port scanner** (sida tusaalaha kore)
- [ ] Waan garanayaa Bash script aasaasiga ah
- [ ] Waan fahmay sida `pip` loo isticmaalo (`pip install requests`)

## ⏱️ Waqti La Qiyaaso
4-6 toddobaad (hal saac maalintii) — ha degdeg: koodhka barashadu waqti ayay qaadataa

## 🏁 Imtixaanka (Milestone)

**Qor tool yar oo dhab ah:** port scanner, ama password generator, ama HTTP header checker. Ku dhig GitHub-kaaga (waxaa hore u baahan tahay akoon GitHub) — kan waa bilowga portfolio-gaaga!

→ Xig: [05-amniga-web-ka.md](05-amniga-web-ka.md)
