# AGENTS.md — FrancescoCastaldi

Repository **PUBBLICO** del profilo GitHub (profile README): contiene il `README.md` mostrato sulla pagina profilo, gli asset SVG in `assets/`, uno script di supporto in `_tools/update.py` e un workflow GitHub Actions in `.github/workflows/oz-agent.yml` — tutto ciò che vi finisce è leggibile da chiunque su GitHub. Repository su `D:/Sviluppo/FrancescoCastaldi` (origin `FrancescoCastaldi/FrancescoCastaldi`). Le direttive generali della chiavetta sono in `D:/AGENTS.md` (da leggere per primo) e `D:/Sviluppo/AGENTS.md` (area Sviluppo): questo file le integra, non le sostituisce.

## 🔐 Credenziali, token & chiavi API — protocollo vault (obbligatorio)

Questo file non contiene segreti e non deve mai contenerne. Tutte le credenziali della chiavetta vivono nel **vault unico** `D:/.env`, cifrato a riposo in `D:/.env.7z` (AES-256). Il protocollo completo è in `D:/AGENTS.md` §5, da leggere prima di qualsiasi attività che richieda un token. In sintesi:

```powershell
powershell -File D:/Scripts/vault/status-env.ps1   # exit 0 = UNLOCKED; exit 2 = LOCKED -> fermarsi e chiedere all'utente di eseguire unlock-env.ps1
. D:/Scripts/vault/load-env.ps1 -Quiet             # esporta le variabili nella sessione corrente (mai stamparne i valori)
```

- **Chiavi rilevanti per quest'area**: `GH_TOKEN`, `GITHUB_TOKEN`, `GITHUB_USER`. Schema completo (nomi, nessun valore): `D:/.env.example`.
- **Vietato**: leggere altri `.env`, `.npmrc` o `connessione_*.txt` come fonte di token; stampare, loggare o copiare valori; committare `.env*` (eccetto `.env.example`); chiedere la password del vault in chat.
- Vault **LOCKED** → fermarsi e chiedere l'unlock, senza cercare copie altrove. Chiave assente dallo schema → non esiste nel vault: proporne l'aggiunta secondo `D:/AGENTS.md` §5.5.
- **Fine sessione**: ricordare all'utente `powershell -File D:/Scripts/vault/lock-env.ps1`.

## 🌐 Repository PUBBLICO — nessun dato riservato

- Questo repository è **pubblico** su GitHub: ogni file, commit, asset e riga di cronologia è visibile a chiunque, per sempre (un revert non cancella la history). Trattarlo come una pagina web pubblicata.
- **Mai** inserire credenziali, token, chiavi API, password, ID di servizi terzi, indirizzi email privati, numeri di telefono, indirizzi fisici o qualsiasi altro identificativo personale oltre a quelli **già pubblici** nel `README.md` (nome, sito web, email di contatto pubblica, link ai profili open source).
- Il workflow in `.github/workflows/` deve usare esclusivamente `secrets.*` di GitHub Actions: nessun valore hardcoded nei file YAML, in `_tools/update.py` o negli SVG di `assets/`.
- Prima di ogni commit/push controllare il diff: non devono comparire file `.env*`, dump, log o output di script che contengano valori. In caso di dubbio, fermarsi e chiedere all'utente.

## 🎨 Manutenzione Estetica & Aggiornamento con `profile-readme-curator`

- Per qualsiasi aggiornamento o miglioramento estetico a `README.md`, seguire la skill portabile **[`profile-readme-curator`](file:///D:/.agents/skills/profile-readme-curator/SKILL.md)**.
- Rispettare rigorosamente il canone *The Editorial Blueprint*:
  1. Palette dual-theme sobria (bone `#E8E2D5`, sage `#9CA68D`, gold `#B99B6B`, slate `#3A372F`, deep charcoal `#2B2823`).
  2. Titoli di sezione solo `### ` con numeri romani (es. `### I &mdash; Open Source`). MAI usare `## ` per evitare la riga grigia nativa di GitHub sotto l'intestazione.
  3. Divisori orizzontali solo tramite l'asset SVG hairlines con motivo a rombo (`assets/rule-*.svg` a 320px). MAI usare `---` o `<hr>`.
  4. Nessuna animazione gif o badge generico sgargiante.
  5. Prima di committare, validare sempre con `python D:/.agents/skills/profile-readme-curator/scripts/verify_profile.py`.

