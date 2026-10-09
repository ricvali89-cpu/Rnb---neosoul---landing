# VRicky Studio v41 — Beta / note di rilascio

**Data:** 09/10/2026  
**Stato:** BETA PRONTA NEL REPOSITORY; DEPLOY WEB DA VERIFICARE  
**File:** [studio-v41.html](../studio-v41.html)  
**Riferimento:** [Bibbia Prompt Suno v6](BIBBIA_PROMPT_SUNO_V6.md)  
**Versione precedente:** v40, incorporata nella landing `index.html`, lasciata invariata.

## Modifiche consegnate
- Interfaccia rapida R&B/Funk, Neo Soul, Dark R&B/Funk, ottimizzata per iPhone.
- Mood, energia, tipo di voce e modalità Precisa/Creativa.
- Un editor del testo: supporta metatag Suno o intestazioni italiane (Strofa, Ritornello, Ponte). Il testo senza intestazioni **non** riceve sezioni inventate.
- Generatore autonomo di Style, Lyrics ed Exclude con copia e modifica di ogni campo.
- Suggerimenti Variety 0 (Precisa) o indicazione sperimentale 35 (Creativa), non modifica di Suno.
- Export JSON locale della scheda esperimento, senza credenziali.
- Laboratorio avanzato: preservate funzioni, preset e motore v40 dentro un pannello espandibile.
- La landing commerciale `index.html` non è stata modificata.

## Verifiche tecniche effettuate
- Controllo sintattico JavaScript del motore rapido.
- 3 preset × 3 modalità vocali, senza crash con mock DOM.
- Tutti i prompt rapidi Style verificati con lunghezza < 850 caratteri.
- Verifica output e codifica Lyrics con tag già esistenti, intestazioni italiane e testo non etichettato.
- Presenza dei controlli v40 e dei suoi 11 pannelli nel file distribuito.
- File e commit verificati su GitHub main.

## Stato e limiti
- **Non è ancora stato svolto un collaudo visivo/interattivo in Safari iPhone o Chrome reale.**
- **Non sono ancora state eseguite generazioni su Suno v6**: BPM, miscelazioni e risultati sono ipotesi di produzione da validare.
- **Non è attiva una preview Vercel dedicata**: tentativo di creazione progetto fallito con errore autorizzazione Vercel 403 sul team collegato. Non esiste un URL pubblico verificato da pubblicare.
- Il CSS/JS v40 resta nel file Beta: la v41 semplifica **l'esperienza**, non ancora il peso del bundle.
- La modalità avanzata riutilizza euristiche v40, incluso il Compatibility Score, che **non** rappresenta una metrica ufficiale Suno.

## Prossime verifiche
1. Ripristinare permessi della connessione Vercel prima del deploy, oppure scegliere deliberatamente GitHub Pages con impostazioni autorizzate.
2. Verificare in Safari iPhone e desktop: apertura, navigazione v41, editor, copia, export JSON, pannello avanzato.
3. Testare 2 generazioni per preset v6 (prima modalità Precisa, Variety 0) senza assumere resa garantita.
4. Sostituire, se approvato, il bundle base64 monolitico con sorgenti separati e build offline; solo dopo i test.
5. Aggiornare la Bibbia con i test e correggere euristiche v40.

**Nessuna modifica a credenziali o dati privati, nessun file musicale toccato.**
