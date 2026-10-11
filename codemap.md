# Codemap: Architettura & Mappa Moduli: Francesco Castaldi GitHub Special Repository

Mappa architetturale e guida alla navigazione del repository `FrancescoCastaldi` (Archetipo 2).

---

## 🎯 Responsabilita del Repository

Repository speciale per il profilo pubblico GitHub di Francesco Castaldi con design system su misura e metriche open source.

---

## 🚪 Punti di Ingresso del Sistema

* **Punto di Ingresso Primario**: `README.md`
* **Tecnologie Impiegate**: Markdown, SVG Custom Graphics, GitHub Actions
* **Organizzazione Moduli**: assets/ (grafiche SVG dual theme), .github/workflows/ (automazione aggiornamenti)

---

## 🌳 Mappa delle Cartelle e Componenti

| Cartella / File | Responsabilita Architetturale | Note di Progetto |
|:---|:---|:---|
| `README.md` | Presentazione del progetto, guida rapida e requisiti | [Apri](README.md) |
| `AGENTS.md` | Linee guida per l'AI, regole SemVer e protocollo test | [Apri](AGENTS.md) |
| `CHANGELOG.md` | Cronologia delle release conforme a Keep a Changelog 1.1.0 | [Apri](CHANGELOG.md) |
| `src/` o root | Codice sorgente e logica applicativa principale | Modulo core |

---

## 🔄 Flusso di Controllo e Dati

1. **Inizializzazione**: Avvio dal modulo `README.md` e caricamento delle configurazioni.
2. **Elaborazione**: Esecuzione della logica specifica attraverso `assets/ (grafiche SVG dual theme), .github/workflows/ (automazione aggiornamenti)`.
3. **Verifica & Output**: Convalida dell'integrita dei dati ed emissione dei risultati.
