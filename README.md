# 🏕️ Camping Piscina Demonte

Sito ufficiale del campeggio “Camping Piscina Demonte”, realizzato con [Hugo](https://gohugo.io) e pubblicato tramite [Netlify](https://www.netlify.com).

👉 [Visita il sito](https://campingpiscinademonte.com)

---

## 🚀 Tecnologie
- **Static site generator**: Hugo (v0.121.2 extended)
- **Hosting & deploy**: Netlify con integrazione GitHub
- **GitHub** (versionamento e collaborazione)
- **DNS**: gestito tramite Netlify
- **Design**: tema custom interamente sviluppato su misura (layouts, shortcodes, partials)

---

## 📂 Struttura principale
- `content/it/` → pagine principali in italiano (`_index.md`, `chi-siamo.md`, `servizi/`, ecc.)
- `layouts/` → template personalizzati (homepage, sezioni servizi, galleria…)
- `static/` → immagini e risorse statiche
- `assets/css/` → file CSS personalizzati
- `netlify.toml` → configurazione deploy, redirect e headers

---

## ✨ Funzionalità
- **Homepage** con hero dinamico e sezioni “Scopri il campeggio” + servizi in evidenza
- Pagina **Servizi** con sottosezioni per chalet, piazzole, piscina, igloo, ecc.
- **Galleria fotografica** responsive per valorizzare l’ambiente
- Pagine **Regolamento** e **Listino** facilmente aggiornabili
- **Contatti rapidi** con link a Google Maps, telefono e form

---

## 🔧 Deploy & sviluppo locale

Per testare il sito in locale:

bash
hugo server -D

---

## 🤝 Credits

Progetto sviluppato con il ❤️ da [**Manuel – Assembler Computer**](https://www.assemblercomputer.net/).

---


[![Netlify Status](https://api.netlify.com/api/v1/badges/02ea4570-e201-4a13-8446-8ff42dac104f/deploy-status)](https://app.netlify.com/projects/testpiscinademonte/deploys)
