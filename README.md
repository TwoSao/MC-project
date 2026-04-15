# 📁 Microsoft Project — Õppematerjal

> Veebipõhine juhend Microsoft Projecti põhifunktsioonide kasutamiseks.

---

## 📋 Sisukord

- [Projekti kirjeldus](#-projekti-kirjeldus)
- [Lisatud funktsioonid](#-lisatud-funktsioonid)
- [Muudetud failid](#-muudetud-failid)
- [Tehtu nimekiri](#-tehtu-nimekiri)
- [Failide tabel](#-failide-tabel)
- [Koodinäide](#-koodinäide)
- [Ekraanipildid](#-ekraanipildid)

---

## 📖 Projekti kirjeldus

See projekt on kolmeleheline veebisait, mis õpetab Microsoft Projecti kasutamist kolmes valdkonnas:

1. **Kalender** — töökalendri loomine ja seadistamine
2. **Valem** — kohandatud arvutusväljade lisamine
3. **Diagramm** — Gantt, Network Diagram ja Resource Graph

---

## ✨ Lisatud funktsioonid

### 📅 Kalender (`index.html`)
- Samm-sammuline juhend töökalendri loomiseks
- Kirjeldus: `Change Working Time`, `Create New Calendar`, tööaja seadistamine

### 🧮 Valem (`valem.html`)
- Kohandatud välja (`Custom Field`) loomine
- Valemi sisestamine (`Formula...`) ja veeru lisamine vaatesse

### 📊 Diagramm (`diagramm.html`)
- Gantt-diagrammi, võrgudiagrammi ja ressursigraafiku kasutamine
- Diagrammi kohandamine (`Bar Styles`, `Layout`)

---

## 🗂 Muudetud failid

- `index.html` — kalendri juhend koos piltidega
- `valem.html` — valemi juhend koos piltidega
- `diagramm.html` — diagrammide juhend koos piltidega
- `style.css` — kõigi lehtede ühine stiil (navigatsioon, päis, sektsioonid)
- `images/` — kõik juhendite ekraanipildid (`img1–5`, `valem1–4`, `dig1–4`)

---

## ✅ Tehtu nimekiri

- [x] Loodud `index.html` — kalendri leht
- [x] Loodud `valem.html` — valemi leht
- [x] Loodud `diagramm.html` — diagrammide leht
- [x] Loodud `style.css` — ühine stiilileht
- [x] Lisatud navigatsioon kõigile lehtedele
- [x] Lisatud ekraanipildid kausta `images/`
- [x] Loodud `README.md`

---

## 📊 Failide tabel

| Fail | Kirjeldus | Pildid |
|------|-----------|--------|
| `index.html` | Kalendri juhend | `img1.png` – `img5.png` |
| `valem.html` | Valemi juhend | `valem1.png` – `valem4.png` |
| `diagramm.html` | Diagrammide juhend | `dig1.png` – `dig4.png` |
| `style.css` | Ühine stiilileht | — |

---

## 💻 Koodinäide

Navigatsioonilinkide HTML-struktuur:

```html
<nav>
  <div class="nav-inner">
    <a href="index.html" class="nav-brand">📁 MS Project</a>
    <a href="index.html" class="active">📅 Kalender</a>
    <a href="valem.html">🧮 Valem</a>
    <a href="diagramm.html">📊 Diagramm</a>
  </div>
</nav>
```

CSS klassi näide aktiivse lingi jaoks:

```css
nav a.active {
  font-weight: bold;
  border-bottom: 2px solid #fff;
}
```

---

## 🖼 Ekraanipildid

### Kalender
<img width="1025" height="838" alt="{A88F9DF0-D7A7-4748-9A2E-03B987EB2BC6}" src="https://github.com/user-attachments/assets/88b6dfcb-a2f8-48c2-a621-52d93bb37a28" />

### Diagramm
<img width="1053" height="923" alt="{B3B0ECD1-4BC4-4CAF-932A-1C33857B6269}" src="https://github.com/user-attachments/assets/69542cb8-86f8-4df0-9558-3f3848c60892" />





> [!WARNING]
> Ekraanipildid on tehtud Microsoft Project 2019 versioonis — mõned menüüd võivad uuemates versioonides erineda.

---

## 🔗 Kasulikud lingid

- [Microsoft Project ametlik leht](https://www.microsoft.com/en-us/microsoft-365/project/project-management-software)
- [GitHub Markdown süntaks](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-syntax)

---

© 2026 Illia Blahun [^1]
