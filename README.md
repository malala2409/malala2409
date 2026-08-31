# Hi, I'm Yihan Ma 👋

**LL.M. Student in Computer Science & Law @ FAU Erlangen-Nürnberg**

Master's student in **Informatik & Recht (Computer Science & Law)** at Friedrich-Alexander-Universität (FAU), Germany, passionate about data — from SQL-based analysis to building tools that make complex information accessible. I work at the intersection of regulation and technology, and embrace vibe coding to turn ideas into real products fast.

---

## Projects

### [Privacy Analyzer](https://github.com/malala2409/privacy-analyzer)

[![Repo](https://img.shields.io/badge/GitHub-malala2409/privacy--analyzer-blue?style=flat-square&logo=github)](https://github.com/malala2409/privacy-analyzer)
[![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)](https://opensource.org/licenses/MIT)

Ein zweisprachiges (DE/EN) Web-Tool, das eine eingefügte **Datenschutzerklärung analysiert** und verständlich aufschlüsselt: welche personenbezogenen Daten und Geräteberechtigungen erfasst werden, an welche Dritte Daten fließen, auf welcher Rechtsgrundlage und wie lange gespeichert wird — jeweils mit Zuordnung zu den einschlägigen **DSGVO- und BDSG-Vorschriften**.

**Kernfunktionen:**
- **KI-Analyse** — Multi-Modell-Gateway (lokales Ollama kostenlos ohne API-Key, DeepSeek, OpenAI, Qwen, GLM, Claude) mit strukturierter JSON-Extraktion, Zitaten und Risikostufen; Offline-Keyword-Fallback
- **16 Datenkategorien & 10 Berechtigungen** — inkl. besonderer Kategorien (Gesundheit, Biometrie, Genetik, Straftaten) mit automatischer Risikoeinstufung
- **Rechtsvorschriften** — DSGVO (Art. 4–9, 10, 22, 88 …) und BDSG (§ 4, 22, 26, 30, 31, 37 …) auf Knopfdruck
- **Report-Export** — HTML/PDF mit farblich markiertem Originaltext und zugeordneten Vorschriften
- **Vollständig zweisprachig** — DE/EN-Umschaltung

[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Python](https://img.shields.io/badge/Python-3.9+-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org)
[![Ollama](https://img.shields.io/badge/Ollama-local_LLM-000000?style=flat-square&logo=ollama&logoColor=white)](https://ollama.com)
[![Topic](https://img.shields.io/badge/Topic-GDPR%20%2F%20BDSG-cd3b3b?style=flat-square)](https://gdpr-info.eu)

---

### [Vertragsmanagementsystem · Contract Management System](https://github.com/malala2409/contract-system-Vertragsmanagementsystem)

[![Repo](https://img.shields.io/badge/GitHub-malala2409/contract--system-blue?style=flat-square&logo=github)](https://github.com/malala2409/contract-system-Vertragsmanagementsystem)
[![Live Demo](https://img.shields.io/badge/Demo-GitHub%20Pages-green?style=flat-square)](https://pages.github.com)
[![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)](https://opensource.org/licenses/MIT)

Eine webbasierte Anwendung zur **Verwaltung, Befüllung und rechtlichen Prüfung von Vertragsvorlagen** nach deutschem Zivilrecht (BGB). Verfügbar in zwei Versionen: einer reinen **Browser-Version** (Vanilla JS + localStorage, kein Server nötig) und einer **Flask-Version** mit SQLite-Backend für den Multi-User-Einsatz.

**Kernfunktionen:**
- **Vorlagenverwaltung** — 7 BGB-Vertragstypen (Kauf-, Miet-, Dienst-, Werk-, Darlehens-, Arbeitsvertrag, NDA) mit zweisprachigen Klauseltexten
- **Vertriebsportal** — Zweistufiger Ausfüllprozess (strukturiertes Formular + Freitextbearbeitung), Vorschau mit farblich markierten Platzhaltern, personalisierte Einreichungsübersicht
- **Prüfungs-Workflow** — Status-Automation (Eingereicht → Genehmigt / Abgelehnt), additive Prüfnotizen mit Zeitstempel und Verlaufshistorie, Überarbeitungsschleife bei Ablehnung
- **Template-Editor** — Visueller Section-Editor + Drag-and-Drop-Assistent zum Zusammenstellen neuer Vorlagen aus vordefinierten Bausteinen
- **Vollständig zweisprachig** — DE/EN-Internationalisierung mit 164+ Übersetzungsschlüsseln, alle UI-Texte und Vertragsklauseln bilingual
- **Dokumenten-Upload** — Word (.docx) und PDF-Anhänge mit Download-Funktion

[![Python](https://img.shields.io/badge/Python-3.9+-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org)
[![Flask](https://img.shields.io/badge/Flask-3.1-red?style=flat-square&logo=flask&logoColor=white)](https://flask.palletsprojects.com)
[![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)](https://www.sqlite.org)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)](https://tailwindcss.com)
[![Topic](https://img.shields.io/badge/Topic-Contract%20Law%20%2F%20BGB-2563eb?style=flat-square)](https://www.gesetze-im-internet.de/bgb/)

---

### [GDPR Compliance Checklist](https://github.com/malala2409/GDPR-checklist)

[![Repo](https://img.shields.io/badge/GitHub-malala2409/GDPR--checklist-blue?style=flat-square&logo=github)](https://github.com/malala2409/GDPR-checklist)
[![Live Demo](https://img.shields.io/badge/Demo-GitHub%20Pages-green?style=flat-square)](https://pages.github.com)
[![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)](https://opensource.org/licenses/MIT)

Ein interaktives, zweisprachiges Web-Tool zur **DSGVO-Compliance-Selbstbewertung**, entwickelt für Datenschutzbeauftragte, Juristen und Compliance-Verantwortliche. Läuft vollständig im Browser — kein Server, keine Abhängigkeiten.

**Kernfunktionen:**
- **Interaktive Checkliste** — 8 Themenbereiche mit 47+ DSGVO-Prüfpunkten, inkl. Artikel-Referenzen und BDSG/TTDSG-Bezügen. Ein-Klick-Erledigung mit visuellem Fortschrittsbalken, Persistenz via localStorage
- **Dokumenten-Scanner** — Keyword-basierte Analyse mit 30+ Regex-Patterns (DE + EN) + **KI-gestützte Prüfung** via Anthropic Claude API mit semantischer Analyse, Zitaten und Begründungen. Unterstützt PDF (PDF.js), DOCX (Mammoth.js), TXT, JSON, CSV
- **Gesetzestexte auf Knopfdruck** — Über 50 Artikel und Paragraphen aus DSGVO, BDSG und TTDSG direkt im Modal abrufbar (DE + EN), Bereichsreferenzen (z.B. Art. 44–49) automatisch aufgelöst
- **Export-Funktionen** — HTML-Report mit zweispaltigem Layout (Originaltext mit Markierungen + zugeordnete Vorschriften) und interaktiven Beweis-Zitaten; PDF-Export via `window.print()`
- **Vollständig zweisprachig** — Alle UI-Texte, Checklistenpunkte, Scan-Patterns und Gesetzestexte bilingual DE/EN

[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Claude API](https://img.shields.io/badge/Claude_API-Sonnet_4.6-d97706?style=flat-square)](https://docs.anthropic.com/en/docs)
[![Topic](https://img.shields.io/badge/Topic-GDPR%20%2F%20Data%20Protection-cd3b3b?style=flat-square)](https://gdpr-info.eu)

---

### [LexCortex — Fristen- und Fallmanagement](https://github.com/malala2409/LexCortex---Case-Management)

[![Repo](https://img.shields.io/badge/GitHub-malala2409/LexCortex-blue?style=flat-square&logo=github)](https://github.com/malala2409/LexCortex---Case-Management)

Ein webbasiertes Tool zur **Verwaltung von Gerichtsverfahren, Fristen und Aufgaben**, entwickelt im Rahmen des Moduls „Informatik 2 für Nebenfachstudierende" an der FAU Erlangen-Nürnberg.

**Kernfunktionen:**
- **Dashboard** — schneller Überblick über aktive Fälle, diese Woche anstehende Fristen und überfällige Aufgaben
- **Verfahrensphasen** — konfigurierbare Phasen pro Fall
- PHP-basiert

[![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)](https://www.php.net)
[![Topic](https://img.shields.io/badge/Topic-Legal%20Case%20Management-2563eb?style=flat-square)](https://github.com/malala2409/LexCortex---Case-Management)

---

## Skills

**Technical**

[![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)](https://www.postgresql.org)
[![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoft-excel&logoColor=white)](https://www.microsoft.com/en-us/microsoft-365/excel)
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org)

**Legal Tech & Databases**

[![Westlaw](https://img.shields.io/badge/Westlaw-003366?style=flat-square)](https://legal.thomsonreuters.com/en/westlaw)
[![Beck-Online](https://img.shields.io/badge/Beck--Online-CC0000?style=flat-square)](https://www.beck-online.de)
[![Juris](https://img.shields.io/badge/Juris-444444?style=flat-square)](https://www.juris.de)

**Languages**

German — C1 &nbsp;|&nbsp; English — Fluent &nbsp;|&nbsp; Chinese — Native

---

## Contact

[yihan.ma@fau.de](mailto:yihan.ma@fau.de)
+49 (0)174 2707466

---
