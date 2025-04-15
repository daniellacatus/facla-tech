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

## Instrumente esențiale pentru verificarea securității pe internet

**martie 24, 2025** by [Daniel Lăcătuș](https://facla.ro/instrumente-esentiale-pentru-verificarea-securitatii-pe-internet/)

În contextul utilizării tot mai largi a internetului, este important să acordăm atenție modului în care ne protejăm informațiile și activitățile online. Evaluarea și menținerea unui nivel corespunzător de securitate reprezintă un pas necesar atât pentru administratorii de site, cât și pentru utilizatorii obișnuiți.

### Verificarea și monitorizarea securității domeniilor web
Un prim pas în asigurarea unei prezențe sigure pe internet constă în evaluarea configurațiilor și monitorizarea constantă a domeniilor web. Verificarea periodică a înregistrărilor DNS, a setărilor serverelor de email și a altor elemente poate preveni problemele ulterioare. De exemplu, MX Toolbox este un instrument util pentru analizarea stării serverelor de email și pentru verificarea prezenței domeniilor pe liste de blocare.

Un alt aspect esențial îl reprezintă identificarea informațiilor de bază despre un domeniu. [Whois Lookup](https://whois.domaintools.com/) oferă detalii despre proprietarul unui site, data înregistrării și termenele de valabilitate. Aceste informații permit verificarea autenticității unui site și pot fi consultate înainte de a furniza date personale sau de a efectua tranzacții comerciale.

În plus, serviciile care analizează reputația unui domeniu, precum [URLVoid](https://www.urlvoid.com/), oferă informații privind istoricul unor posibile activități suspecte raportate în legătură cu acel site. Monitorizarea constantă a modificărilor în configurația DNS și a certificatelor de securitate permite administratorilor să detecteze orice modificare neautorizată și să ia măsuri înainte ca aceasta să provoace probleme majore.

### Protecția împotriva programelor malițioase și analiza amenințărilor
Existența programelor malițioase și a altor tipuri de amenințări reprezintă un factor de risc ce trebuie gestionat cu atenție. Identificarea și eliminarea riscurilor presupune utilizarea unor instrumente care analizează fișiere, URL-uri și comportamentul site-urilor pentru a detecta semnele unor activități potențial dăunătoare.

Un exemplu de astfel de instrument este [VirusTotal](https://www.virustotal.com/), care permite scanarea fișierelor și a adreselor web prin intermediul mai multor motoare antivirus. Rapoartele detaliate oferite ajută la compararea rezultatelor obținute de la diverși furnizori de servicii de securitate, contribuind la o evaluare obiectivă a fișierelor suspecte.

Serviciul oferit de [Google Safe Browsing](https://transparencyreport.google.com/safe-browsing/search) funcționează în fundalul browserelor și analizează comportamentul site-urilor, identificând posibilele activități asociate cu phishing-ul sau alte acțiuni neautorizate. Informațiile furnizate contribuie la blocarea automată a site-urilor considerate nesigure, reducând astfel riscul de expunere a datelor personale. În plus, actualizările periodice ale bazei de date ale Google Safe Browsing asigură o protecție continuă și adaptată la noile metode de atac.

Pe lângă instrumentele menționate, soluții precum [Malwarebytes](https://www.malwarebytes.com/) sunt de asemenea utilizate pentru identificarea și eliminarea codurilor dăunătoare care pot afecta integritatea sistemelor.

### Criptarea și protejarea datelor personale
Protejarea informațiilor personale este un aspect central în asigurarea securității online. Metodele de criptare oferă un strat suplimentar de protecție, prevenind accesul neautorizat la datele sensibile.

[SSL Labs](https://www.ssllabs.com/ssltest/) este utilizat pentru evaluarea configurării certificatelor SSL/TLS ale site-urilor. Prin generarea unor rapoarte detaliate, certificatele identifică eventualele vulnerabilități ale setărilor de criptare și oferă recomandări pentru îmbunătățirea securității conexiunilor.

Pe lângă analiza certificatelor SSL, serviciile [VPN](https://www.expressvpn.com/) sunt folosite pentru criptarea traficului pe internet, mascarea adresei IP și protejarea datelor atunci când se accesează rețele publice, reducând riscul interceptării datelor și contribuind la menținerea confidențialității informațiilor transmise.

Gestionarea parolelor reprezintă o altă componentă esențială în protejarea informațiilor. Soluții precum [Bitwarden](https://bitwarden.com/) și [LastPass](https://www.lastpass.com/) permit generarea și stocarea în siguranță a unor parole complexe. De asemenea, implementarea autentificării în doi pași adaugă un nivel suplimentar de securizare, oferind o verificare suplimentară înainte să fie acordat accesul la conturile personale.

În final, politica de backup regulat al datelor completează ansamblul de măsuri de protecție. Stocarea securizată și verificarea periodică a datelor asigură posibilitatea restaurării informațiilor în caz de incident, contribuind la menținerea funcționării neîntrerupte a sistemelor.

### Concluzie
Consider că o abordare integrată, ce combină verificarea constantă a domeniilor, monitorizarea atentă a programelor malițioase și implementarea metodelor de criptare, reprezintă o soluție echilibrată pentru menținerea securității pe internet. Experiența mă învață că niciun instrument nu este suficient de sigur, ci este necesară o combinație de resurse care să ofere o evaluare cuprinzătoare a riscurilor.

Cred că această abordare modulară, bazată pe instrumente precum [MX Toolbox](https://mxtoolbox.com/), [VirusTotal](https://www.virustotal.com/), și [SSL Labs](https://www.ssllabs.com/ssltest/), reprezintă un punct de plecare solid în procesul de protejare a datelor și de prevenire a incidentelor. Adaptarea continuă la noile amenințări și menținerea unei atitudini preventive sunt, în final, esențiale pentru a face față provocărilor actuale.


