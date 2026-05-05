[README.md](https://github.com/user-attachments/files/27405659/README.md)
# Sicilia in Famiglia – Landing Page

Sito informativo statico per il progetto **Sicilia in Famiglia**.  
Realizzato in HTML + CSS puro, ottimizzato per GitHub Pages.

---

## ⚠ Natura del servizio

Sicilia in Famiglia è un **servizio gratuito di orientamento informativo** per famiglie interessate a soggiorni in Sicilia.  
**Non è un'agenzia di viaggi.** Non incassa pagamenti, non emette contratti, non conclude accordi commerciali con i clienti.  
Prenotazioni, preventivi, contratti, pagamenti e garanzie sono gestiti esclusivamente da **GB Viaggi**.

---

## 📁 Struttura della repository

```
sicilia-in-famiglia/
├── index.html              # Landing page principale
├── style.css               # Foglio di stile esterno
├── README.md               # Questo file
│
├── assets/                 # Loghi e favicon
│   ├── favicon.png
│   ├── logo-sicilia-famiglia.png
│   └── logo-gb-viaggi.png
│
└── images/                 # Immagini delle destinazioni e sfondi
    ├── hero-main.jpg
    ├── bg-intermezzo.jpg
    ├── agrigento.jpg
    ├── catania.jpg
    ├── cefalu.jpg
    ├── isole-eolie.jpg
    ├── palermo.jpg
    ├── ragusa.jpg
    ├── san-vito-lo-capo.jpg
    ├── siracusa.jpg
    ├── taormina.jpg
    └── trapani.jpg
```

---

## 🚀 Deploy su GitHub Pages

1. Crea una repository pubblica su GitHub (es. `sicilia-in-famiglia`)
2. Carica tutti i file rispettando la struttura sopra
3. Vai in **Settings → Pages**
4. Sorgente: **Deploy from a branch** → `main` → `/ (root)`
5. Salva — il sito sarà disponibile su `https://tuonome.github.io/sicilia-in-famiglia/`

---

## ✏️ Personalizzazioni necessarie

Prima di pubblicare, modifica in `index.html`:

| Cosa | Dove | Valore attuale |
|---|---|---|
| Numero WhatsApp | tutti i link `href="https://wa.me/..."` | `NUMERODAINSERIRE` |
| Email | `href="mailto:..."` | `info@siciliainfamiglia.it` |
| Open Graph image | `<meta property="og:image">` | `assets/og-image.jpg` |

---

## 🎨 Palette colori

Estratta direttamente dal logo:

| Token | Valore | Uso |
|---|---|---|
| `--t` | `#C4622D` | Terracotta primario (CTA, tag, accenti) |
| `--t-l` | `#D97848` | Terracotta light (hover) |
| `--t-d` | `#9E4E22` | Terracotta dark (top bar) |
| `--brown` | `#1E130A` | Bruno scuro (sezioni dark, footer) |
| `--cream` | `#FDFAF4` | Sfondo principale |
| `--cream-d` | `#F5EBD8` | Sfondo sezioni alternate |
| `--sand` | `#DEB97A` | Highlights su sfondo scuro |

---

## 🛠 Tecnologie

- HTML5 semantico
- CSS3 custom properties (no framework)
- JavaScript vanilla (accordion FAQ + scroll reveal)
- Google Fonts: Cormorant Garamond + DM Sans
- Zero dipendenze esterne
- Mobile first, responsive

---

## 📋 Sezioni della landing

1. **Top bar** — disclaimer fisso sempre visibile
2. **Hero** — immagine `hero-main.jpg` + CTA WhatsApp + disclaimer
3. **Come funziona** — 3 step + logo GB Viaggi + nota legale
4. **Cosa facciamo** — lista servizi informativi + immagine Taormina
5. **Cosa NON facciamo** — 5 card graficamente separate
6. **Destinazioni** — griglia 10 zone in chiave editoriale (no prezzi)
7. **Intermezzo** — sfondo `bg-intermezzo.jpg` + CTA
8. **FAQ trasparenza** — 6 domande/risposte accordion
9. **CTA finale** — invito WhatsApp
10. **Footer** — disclaimer legale completo + link legali

---

## ⚖️ Note legali

Tutta la pagina è progettata per **minimizzare il rischio** che l'utente percepisca Sicilia in Famiglia come venditore diretto di servizi turistici.  
Sono presenti **3 disclaimer espliciti** (hero, sezione "Come funziona", footer).  
La parola chiave "GB Viaggi" appare nominativamente in ogni sezione rilevante.

---

*Aggiornato: 2026*
