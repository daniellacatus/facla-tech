# Articole: Tehnologie, Inteligență Artificială și Securitate online

Acest repository conține articole și resurse publicate pe teme din tehnologie: vulnerabilități wordpress, securitate online, securitatea aplicațiilor mobile și evoluția inteligenței artificiale. Conținutul este original și reflectă o analiză critică, orientată spre realitatea tehnică și socială contemporană.

🔗 Articolele sunt publicate și în categoria **Tehnologie și Știință** de pe [Facla.ro](https://facla.ro/category/tehnologie-si-stiinta/).

## Domenii tratate

- Securitate web și mobilă
- Manipulare online și dezinformare digitală
- Inteligență artificială – avantaje și riscuri
- Optimizare web și transparență în SEO
- Tehnologii emergente și impact social

## Structura repository-ului

Fiecare articol este salvat într-un fișier `.md` separat, grupat tematic în directoare:
```
- securitate/
- ai/
- manipulare-online/
- google-algoritmi/
```

## Licență

Conținutul este public pentru lectură, dar nu poate fi preluat fără acordul autorului.

# Aplicația DeepSeek pentru iOS prezintă riscuri majore de securitate

📅 martie 11, 2025  
✍️ by Daniel Lăcătuș  

---

Un audit recent al aplicației mobile **DeepSeek** pentru sistemul de operare **iOS** al Apple a identificat vulnerabilități semnificative de securitate, în principal transmiterea de date sensibile ale utilizatorilor și dispozitivelor prin internet fără criptare. Această expunere crește riscul de interceptare și manipulare a datelor, conform *TheHackerNews.com*.

Constatările provin de la compania de securitate **NowSecure**, care a constatat, de asemenea, că aplicația nu respectă cele mai bune practici de securitate și colectează o cantitate considerabilă de informații despre utilizatori și dispozitive.

> „Aplicația DeepSeek pentru iOS trimite anumite date de înregistrare și informații despre dispozitiv prin internet fără criptare”, a raportat NowSecure. „Acest lucru expune orice date din traficul de internet la atacuri pasive și active.”

---

### 🔐 Probleme de criptare

- Algoritm criptografic învechit: **3DES**
- Cheie de criptare inclusă în codul sursă
- Reutilizarea vectorilor de inițializare
- Dezactivarea completă a funcției **App Transport Security (ATS)**

---

### ☁️ Servere & Transmitere Date

Datele colectate sunt transmise către servere administrate de **Volcano Engine**, o platformă de cloud deținută de **ByteDance**, compania-mamă a TikTok.

---

### 🚨 Alte riscuri & implicații

- Actori malițioși folosesc AI de la DeepSeek, Alibaba Qwen și ChatGPT pentru generare malware și spam
- Transfer de date către **China Mobile**, ceea ce a determinat propunerea unor restricții în SUA
- Țări și instituții care au interzis aplicația: SUA (Congres, NASA, Pentagon), Australia, Italia, Olanda, Taiwan, Coreea de Sud etc.
- Atacuri **DDoS** de la botneții **Mirai**
- **Site-uri false** cu malware, scheme de criptomonede
- Acuzații de colectare excesivă de date de către Serviciul Național de Informații al Coreei de Sud

---

### 📉 Vulnerabilități și pe Android

Versiunea 1.0.8 Android include:
- Chei de criptare hardcodate
- Algoritmi slabi
- Risc de **SQL injection**
- Mecanisme anti-debugging (contra transparenței)

---

### ⚠️ Concluzie

Aceste descoperiri accentuează riscurile de securitate asociate aplicațiilor AI și necesitatea unor măsuri de reglementare și supraveghere riguroasă.

---

📎 [Sursa originală articol pe Facla.ro](https://facla.ro/aplicatia-deepseek-pentru-ios-prezinta-riscuri-majore-de-securitate/)

