# VRicky Studio v41 — Beta / note di rilascio

**Data:** 09/10/2026  
**Stato:** BETA ONLINE SU VERCEL (deployment READY); COLLAUDO MANUALE SAFARI/CHROME DA VERIFICARE  
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
- **Vercel: progetto separato creato e deployment READY**, https://vricky-studio-v41-beta.vercel.app — dominio verificato nel pannello Vercel, con protezione SSO disattivata esclusivamente per questo progetto beta. La verifica diretta via browser esterno/Safari non è ancora completata.
- **Build da GitHub:** progetto collegato a `ricvali89-cpu/Rnb---neosoul---landing` branch `main`; configurazione build `mkdir -p dist && cp studio-v41.html dist/index.html`, output directory `dist` per servire la v41 invece della landing. Build registrata come completata nei log Vercel.
- Il CSS/JS v40 resta nel file Beta: la v41 semplifica **l'esperienza**, non ancora il peso del bundle.
- La modalità avanzata riutilizza euristiche v40, incluso il Compatibility Score, che **non** rappresenta una metrica ufficiale Suno.

## Prossime verifiche
1. Verificare su iPhone Safari che https://vricky-studio-v41-beta.vercel.app apra effettivamente VRicky Studio v41 (e non la landing).
2. Verificare in Safari iPhone e desktop: apertura, navigazione v41, editor, copia, export JSON, pannello avanzato.
3. Testare 2 generazioni per preset v6 (prima modalità Precisa, Variety 0) senza assumere resa garantita.
4. Sostituire, se approvato, il bundle base64 monolitico con sorgenti separati e build offline; solo dopo i test.
5. Aggiornare la Bibbia con i test e correggere euristiche v40.

**Nessuna modifica a credenziali o dati privati, nessun file musicale toccato.**

## Aggiornamento v41.1 — 09/10/2026

**Stato:** DOCUMENTATO nel codice; test con DOM simulato superati. **Collaudo visivo iPhone e test sonori Suno v6: DA_VERIFICARE.**

Richiesta autore: mantenere personalizzazione profonda con **massimo 10 strumenti**, famiglie e sottotipi + opzione **Nessuno**. I preset sono suggerimenti, non impongono strumenti.

### Implementato
- 14 famiglie, 72 varianti in totale, opzione Nessuno per famiglia: Batteria, Basso, Percussioni; Piano, Organo, Sintetizzatori, Mallet e arpe; Chitarra elettrica, Chitarra acustica; Violino, Altri archi, Ottoni, Sassofono, Altri fiati.
- Selettore per ogni famiglia; massimo 10 famiglie attive contemporaneamente. Contatore 0/10–10/10; undicesima scelta annullata.
- Cori separati: Nessuno / solo maschili / solo femminili / misti; stili Soul, Funk call-and-response, Gospel, Eterei. Non consumano slot strumentali. Modalità strumentale disattiva i cori.
- Ogni selezione produce un'indicazione in inglese sul ruolo musicale; Nessuno non viene riportato nello Style.
- Rimossi riferimenti strumentali e ai cori forzati dal testo dei preset, che rispettano ora la strumentazione selezionata.
- Pulsante Carica strumenti suggeriti dal preset: sovrascrive *solo su richiesta* le scelte manuali. Il semplice cambio di genere le conserva.
- Pulsante Azzera strumenti. Con zero strumenti blocca la generazione senza inventare un arrangiamento.
- Export JSON include famiglie, sottotipi, tipo e stile dei cori.
- Conservato il laboratorio avanzato v40, non modificata la landing v40.

### Test
- 3 preset × 4 modalità cori = **12 test** con controllo del risultato e dell'assenza di cori se Nessuno.
- Verificata emissione soltanto degli strumenti effettivamente scelti.
- Limite 10 confermato, undicesima selezione respinta.
- I prompt con strumenti suggeriti sono sotto gli 850 caratteri; 10 strumenti personalizzati possono superare la soglia **interna**, senza troncare lo Style.
- Verifica sintattica JavaScript.
- Deployment Vercel successivo alla correzione finale: READY.

### Limiti / prossimi test
- Al momento si sceglie una variante per famiglia; due pianoforti o due chitarre elettriche simultanei richiedono una successiva estensione senza sforare il massimo di 10 strumenti.
- Collaudo visivo Safari iPhone ancora DA_VERIFICARE.
- Suono e fedeltà di Suno v6 ancora DA_VERIFICARE con generazioni reali.
- Il bundle HTML resta monolitico; la separazione in file sorgente è un'ottimizzazione futura.

**URL Beta:** https://vricky-studio-v41-beta.vercel.app

## v41.2 — Due modalità Lyrics con suggerimenti musicali

**Stato:** codice DOCUMENTATO e verificato con test simulati; interpretazione Suno **DA_VERIFICARE**.

- **Mantieni i miei tag (predefinito):** la copia dei Lyrics preserva ESATTAMENTE il testo inserito, compresi spazi, righe vuote e tag personalizzati; nessun [End] è aggiunto implicitamente.
- **Suggerisci metatag musicali:** elaborazione locale deterministica (non è IA). Interpreta sezioni già taggate o intestazioni italiane; prova a riconoscere ritornelli ripetuti identici nei blocchi senza tag; se gli indizi non bastano, non inventa sezioni.
- Per sezione propone **dinamiche, armonizzazioni e cori** secondo tipologia scelta (solo maschili / femminili / misti / nessuno), **falsetto** quando pertinente alla voce maschile e una breve **pausa strumentale** prima del ritornello finale quando sono presenti bridge e strumento melodico.
- Conserva i tag già dettagliati dell'autore: non li sovrascrive. Non riscrive alcuna parola del testo.
- **Anteprima Lyrics modificabile** accanto al pulsante Copia Lyrics; report riporta conteggio sezioni e suggerimenti. Input originale mantenuto separato.
- Esportazione JSON conserva versione originale, modalità selezionata e anteprima finale.
- Come modello di prova iniziale nella scheda export è suggerito **v6-mini**, Variety 0 in modalità Precisa. In futuro si confronterà v6 a pagamento, senza dati di test ancora acquisiti.
- Tag del tipo [Chorus: ...], [Instrumental Break: ...] sono **ipotesi sperimentali**, non comandi con esito deterministico confermato da Suno.
- **Test automatici (8 casi):** conservazione di tag/spazi, cori misti e falsetto, rispetto dei tag dettagliati, gestione testo senza struttura, conversione intestazioni italiane, ritornelli identici, disattivazione cori, brano strumentale. **8/8 riusciti** usando DOM simulato.

Il collegamento alla landing originale v40 non è stato toccato. La Beta dedicata su Vercel distribuisce automaticamente main. Collaudo visivo Safari e generazioni audio reali ancora DA_VERIFICARE.

## v41.3 — Velocità generale e BPM desiderati (09/10/2026)
**Stato:** DOCUMENTATO nel codice; collaudo sonoro v6-mini e Safari iPhone DA_VERIFICARE.

**DICHIARATO:** per le generazioni rapide serve distinguere fra cinque fasce di velocità e poter correggere il BPM target. Evitare che Energia alta acceleri un brano lento.

- **Molto lento:** 55–70 BPM; rapido 64. Pocket spazioso, senza passaggi double-time.
- **Lento:** 71–85 BPM; rapido 78. Neo Soul morbido, pause fra gli accenti.
- **Moderato:** 86–100 BPM; rapido 94. R&B midtempo bilanciato.
- **Mosso:** 101–115 BPM; rapido 108. Funk/R&B sincopato.
- **Veloce:** 116–140 BPM; rapido 124. Groove brillante dal backbeat deciso.
- Le fasce sono **euristiche di produzione VRicky**, non valori Suno ufficiali.
- Il numero BPM target accetta interi 55–140, riallinea automaticamente la fascia e blocca input vuoti/non validi. Cambiare fascia inserisce il suo default.
- Inizialmente il genere dà Funk 108, Neo Soul 82, Dark 96; dopo una personalizzazione dell'utente, cambiare genere **non cambia** i BPM manuali.
- **Energia** ora governa solo dinamica e intensità: alta energia + Lento conserva il tempo Lento.
- Se target <=85, Exclude aggiunge ritmiche ska/double-time/rushed. Non è una garanzia di conformità del modello.
- Style compatto: la priorità va a BPM, groove, mood, energia e strumenti. Compressi i riempitivi se necessari, senza troncare il prompt.
- Export JSON include tempoBand, bpmTarget, bpmStatus (DA_VERIFICARE); versione 41.3.0-beta.
- Test: 17 verifiche iniziali delle interazioni + 45/45 combinazioni (3 generi x 5 velocità x 3 energie), Style default 705–850 caratteri. Tutti test DOM simulato; non verificati audio o Safari.

**Beta:** https://vricky-studio-v41-beta.vercel.app
**Fonte:** studio-v41.html e Bibbia Prompt v6 (GitHub main).
