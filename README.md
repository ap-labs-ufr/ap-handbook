# 🧪 Physikalisches Anfängerpraktikum – Jupyter Book

Willkommen im Repository des **Jupyter Books zum Physikalischen Anfängerpraktikum** an der Universität Freiburg.  
Dieses Projekt dient als zentrale Sammlung aller **Versuchsanleitungen**, **Ergänzungsmaterialien**, **Tutorials** und **Notebook-Beispiele** für Studierende, die die Praktikumsversuche digital vorbereiten oder auswerten möchten.

---

## 🌐 Online-Version des Praktikumshandbuchs

Das interaktive Handbuch ist hier abrufbar:  
👉 **[https://ap-labs-ufr.github.io/ap-handbook/Intro.html](https://ap-labs-ufr.github.io/ap-handbook/Intro.html)**

*(Die Seite wird automatisch über GitHub Actions aktualisiert, sobald Änderungen im Repository vorgenommen werden.)*

---

## 📁 Projektstruktur

```
ap-handbook/
├─ _config.yml           # Jupyter-Book-Konfiguration
├─ _toc.yml              # Inhaltsverzeichnis des Buchs
├─ README.md             # Diese Datei (nur auf GitHub sichtbar)
├─ requirements.txt      # Python-Abhängigkeiten
├─ .github/workflows/    # Automatischer Build- und Deploy-Prozess
│   └─ deploy.yml
└─ experiments/
   ├─ 02_pendel/
   └─ 04_dichte/
```

---

## ⚙️ Lokaler Build

Um das Jupyter Book lokal zu erstellen:

```
# 1. Abhängigkeiten installieren
pip install -r requirements.txt

# 2. Buch bauen
jupyter-book build .

# 3. Lokales HTML öffnen
open _build/html/index.html
```

---

## 🎯 Ziel des Projekts

Das Projekt verfolgt das Ziel, das **Praktikum digitaler, interaktiver und barrierefreier** zu gestalten.  
Es enthält:
- Schritt-für-Schritt-Anleitungen zu allen Versuchen,  
- interaktive Fragen zur Versuchsvorbereitung,  
- eingebettete Videos und Abbildungen,  
- Python-Notebooks zur Datenauswertung.

Das Material richtet sich an Studierende im **Physikalischen Anfängerpraktikum (AP)**,  
kann aber auch zur **Vorbereitung auf das Fortgeschrittenenpraktikum (FP)** genutzt werden.

---

## 👥 Mitwirkende

Projektkoordination und Inhalte: Christof Bartels 
unterstützt durch das Team des Physikalischen Praktikums der **Universität Freiburg**.

---

## 🛠️ Lizenz

Sofern nicht anders angegeben, steht das Material unter der  
[MIT-Lizenz](https://opensource.org/licenses/MIT).
