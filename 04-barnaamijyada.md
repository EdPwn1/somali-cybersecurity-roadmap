# Marxalad 3 · Barnaamij-samaynta — Python iyo Bash

> Barnaamij-samayntu waxay kuu sahlaysaa inaad hawlo soo noqnoqda otomaatig ka dhigto, xogta falanqayso, oo aad fahanto sida software-ku u shaqeeyo. Python ayaa ah meel wanaagsan oo laga bilaabo.

---

## 🎯 Hadaf

Baro aasaaska Python iyo Bash si aad u qori karto qoraallo yar-yar oo hawlo sharci ah kuu fududeeya.

## 📚 Mawduucyada la baranayo

| Mawduuc | Waxa aad baranayso |
|---|---|
| Python aasaasi ah | Variables, noocyada xogta (`int`, `str`, `list`, `dict`), gelin iyo soo-saar |
| Xakamaynta socodka | `if/else`, `for`, `while` |
| Functions | `def`, arguments iyo `return` |
| Faylasha | Akhrinta iyo qorista faylasha adigoo adeegsanaya `open` |
| Modules | `import` iyo maktabadaha Python |
| Codsiyada webka | `requests` si loo diro HTTP requests shaybaar la oggolaaday |
| Shabakadaha | `socket` aasaasi ah iyo fahamka xiriirrada |
| Bash | Amarada la isku xiro, variables iyo loops fudud |
| JavaScript | Aasaaska HTML/JS; waxay kaa caawinaysaa marxaladda webka |

### Tusaale waxbarasho: hubinta dekedo kooban oo shaybaar kuu gaar ah

Isticmaal tusaalahan oo keliya domain ama mashiin aad leedahay ama aad fasax u haysato inaad tijaabiso.

```python
import socket

host = "127.0.0.1"  # kombiyuutarkaaga; ku beddel oo keliya bartilmaameed fasax leh
for port in [80, 443, 22, 8080]:
    with socket.socket() as sock:
        sock.settimeout(1)
        result = sock.connect_ex((host, port))
        state = "furan" if result == 0 else "xiran ama aan la gaari karin"
        print(f"Dekedda {port}: {state}")
```

## 🔗 Agab bilaash ah

| Agab | Waxa uu bixinayo | Xiriiriye |
|---|---|---|
| **freeCodeCamp — Python** | Koorso muuqaal ah oo hordhac ilaa aasaas ah | [YouTube](https://www.youtube.com/watch?v=rfscVS0vtbw) |
| **Automate the Boring Stuff** | Buug online ah oo Python lagu barto | [automatetheboringstuff.com](https://automatetheboringstuff.com) |
| **Python.org — Tutorial** | Casharka rasmiga ah ee Python | [docs.python.org/3/tutorial](https://docs.python.org/3/tutorial/) |
| **Codecademy — Python** | Layliyo isdhexgal leh; qayb bilaash ah | [codecademy.com/learn/learn-python-3](https://www.codecademy.com/learn/learn-python-3) |
| **CS50 (Harvard)** | Hordhac sayniska kombiyuutarka; agab bilaash ah | [cs50.harvard.edu/x](https://cs50.harvard.edu/x/) |

## ✅ Liiska hubinta

- [ ] Waxaan qoray barnaamij Python ah oo adeegsada variables, loops iyo functions.
- [ ] Waxaan akhriyey oo qoray fayl Python ah.
- [ ] Waxaan `requests` ku diray codsi bog tijaabo ah.
- [ ] Waxaan qoray qoraal yar oo hubiya dekedaha mashiin maxalli ah ama shaybaar fasax leh.
- [ ] Waxaan fahmay aasaaska Bash.
- [ ] Waxaan rakibay maktabad anigoo adeegsanaya `pip`.

## ⏱️ Waqtiga qiyaasta ah

4–6 toddobaad. Ku celceli; uma baahnid inaad luuqadda oo dhan barato ka hor intaadan marxaladda xigta bilaabin.

## 🏁 Hawsha lagu hubinayo horumarka

Samee mashruuc yar oo aad sharxi karto, sida hubiye headers HTTP ah oo ka shaqeeya shaybaar maxalli ah. Ku qor GitHub oo ku dar README sharxaya sida loo isticmaalo. Tani waxay noqon kartaa bilowga galkaaga shaqo (portfolio).

→ Marka xigta: [Marxaladda 4: Amniga barnaamijyada webka](05-amniga-web-ka.md)
