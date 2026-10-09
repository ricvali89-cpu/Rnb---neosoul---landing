# BIBBIA PROMPT SUNO v6 — VRicky R&B · Neo Soul · Funk

**Versione documento:** 1.4.0 — 10/10/2026  
**Stato:** BASE DOCUMENTATA / REGISTRO SPERIMENTALE APERTO  
**Repository:** ricvali89-cpu/Rnb---neosoul---landing (main)  
**Tool di partenza:** R&B Neo Soul Studio v40, codice incorporato in index.html  
**Ambito:** composizione testi originali, Style, Lyrics, Exclude, sperimentazione e diagnostica v6.  
**Controlli diretti VRicky su v6:** **PARZIALMENTE DOCUMENTATI** — esiste un MP3 generato con Style Future Soul e misurazioni tecniche su Drive; interpretazione di strumenti, voce, qualità artistica e parametri effettivi di Suno restano **DA_VERIFICARE**. Le prove descritte come protocolli sotto non si considerano eseguite.  

> **Principio di onestà:** distinguere sempre DOCUMENTATO (documentazione ufficiale o codice effettivo), DICHIARATO (preferenza/decisione dell'autore), DA_VERIFICARE (ipotesi da testare), STORICO (comportamenti di modelli precedenti), SUPERATO (indicazioni smentite o non più applicabili). Reddit, blog e testimonianze sono osservazioni con campione e metodo variabili, mai garanzie di comportamento.

## 0. Indice

1. Identità artistica e riferimenti
2. Evidenze ufficiali v6
3. Osservazioni indipendenti e limiti
4. Il DNA sonoro VRicky
5. Scrittura dei testi
6. Come costruire Style, Lyrics ed Exclude
7. Template pronti
8. Impostazioni modello e slider
9. Diagnostica — sintomo → intervento
10. Protocollo A/B e valutazione
11. Audit dello Studio v40 / interventi futuri
12. Sicurezza creativa, versione e governance
13. Registro esperimenti VRicky
14. Fonti e data di consultazione
15. Protocollo Lyrics v41.2
16. BPM e controllo tempo
17. Changelog

## 1. Identità artistica: non cambiare genere per inseguire gli hack

**DICHIARATO dall'autore (09/10/2026):** la musica VRicky è soprattutto un mix di **R&B moderno + Neo Soul + Funk**, tra sensualità/atmosfera notturna e groove brillante/orecchiabile. Riferimenti di direzione, non modelli da clonare: il funk melodico, i cori e l'energia scenica associabili ad alcuni brani di Bruno Mars; l'intimità, il falsetto e le atmosfere elettroniche notturne associabili ad alcuni brani di The Weeknd.

- **Vincolo d'identità aggiornato 10/10/2026:** per nuove canzoni partire preferibilmente da Future Soul melodico/romantico con pocket Alternative R&B, armonie Neo Soul e texture elettroniche sobrie; Contemporary R&B e Funk restano sfumature disponibili e non sono eliminati. Un'identità principale per brano; il genere non obbliga a usare gli stessi strumenti su tutte le produzioni.
- **Originalità:** evitare richiesta di duplicare la voce identificabile, una melodia, un brano o un arrangiamento specifico di artisti reali. Tradurre i riferimenti in proprietà sonore osservabili.
- **Consistenza tra brani:** «firma» definita di volta in volta per voce, timbro/ambiente, basso e rapporti di mix, senza bloccare tutti gli elementi creativi.

### Future Soul — nuova firma sonora preferita (DICHIARATO 10/10/2026)

Dopo aver generato **The Past Future**, l'autore dichiara di apprezzare moltissimo lo Style Future Soul utilizzato e di volerlo usare come **punto di partenza abituale per le sue prossime canzoni** («lo userei per tutte le mie canzoni»). La preferenza riguarda il **DNA sonoro comune**, non una direttiva di copiare alla lettera ritmo, strumenti, mood, melodia o interpretazione a ogni brano. Il precedente mix R&B / Neo Soul / Funk rimane parte dell'identità, non è stato cancellato.

**Style originale effettivamente usato, conservato senza modifiche:**

```text
Future Soul With Alternative R&B Pocket, Neo-Soul Harmony And Tasteful Electronic Textures, Warm Heartfelt Romantic, Moderate 4/4 R&B Groove, Unhurried Backbeat And Balanced Syncopation, 98 Bpm Target, Steady Pulse, Balanced Expressive Dynamics, Modern R&B Drum Kit, Crisp Controlled Kick And Rimshot, Articulate Analog Synth-Bass Pulsing With Kick, Intimate Felt Upright Piano, Soft Warm Chords, Smooth Monophonic Synth Lead Answering Vocals, Steel-String Acoustic Guitar, Delicate Syncopated Strums, Small Orchestral Violin Section Swelling In Chorus, Warm Male Lead, Intimate Verses, Soulful Chorus And Selective Falsetto, Mixed Male And Female Backing Vocals, Restrained Airy Layered Harmonies Behind The Lead, Verses Lift Into A Melodic Chorus, Short Natural Outro.
```

- **Firma da mantenere secondo la canzone:** groove R&B sincopato e naturale; armonie Neo Soul; calore emotivo; elettronica misurata; voce personale VRicky selezionata in Suno, armonizzazioni e falsetto usati con intenzione; cura per progressione, ritornello e dinamiche.
- **Variabili da adattare al testo:** BPM (98 è solo il target del singolo esperimento), intensità, groove, tonalità, strumenti singoli (anche piano/archi/chitarra possono essere omessi), sfumature romantiche, malinconiche o energiche. Non aggiungere instruments non selezionati né rendere tutti i brani uguali.
- **DICHIARATO:** l'autore giudica la resa di *The Past Future* «super bene» ed esprime forte preferenza per lo Style completo; **DOCUMENTATO:** file audio MP3 recuperato su Drive e misure tecniche registrate nel registro Notion; **DA_VERIFICARE:** esito di ascolti professionali comparativi, generalizzabilità dello Style su testi diversi, piena conformità degli strumenti richiesti e valori BPM in nuove generazioni.
- **Metodo:** riutilizzare Lyrics e persona vocale quando appropriato, personalizzare lo Style per ciascuna canzone, conservare originale e varianti, valutare quale versione serve meglio la canzone. Non si assume disponibilità di Remix nel piano base.

## 2. Cosa è ufficialmente documentato su v6

Fonte primaria Suno 09/09/2026: [S1], [S2], [S3], [S4].

- **DOCUMENTATO:** modelli **v6** (precisione, abbonamenti Pro/Premier), **v6-wild** (variazione/esplorazione, Pro/Premier), **v6-mini** (velocità e ideazione, accessibile a tutti). Non presupporre che v6-mini abbia qualità inferiore per ogni genere: verificare caso per caso.
- **DOCUMENTATO:** fino a **8 minuti per generazione** su tutti e tre; NON è garanzia di durata specifica.
- **DOCUMENTATO:** migliore interpretazione delle istruzioni musicali per voci, strumenti, struttura, atmosfera e riferimenti; la risposta effettiva alle singole istruzioni rimane probabilistica.
- **DOCUMENTATO:** è possibile partire da input multipli (testo, audio, immagini, video), mixare fonti proprie, modificare una sezione/testo, utilizzare editing/Remix/Extend/Cover secondo funzioni e piani disponibili.
- **DOCUMENTATO:** **Variety** può riscrivere/arricchire gli Style prompt. Suno suggerisce **Variety = 0** quando serve preservare interamente i propri tag di stile [S3].
- **DOCUMENTATO:** **Max Mode** costa più crediti ed è consigliato da Suno soprattutto per brani più lunghi di due minuti, Covers fedeli, trasferimento di stile e continuità vocale/stilistica lungo il brano. **Non** implica risultato garantito [S3].
- **DOCUMENTATO:** Custom Mode consente di usare testi originali; Exclude è un campo distinto in Advanced Options [S5], [S6].
- **DOCUMENTATO:** Suno conferma che gli original lyrics forniti dall'utente restano dell'autore [S5].
- **DOCUMENTATO:** le modalità Simple e Custom sono disponibili come flussi di partenza; la promessa di Suno per v6 include istruzioni più complesse anche in Simple [S3].
- **ATTENZIONE:** «Variety», «Weirdness», «Style Influence», «Audio Influence», «Max» e le rispettive interfacce possono cambiare: registrare nel diario modello, piattaforma, piano e valori visibili al momento del test.

## 3. Evidenze da creatori e analisi esterne — non leggi

### 3.1 Riscontri favorevoli o utili
- **COMMUNITY TEST DIRETTO:** alcuni utenti che hanno rigenerato molti brani riportano migliore coerenza con indicazioni di produzione specifiche: «il basso si incastra nella cassa» anziché «super funky». Raccomandano un'identità, un groove, i ruoli degli strumenti, la voce per sezione, l'arco e il mix [C1], [C2], [C3].
- **COMMUNITY TEST DIRETTO:** prove incentrate sui ritornelli riferiscono che cambiare **prosodia e impaginazione dei testi** (versi brevi/asimmetrici, pause, ripetizioni) può rompere un ciclo di topline troppo simili [C4].
- **COMMUNITY TEST DIRETTO CON BRANI DI RIFERIMENTO:** «Root Funk Radio» pubblica una traccia v5.5 e una playlist di test v6, da usare come caso di studio funk, non come prova statistica [C5].
- **COMMUNITY TEST DIRETTO:** alcune guide con esempi R&B/Neo Soul propongono pocket rilassato, Rhodes con accordi estesi, ghost notes, chitarra in risposta alla voce, cori selettivi [C6].
- **TEST AUDIO INDIPENDENTE LIMITATO:** un autore ha confrontato tre canzoni tra v5.5 e tre modelli v6 misurando LUFS e True Peak. In due tracce con WAV/MP3, i v6 avevano loudness integrato coincidente fra formati, mentre v5.5 mostrava differenze. **Non** dimostra superiorità timbrica generale, si limita a poche misure e pochi brani [I1].

### 3.2 Difetti segnalati con frequenza
- **COMMUNITY TEST DIRETTO:** alcuni autori riferiscono produzioni v6 troppo omogenee, ritornelli generici, chitarre che spariscono, volume e timbro vocali instabili, mix ovattato, dinamica che collassa nella seconda metà, finali tagliati [C1], [C7], [C8], [C9].
- **SPECIFICO FUNK:** un musicista riferisce oltre 130 generazioni con difficoltà a ottenere vero funk anziché blues/rock/soul [C10]. Un'altra discussione sul Brazilian funk evidenzia basso troppo poco presente e batteria piatta; è un sottogenere diverso dal nostro, quindi usarla solo come segnale di rischio, non assimilare i generi [C11].
- **SUI RIMEDI:** utenti diversi riportano risultati opposti su Max, slider, metatag e posizionamento delle istruzioni. Esistono commenti che non ottengono miglioramenti con nessun tipo di prompt [C7], [C12].
- **DISCUSSIONI COMPILATE CON IA:** [C6] e alcune «guide definitive» aggregano anche materiale generato da LLM; NON certificano test replicabili indipendenti. Dare più peso a resoconti con link audio, valori impostati, iterazioni contate e descrizione del confronto.

**Conclusione prudente:** la buona formulazione del prompt aumenta la chiarezza delle richieste, ma non corregge necessariamente limiti strutturali del generatore.

### 3.3 Facebook e piattaforme social
- La ricerca pubblica del 09/10/2026 non ha prodotto **post Facebook con test v6 verificabili, metodologia e audio confrontabili**. **DA_VERIFICARE**, nessuna regola basata su Facebook per ora.
- Se emergeranno prove accessibili, conservare URL, data, autore, numero generazioni, prompt, audio e impostazioni. Non trattare screenshot anonimi come prova conclusiva.

## 4. DNA sonoro VRicky: una griglia concreta

### Fondamenta
- **Identità:** modern Contemporary R&B / Neo Soul / Funk-R&B, armonicamente ricco ma comprensibile, con canzone e hook al centro.
- **Drum pocket:** kick e snare nitidi, ghost notes leggere, hi-hat controllati, lieve swing e intenzionale «laid-back feel». Specificare *come* deve muoversi il groove, non solo BPM.
- **Basso:** basso elettrico caldo o synth-bass secondo brano; linee sincopate che dialogano con il kick, fills fra le frasi, attacco definito. Evitare bassi solo sub che spariscono su piccoli diffusori.
- **Chitarra:** palm-mute/clean guitar, **syncopated sixteenth-note chops**, risposte brevi tra frasi vocali; wah-wah occasionale, se richiesto.
- **Tastiere:** Rhodes/Wurlitzer con voicing estesi, 7th/9th, comping ritmico negli spazi. Evitare pad continui se nascondono basso e voce.
- **Voce:** lead vicino, caldo, melodico; pronuncia chiara, intenzione conversazionale nei versi e maggiore apertura nei chorus; melismi e falsetto come *accenti selettivi*.
- **Arrangiamento:** strofa con spazio e groove udibile; pre-chorus apre la tensione; chorus espande armonie e ritmo; bridge introduce contrasto; ultimo chorus aggiunge 1–2 elementi invece di sommare tutto.
- **Mix:** bass/kick separati, voce in primo piano, transienti leggibili, chitarre ai lati senza assorbire il centro, riverbero controllato; lasciare naturale dinamica.

### Tre archetipi VRicky DA_VERIFICARE
1. **FUNK BRILLANTE**: 100–118 BPM indicativi, groove danceable live-feel, bass melodico elastico, chitarra a sedicesimi, clavinet/Rhodes, cori call-and-response; energia giocosa.
2. **NEO SOUL NOTTURNO**: 72–94 BPM indicativi, rimshot morbido e ghost notes, Rhodes 9ths, warm bass, lead intima, chorus armonicamente ricco, reverb corto.
3. **DARK R&B/FUNK MODERNO**: 85–110 BPM indicativi, disco/funk pocket misurato, synth analogici essenziali, chitarra clean sincopata, falsetto usato con parsimonia, atmosfera notturna; NON clonare timbri/melodie di artisti noti.

Gli intervalli BPM sono **scelte creative** per test iniziali, non regole Suno. Se il generatore ignora BPM precisi, favorire indicazioni sul time feel.

## 5. Bibbia TESTI — prima la canzone, poi il prompt

### 5.1 Prima di scrivere: brief di sei righe (DA_VERIFICARE come metodo VRicky)
1. **Nucleo drammatico** in una frase (cosa vuole il narratore / cosa lo ostacola).
2. **Punto di vista** (io/tu, tempo e distanza emotiva), coerente.
3. **Una scena visibile** (luogo, gesto, oggetto), non 5 metafore generiche.
4. **Contraddizione**: cosa dice la voce vs cosa fa/sente.
5. **Una frase-hook** breve e pronunciabile, che valga la pena ripetere.
6. **Arco**: cosa cambia fra primo verse, bridge e ultimo chorus.

### 5.2 Metodo di scrittura
- Favorire parole concrete, tensione e implicazione; evitare riempitivi come «sei tutto», «notte infinita», «cuore spezzato» senza un'immagine originale che le trasformi.
- **Versi:** dettagli e sviluppo; evitare due strofe che ripetono la medesima informazione. 4–8 righe per blocco come scelta editoriale iniziale, non requisito v6.
- **Pre-chorus:** spostamento armonico/ritmico ed emotivo, frase che apre domanda o urgenza.
- **Chorus:** 1 idea centrale, parole chiare, hook riconoscibile. Ripetizione intenzionale, non copia casuale dei versi.
- **Bridge:** nuova prospettiva, verità scomoda, scelta o inversione; ridurre band/armoniche per far risalire l'ultimo chorus.
- **Final chorus:** risoluzione/cambio piccolo ma percepibile, non aggiungere inutili parole.
- **R&B/Neo Soul:** righe cantabili, consonanti gestibili, spazi per respiri e pickup, interazione «call / response» solo dove crea musica.
- **Multilingua:** preferire una lingua portante per il brano; eventuali linee IT/ES/EN devono servire intenzione e prosodia, non essere riempitivi. Accenti e pronuncia da ascoltare.
- **Duetto:** definire turni vocali e pochi scambi ben motivati; non attribuire automaticamente il testo a un interprete se il modello non rispetta i tag.

### 5.3 Prosodia come parametro sperimentale
Se l'hook esce generico, cambiare prima **numero di sillabe, lunghezza/ordine delle righe, pausa, ripetizione breve, parola finale** del chorus tenendo fisso Style e preset; testare 2–3 varianti. Evidenza comunitaria [C4], non certezza.

Mini esempio **originale e dimostrativo**, non testo di un brano:
~~~
[Chorus]
Non dire niente
resta qui
un passo indietro
e poi... così

Non dire niente
guardami
lo sai già
che torni qui
~~~
Rivedere ripetizioni e qualità artistica per il brano concreto. Il segno «...» potrebbe essere interpretato diversamente; non diventa un comando certificato.

### 5.4 Checklist editoriale testi (pass/fail)
- Titolo coerente con il ritornello?
- Prima strofa racconta qualcosa, non solo aggettivi?
- Hook pronunciabile e riconoscibile entro il secondo ascolto?
- Cambia un'informazione o una posta in gioco nel bridge?
- Rime naturali, niente sintassi forzata?
- Prosodia compatibile col pocket e con la lingua?
- Nessun cliché non voluto / riferimento letterale a musica altrui?
- Finale soddisfacente?
- Metatag non pronunciati o cantati involontariamente?

## 6. Prompt: campi e priorità

### 6.1 STYLE: una **direzione di produzione**
Protocollo combinato: codice Studio v40 [R1] + osservazioni community [C2], [C3], [C6].
1. **Core identity**: un solo genere primario, Funk come descrizione del pocket e dell'incastro ritmico.
2. **Groove**: BPM approssimato, swing/backbeat, densità hi-hat, kick/snare.
3. **Basso e chitarra**: chi fa cosa, quando e in rapporto alla voce; non catalogo strumenti.
4. **Voce**: registro, timbro, articolazione, dinamica fra sezioni, cori come evento.
5. **Arco**: verse → pre → chorus → bridge → final chorus; differenze udibili.
6. **Mix**: primo piano voce, mid-bass controllato, reale separazione, stanza/reverb preciso.
7. **Ending**: tipo di conclusione coerente.

**Aggiustamento rispetto all'ordine del tool v40:** il codice ha nove blocchi nominali Genre, Vocals, Drums, Guitars, Bass, Other, Arrangement, Production, Ending e inserisce anche mood/key/BPM all'interno. Questa guida mantiene quei contenuti ma può riordinarli per leggibilità. La landing commerciale parla di «10 blocchi», mentre il generatore effettivo dichiara «9 blocchi». La differenza è **DOCUMENTATA**; non attribuire a Suno una gerarchia ufficiale né una regola fissa sui primi 20–30 termini.

**Lunghezza Style:** v40 segnala fino a ~850 caratteri come zona utile, 850–1000 denso e oltre 1000 critico; ~6 strumenti max. Questi sono **guardrail interni dello Studio**, **DA_VERIFICARE su v6 reale**, non limiti ufficiali. Prima versione: privilegiare brevità funzionale e osservare esito.

### 6.2 LYRICS: testo e direzione per sezioni
- **Conservativo / A-B iniziale:** metatag puliti [Intro], [Verse 1], [Pre-Chorus], [Chorus], [Verse 2], [Bridge], [Final Chorus], [Outro]. Le sezioni non sono istruzioni deterministiche.
- **Variante sperimentale:** aggiungere una sola descrizione di transizione su pochi punti, es. [Chorus: full backbeat, three-part harmonies], e testare contro la versione pulita. Reddit è discordante: alcuni riportano che dettagli nei lyrics migliorano l'esecuzione [C3]; v40 usa «tag puliti» come default [R1].
- **Non riscrivere tutta la produzione in ogni sezione**.
- **Finale v40:** [Instrumental Outro] → [Hard Stop] → [End]. **DA_VERIFICARE** se impedisce davvero cut-off. Provare contro [Outro] → [End] e valutare, non promettere.
- **Ad-lib:** utilizzare righe brevi/poche indicazioni ben localizzate (non continui «oh» automatici); vietato affermare che parentesi o markup garantiscano turni vocali.
- **Durata:** non usare «song duration 3:30» come un timer affidabile. Suno documenta un tetto massimo di 8 min, non un comando deterministico di durata.

### 6.3 EXCLUDE: campo distinto, poche esclusioni sensate
Suno conferma campo dedicato [S6].
- Evitare di riempire Style con «no ...» o descrizioni negative lunghe.
- Per il caso funk/R&B, selezionare solo elementi non desiderati **nel brano concreto**: «arena rock guitars, trap hi-hat rolls, operatic vocals, muddy reverb wash», ma non escludere un genere che è davvero richiesto.
- Limite **5–6 voci** suggerito dall'interfaccia v40, **non** da Suno. In A/B testare anche Exclude vuoto.
- Promuovere la parte positiva: «close dry lead above the instruments» è più azionabile di «not muddy».

### 6.4 Formato suggerito
~~~
STYLE:
[IDENTITÀ], [GROOVE], [RUOLO BASSO], [RUOLO BATTERIA], [CHITARRA/TASTIERE], [VOCE], [ARCO], [MIX], [ENDING].

LYRICS:
[Intro]
...
[Verse 1]
...
[Pre-Chorus]
...
[Chorus]
...
[Verse 2]
...
[Bridge]
...
[Final Chorus]
...
[Outro]

EXCLUDE:
[SOLO ELEMENTI NON DESIDERATI]
~~~

## 7. Tre Style-base pronti da testare (originali, non «risultati garantiti»)

### A. VRicky — FUNK BRILLANTE / R&B moderno (DA_VERIFICARE)
~~~
Contemporary R&B with bright neo-soul funk, 108 BPM, syncopated live-feel pocket with a tight kick/snare backbeat and restrained hi-hats, melodic electric bass locking with the kick and adding short fills, clean muted rhythm guitar chopping sixteenth-note offbeats, Rhodes playing warm 7th and 9th chords, confident warm male lead with conversational verses and open melodic chorus phrasing, selective short falsetto accents, call-and-response backing harmonies entering on the hook, stripped verses expanding into a danceable full-band chorus, punchy clean transients, clear vocal upfront, controlled reverb and defined bass, brief instrumental outro.
~~~
EXCLUDE **facoltativo**: operatic vocals, stadium rock guitars, boomy reverb wash.

### B. VRicky — NEO SOUL NOTTURNO (DA_VERIFICARE)
~~~
Modern intimate neo-soul and contemporary R&B, unhurried 82 BPM late-beat pocket, soft snare ghost notes and controlled kick, warm electric bass playing melodic answers between vocal phrases, Rhodes sustaining extended jazzy chord voicings, sparse clean guitar replies, mature warm male lead close to the microphone with clear soft articulation in verses, restrained melisma at line endings, the chorus opens into wider harmonies and longer held notes without shouting, bridge reduces to voice and keys before the rhythm returns, intimate detailed mix, bass and kick clearly separated, short room reverb, natural dynamics, gentle resolved outro.
~~~
EXCLUDE **facoltativo**: aggressive trap rolls, huge cinematic strings, distant vocals.

### C. VRicky — DARK ELECTRO R&B + FUNK (DA_VERIFICARE)
~~~
Nocturnal contemporary R&B rooted in syncopated funk, 96 BPM steady danceable pocket, dry punchy backbeat, warm articulate synth bass closely following the kick, clean funk guitar stabs answering the vocal, subdued analog synth chords and sparse Rhodes accents, intimate low-mid male lead in verses with carefully placed falsetto lifts on the hook, subtle stacked harmonies reserved for the final chorus, verse remains rhythmically active while the pre-chorus briefly thins the groove, chorus expands without losing drum/bass definition, tight stereo image, upfront voice, controlled ambience, natural transients, short instrumental outro.
~~~
EXCLUDE **facoltativo**: EDM drops, orchestral trailer percussion, washed-out vocals.

**Nota:** i valori 108/82/96 BPM, la descrizione voce e gli Exclude sono *ipotesi produttive*. Tararli con l'autore, non trattarli come la sua firma sonora già certificata.

## 8. Scelta modello e impostazioni

### Modalità 1 — Diagnosi controllata
- Modello **v6**, ove disponibile, o **v6-mini** per prove rapide.
- **Variety = 0**: scelta **DOCUMENTATA UFFICIALE** per evitare che Suno modifichi il nostro Style [S3].
- Style Influence / Weirdness: **non fissare valori universali**. Registrare impostazioni correnti e lasciarle costanti durante confronto.
- **Max Mode OFF** per abbozzi e A/B economici; poi ON per verificare se migliora coerenza nei candidati >2 min (Suno raccomanda il caso, ma i test Reddit sono discordi [S3], [C12]).
- Stessa lingua, stesso testo, stesso brief, generare più volte. Non cambiare prompt, slider e modello tutti insieme.

### Modalità 2 — Esplorazione
- v6-wild o Variety >0 solo dopo aver salvato il controllo; può riscrivere Style. Annotare e confrontare il **prompt realmente inviato**, non solo quello originale.
- Cercare groove/hook/idee migliori. Non assumere che «wild» sia sempre qualitativamente superiore.

### Modalità 3 — Rifinitura
- Se il ritornello è debole: testare prosodia del chorus.
- Se la seconda metà collassa: valutare Max (non garantito) e/o editing locale di sezione.
- Se una generazione ha ottimo groove ma cattiva voce: **editing, separazione tracce o mashup fra versioni proprie** prima di ricominciare.
- Conservare master/edit finale WAV quando possibile per eventuale master esterno; evitare dichiarazioni universali sulla qualità dei formati [I1].

## 9. Diagnostica operativa

| Sintomo | Intervento ipotizzato | Stato |
|---|---|---|
| Funk suona come pop/soul generico | Specificare offbeat sixteenth-note guitar chops + melodic bass locked to kick + ghost notes + groove danceable; togliere etichette vaghe | DA_VERIFICARE; [C10] segnala problemi non sempre risolvibili |
| Basso troppo indietro | Definire basso come protagonista melodico, mid-bass articulate, kick/bass separation e ruolo dei fills; ridurre pad | DA_VERIFICARE |
| Voce sommersa | Close dry vocal, vocals upfront above keys/guitar, controlled room; confrontare Exclude «reverb wash» | Comunità, [C3], [C13] |
| Mix ovattato | Defined low-mids, crisp transients, spectral separation; non sovraccaricare strumenti; testare remaster | Regola v40 [R1], non garanzia |
| Ritornello sempre uguale | Cambiare **metrica e spezzatura del testo** e aprire/collassare strumenti per contrasti udibili | Comunità [C4] |
| Voce muta timbro dopo metà | Annotare timecode, Max ON/OFF su stesso testo, riparare sezione invece di rigenerare tutto | Ufficiale Max [S3] + comunità discordante [C7], [C12] |
| Voce «lirica» non richiesta | Exclude opera; close-mic raw soulful male lead | v40 [R1] |
| Chitarra funky assente | Ridurre «other instruments», assegnare compito ritmico obbligatorio e confrontare con/ senza descrizione sezione | DA_VERIFICARE |
| Outro canta una frase tagliata | Confrontare v40 hard-stop protocol, outro semplice e editing/extend | v40 [R1]; efficacia non dimostrata |
| Risultato troppo generico | Ridurre accumulo di aggettivi, preservare pocket e compiti strumentali, provare v6-wild per idee | Comunità [C2], ufficiale [S1] |
| Canta i metatag | Testare tag più puliti senza descrizioni, niente prosa tecnica fuori parentesi nel campo Lyrics | DA_VERIFICARE |

## 10. Benchmark VRicky v6 — prima sperimentazione

**Niente «questo hack funziona» senza un confronto ripetibile.**

### 10.1 Tre microbrani di prova da produrre
- Test F — funk brillante / chitarra a sedicesimi / bassline protagonista.
- Test N — neo soul intimo / voce vicina e naturale / ghost notes / 7th & 9th chords.
- Test D — dark R&B/funk / armonie moderne / falsetto selettivo / chorus ampio.

### 10.2 Matrice sperimentale minima
Per **ciascuno**:
1. **A controllo:** Style-base, lyrics corti originali, Exclude vuoto, v6, Variety 0, Max OFF; almeno 2 generazioni per stimare variabilità.
2. **B ruoli strumentali:** identico ad A salvo frase di compito specifico alla chitarra/basso; almeno 2 generazioni.
3. **C prosodia:** stesso Style di A, varia solo la disposizione metrica del chorus; almeno 2 generazioni.
4. **D Exclude:** stesso A, poche esclusioni; almeno 2 generazioni.
5. **E Max:** stesso A, Max ON; almeno 2 generazioni se crediti permettono.
6. Solo dopo, **F Variety e/o v6-wild**, registrando eventuale Style riscritto.

Contare output effettivi, crediti spesi e non confrontare un risultato «fortunato» isolato con un altro modello. Se risorse limitate, partire da A/B sul solo Test F.

### 10.3 Scheda di valutazione per ogni output (scala 0–5)
- Fedeltà **R&B/Neo Soul/Funk** (funk udibile, non soltanto etichetta)
- Pocket batteria / microtiming / swing
- Basso: presenza, linea, relazione col kick
- Chitarra sincopata e sue entrate
- Voce: credibilità, dizione, timbro, dinamica
- Hook: memorabilità e prosodia
- Arrangiamento: contrasti e progressione
- Mix: chiarezza, stereo, basso/voce separati
- Stabilità dopo il 50–70% della durata
- Finale: naturalezza, nessuna parola troncata
**Totale /50**, con motivazioni + timestamp problematici; ascoltare su cuffie e speaker iPhone per bass translation.

### 10.4 Registro CSV/log (schema)
~~~
date,experiment_id,model,mode,source_track,style_version,lyrics_version,exclude_version,variety,weirdness,style_influence,audio_influence,max_mode,personalize_on,prompt_rewritten,credits,output_url,duration,score_50,problem_timestamps,decision,notes
~~~
Non salvare credenziali, URL di materiale privato condivisi pubblicamente, oppure audio personali non autorizzati.

## 11. Audit tecnico dello Studio v40 (R1)

**Verificato sul codice di index.html del repository — nessuna modifica al motore effettuata con questo documento.**

| Elemento v40 | Stato rispetto a nuove prove |
|---|---|
| Gerarchia 9 blocchi e voce all'inizio | DOCUMENTATO NEL CODICE; buona impostazione iniziale, priorità esatta non confermata ufficialmente |
| Descrizione «verbi d'azione» degli strumenti | DOCUMENTATO NEL CODICE; coerente con riscontri [C2] |
| Guardrail 850/1000 caratteri e massimo ~6 strumenti | REGOLA INTERNA, **DA_VERIFICARE** |
| Metatag puliti come default | REGOLA INTERNA; confrontare con metatag per-sezione |
| Outro '[Instrumental Outro] / [Hard Stop] / [End]' | REGOLA INTERNA; test A/B obbligatorio |
| Slider Variety auto 25–58 e Style Influence 82/88 | **DA_RIVEDERE PRIORITARIAMENTE**: per diagnosi controllata Suno consiglia Variety=0 [S3] |
| Ramo v6-wild automatico quando Variety alta | REGOLA INTERNA, non necessaria né ufficiale |
| «Passata v6-mini → finale v6» | Workflow ragionevole ma **non** certifica costi o qualità migliori in ogni caso |
| Firma voce/basso/mix/instrumenti salvata localmente | DOCUMENTATO NEL CODICE; non confondere localStorage del browser con salvataggio cloud |
| Compatibility Score interno | Euristica dello sviluppatore, **non** punteggio ufficiale Suno né validazione sonora |
| Preset neo-soul/funk con molti layer contemporanei | Fare riduzione controllata per non perdere il pocket |

**Raccomandazioni di modifica futura (NON APPLICATE):**
1. Aggiungere modalità «VRicky v6 — Controlled» con **Variety 0**, prompt preservato, logging completo.
2. Rendere i valori degli slider consigli e non automatismi, con distinte opzioni «Exploration».
3. Prevedere baseline Style «producer brief» con ruoli di basso/chitarra/voce e archi distinti.
4. A/B generator: tag puliti vs tag sezione dettagliati; outro standard vs hard-stop.
5. Inserire pulsante export JSON/csv della scheda esperimento, *senza* token né dati personali.
6. Misurare differenza tra score del toolkit ed esito d'ascolto, e ritarare euristiche.
7. Mantenere voce e strumenti della firma sonoro-artistica originali, non la somiglianza a cantanti noti.

## 12. Governance delle nuove scoperte

Ogni nuova tecnica deve avere una scheda:
- **Titolo / data / autore / URL / piattaforma / versione app Suno / modello / piano**
- **Tipo prova:** ufficiale / test pubblico con audio / resoconto aneddotico / teoria / prova nostra.
- **Campione:** quante generazioni, quanti brani, stesso input?
- **Controlli:** stessi lyrics, style, sliders, crediti, ordine ascolto?
- **Risultato** e **risultato contrario**.
- **Rischio** di stile generico, perdita di identità, peggioramento seconda metà.
- **Stato:** DOCUMENTATO / DICHIARATO / DA_VERIFICARE / STORICO / SUPERATO.
- **Decisione:** Aggiungere / Testare / Scartare / Ritirare, con numero versione.
- Non convertire correlazioni in «l'algoritmo di Suno fa sempre X».
- Per le release future Suno controllare **release notes ufficiali** e confrontare la data dei test; aggiornare senza cancellare lo storico.
- Non usare la guida pubblica come contenitore di bozze di testi musicali inediti, password, numeri account, credenziali o materiali privati.

## 13. Registro esperimenti VRicky

| Data | ID | Modello | Ipotesi | Prova/audio | Risultato | Stato |
|---|---|---|---|---|---|---|
| 2026-10-09 | BASE-000 | — | Prima versione della Bibbia basata su fonti | Nessuna generazione diretta | Protocollo pronto da verificare | DA_VERIFICARE |

**Primo passo quando l'autore inizierà v6:** condurre Test F - A (v6, Variety 0, Max OFF, Style e lyrics salvati), annotare due output prima di provare modifiche. Nessuna spesa senza richiesta esplicita dell'autore.

## 14. Fonti, link completi e limiti

**Consultazione: 09/10/2026.** Le date seguenti sono di pubblicazione dove disponibili.

### Fonti ufficiali (priorità massima)
- [S1] Suno, *Introducing v6*, 09/09/2026: https://www.suno.com/blog/introducing-v6
- [S2] Suno Help, *What's new in v6?*, 09/09/2026: https://help.suno.com/en/articles/13924801
- [S3] Suno Help, *v6 FAQ*, 09/09/2026: https://help.suno.com/en/articles/13924481
- [S4] Suno Help, *Current Models: v6*: https://help.suno.com/en/articles/13924737
- [S5] Suno Help, *Can I use my own lyrics?*: https://help.suno.com/en/articles/2415873
- [S6] Suno Help, *How do I exclude elements of a song?*: https://help.suno.com/en/articles/3161921
- [S7] Suno, *Release notes*: https://suno.com/release-notes
- [S8] Suno Help, *Song Editor*: https://help.suno.com/en/articles/6141505
- [S9] Suno Help, *Remaster*: https://help.suno.com/en/articles/8105281

### Test, discussioni e testimonianze (metodo variabile)
- [C1] Reddit, test/guida personale v6 (10 settembre; 109 upvote al momento della ricerca): https://www.reddit.com/r/SunoAI/comments/1wcyryw/unofficial_suno_v6_prompting_guide_what_has_been/
- [C2] Reddit, guida compilata da esperienze e fonti (12 settembre; include testo AI): https://www.reddit.com/r/SunoAI/comments/1wehqi9/suno_v6_prompting_guide_compiled_from_your_reddit/
- [C3] Reddit, autore fornisce riscritture di prompt e esempi di esecuzione sezione: https://www.reddit.com/r/SunoAI/comments/1wghdpr/v6_prompt_help/
- [C4] Reddit, utente riferisce confronti fra generazioni e cambiamento di prosodia: https://www.reddit.com/r/SunoAI/comments/1wcxd6r/suno_v6_has_lost_the_main_reason_i_used_suno/
- [C5] Reddit, test funk «Root Funk Radio», link playlist e brano precedente: https://www.reddit.com/r/SunoAI/comments/1wdwpmu/testing_the_sliders_and_options_for_covers/
- [C6] Reddit, guida aggregata con esempio Neo Soul: https://www.reddit.com/r/SunoAI/comments/1wehqi9/suno_v6_prompting_guide_compiled_from_your_reddit/
- [C7] Reddit, tre settimane di prove negative e degrado seconda metà: https://www.reddit.com/r/SunoAI/comments/1ws8ybp/suno_please_acknowledge_what_is_happening_with_v6/
- [C8] Reddit, prova 20+ rigenerazioni e molte melodie simili: https://www.reddit.com/r/SunoAI/comments/1wdij5y/suno_v6_is_a_massive_creative_downgrade/
- [C9] Reddit, lamentele v6 aggiornate 05/10: https://www.reddit.com/r/SunoAI/comments/1wybv48/what_is_going_on_with_v6/
- [C10] Reddit, 130+ creazioni; difficoltà a generare funk: https://www.reddit.com/r/SunoAI/comments/1wf9in2/the_5_scams_of_suno_and_v6/
- [C11] Reddit, Brazilian funk «V6 lost the magic» (sottogenere differente): https://www.reddit.com/r/SunoAI/comments/1wcqsvt/v6_lost_the_magic/
- [C12] Reddit, esiti Max contrastanti: https://www.reddit.com/r/SunoAI/comments/1wecg2l/new_option_with_v6_maxmode/
- [C13] Reddit, negative prompt per mix ovattato, metodo non isolato: https://www.reddit.com/r/SunoAI/comments/1wexy81/these_are_the_cover_settings_worked_for_me/
- [C14] Reddit, test controllato a cappella con lyrics tags: https://www.reddit.com/r/SunoAI/comments/1wbxnt7/title_suno_v6_pro_controlled_a_cappella_test_lead/
- [C15] Reddit, v6-creator «What I find to work»: https://www.reddit.com/r/SunoAI/comments/1wmy68m/what_i_find_to_work_on_v6/
- [C16] Reddit, esperienze con slider e Variety anche ai primi di ottobre: https://www.reddit.com/r/SunoAI/comments/1wxthhn/wtf_did_they_quietly_bake_in_variety_now/
- [C17] Reddit, consiglio sintetico da ~20 brani: https://www.reddit.com/r/SunoAI/comments/1wfhxg5/condensed_lessons_for_v6/
- [C18] Reddit, test di 12 brani con link confronti precedenti: https://www.reddit.com/r/SunoAI/comments/1wphbnq/comparison_of_my_12_favourite_songs_in_v45all_v50/

### Audio measurement indipendente — campione limitato
- [I1] WaveDisco, test di tre brani e misura LUFS/True Peak (20/09/2026): https://blog.wavedisco.com/blog/suno-v6-vs-v55-audio-test

### Codice repository
- [R1] Implementazione Studio v40, da cui derivano struttura e impostazioni locali: https://github.com/ricvali89-cpu/Rnb---neosoul---landing/blob/main/index.html

### Fonti escluse come conferme
- Portali che sembrano ufficiali ma non sono nei domini Suno (es. siti terzi che si presentano come «Suno AI Team») non sono fonti primarie.
- Guide scritte per v4.5/v5.5 non diventano automaticamente vere per v6.
- Facebook: nessuna prova con metodi e output identificabili reperita nella ricerca pubblica odierna.


## 15. Protocollo editor Lyrics v41.2 (nuove regole editoriali)

**DICHIARATO dall'autore:** il generatore deve proporre un lavoro musicale più approfondito sul testo: riconoscimento sezioni, cori maschili/femminili, armonizzazioni, pause, falsetto e variazioni d'energia secondo testo e strumenti scelti, senza perdere il controllo autoriale.

**Implementazione DOCUMENTATA nel codice [R2]:**
- Modalità **Mantieni i miei tag**: testo e metatag vengono restituiti esattamente come forniti. È la modalità conservativa per l'A/B baseline.
- Modalità **Suggerisci metatag musicali**: vengono lette le sezioni esplicite [Verse], [Chorus], [Pre-Chorus], [Bridge], [Final Chorus], [Intro], [Outro] oppure intestazioni italiane. Il riconoscimento da blocchi non etichettati avviene soltanto quando una strofa è ripetuta identica, con avviso di **inferenza DA_VERIFICARE**.
- Ogni sezione ottiene una proposta concisa di dinamica/interpretazione. Il tipo di cori deriva esclusivamente dalla scelta dell'utente; **Nessuno** equivale a non chiedere cori. Il falsetto può comparire come proposta sul ritornello per voce maschile; non viene attribuito automaticamente a voce femminile. Una sola pausa strumentale suggerita tra Bridge e Final Chorus quando esiste uno strumento melodico selezionato.
- I metatag già descrittivi dell'autore hanno precedenza; il testo cantato non viene riscritto.
- L'anteprima è modificabile prima di Copia; il sorgente originale resta immutato.
- Si tratta di regole JavaScript **non di analisi IA del significato profondo né di analisi audio**; identificazione semantica limitata ad alcune parole chiave. La compatibilità Suno v6-mini di parentesi descrittive e pause richiede test A/B audio reali, perciò i risultati rimangono **DA_VERIFICARE**.
- Per i primi test usare **v6-mini** come scelta gratuita dichiarata, modalità Precisa e Variety 0 se disponibile; v6 Pro da provare successivamente. Non inferire che il comportamento sia identico fra i modelli.

**Prima prova consigliata:** incollare la stessa canzone con tag espliciti; generare A mantenendo i propri tag e B con suggerimenti, lasciando invariati tutti gli strumenti e gli slider. Ascoltare due generazioni per ciascuna variante; confrontare presenza di cori, intelligibilità delle parole, cambi d'energia, pausa strumentale, interpretazione del falsetto e naturalezza. Documentare le anomalie per sezione.

- [R2] Codice v41.2: https://github.com/ricvali89-cpu/Rnb---neosoul---landing/blob/main/studio-v41.html

## 16. BPM e controllo tempo — aggiornamento 09/10/2026

**Conclusione:** non è DOCUMENTATO un parametro della generazione di **canzoni intere con v6-mini** che garantisca un BPM numerico esatto usando soltanto lo Style. Scrivere «96 BPM» è un'istruzione musicale, non un metronomo vincolante.

### Distinguere tre funzioni ufficiali
- **Canzone generata da prompt v6/v6-mini:** Suno documenta migliore comprensione di linguaggio, strumenti e struttura ma non certifica che il BPM testuale sia rispettato al numero esatto. Fonte [S1].
- **Suno Studio (DAW, Premier):** Project Tempo → Manual Tempo consente di impostare il BPM della timeline e adattare le regioni audio al tempo del progetto. Follow Track, metronomo e Warp Markers servono a gestire/correggere il tempo. È **editing del risultato**, non una garanzia della generazione iniziale. Fonti [B1], [B2], [B3].
- **Suno Sounds → Loop:** è documentata un'impostazione numerica BPM per il **loop/campione**, non per la generazione della canzone completa. Funzioni e accesso dipendono dal piano e vanno verificati nell'interfaccia. Fonte [B4].

### Prove e segnalazioni esterne
- Un utente riferisce di aver usato una demo con metronomo 129 BPM, impostazione «Fixed Tempo» e alta influenza audio, ottenendo un risultato a circa 130 BPM con drift: prova aneddotica, NON test controllato né esito universale [B5].
- Altri utenti v6 riferiscono mancata aderenza ai BPM, mentre alcuni hanno risultati migliori con istruzioni di arrangiamento dettagliate. Non dedurre una precisione percentuale senza dati. Fonte [B6].
- È possibile un errore di classificazione metà/doppio tempo: una traccia dal feel half-time può essere etichettata 48, 96 o 192 BPM da diversi beat tracker; non confondere «sensazione» con BPM metronomico.

### Protocollo VRicky da usare nei primi test v6-mini
1. **Obiettivo**: indicare BPM + feel, non forzatura: «96 BPM, steady 4/4 neo-soul funk pocket, tight kick and snare backbeat, syncopated electric bass locked to the kick, clean sixteenth-note funk guitar chops, consistent rhythmic pulse.»
2. Generare 2 campioni con numero BPM e ruoli strumentali; mantenere invariati testo, strumenti e slider.
3. Generare 2 campioni togliendo **solo** il numero BPM ma conservando il resto del prompt; confrontare senza alterare le altre variabili.
4. Ascoltare e, se possibile, stimare il BPM reale con beat detector/DAW; verificare la griglia su più punti della traccia, distinguere metà/doppio tempo e segnalare drift.
5. Non segnare «SUCCESSO» senza misurazione/ascolto. Annotare numero richiesto, numero misurato, stabilità e preferenza di groove.
6. Se serve BPM **esatto** per mix, registrazione o video, valutare correzione audio in un editor/DAW (es. Manual Tempo in Suno Studio se accessibile) e controllare artefatti di time stretching.

**Stato:** DOCUMENTATO il funzionamento di Studio e Sounds, DA_VERIFICARE l'efficacia dei prompt BPM su v6-mini. **STORICO / SUPERATO:** v41.2 derivava BPM da preset/energia. Studio v41.3 separa energia e velocità, con obiettivo BPM manuale, senza pretendere un lock metronomico.

### Implementazione Studio v41.3: cinque fasce e BPM manuali

| Etichetta rapida | Fascia indicativa | BPM rapido | Tempo percepito |
|---|---:|---:|---|
| Molto lento | 55–70 | 64 | 4/4 spazioso, senza double-time |
| Lento | 71–85 | 78 | Neo Soul morbido, non affrettato |
| Moderato | 86–100 | 94 | R&B midtempo bilanciato |
| Mosso | 101–115 | 108 | Funk/R&B ritmico e sincopato |
| Veloce | 116–140 | 124 | Groove brillante dal backbeat rapido |

Intervalli **DICHIARATI come convenzioni creative VRicky**, non classificazione ufficiale Suno. Nel motore v41.3 il campo manuale accetta interi 55–140 e aggiorna la fascia, senza arrotondamenti nascosti. I default iniziali di genere sono Funk 108, Neo Soul 82 e Dark 96; dopo scelta manuale si conservano anche cambiando genere.

**Regola:** energia modifica intensità/dinamica senza aumentare il BPM. Tempo <=85 inserisce groove disteso nello Style ed esclusioni per ska, double-time e ritmi affrettati. I sottotipi strumentali scelti rimangono invariati, con avviso in caso di batteria disco associata a tempo lento.

**Test funzionali DOCUMENTATI:** 45/45 combinazioni genere × fascia × energia corrette, Style proposti 705–850 caratteri; test audio v6-mini e Safari ancora DA_VERIFICARE. Il BPM resta un **obiettivo** e non un tempo garantito.
### Fonti — consultate 09/10/2026
- [B1] Suno Help, *Transport controls in Studio*: https://help.suno.com/en/articles/8121281
- [B2] Suno Help, *Introducing Suno Studio 1.2*: https://help.suno.com/en/articles/10625089
- [B3] Suno, *Introducing Suno Studio*: https://blog.suno.com/blog/suno-studio
- [B4] Suno Help, *Suno Sounds*: https://help.suno.com/en/articles/10625537
- [B5] Reddit, *Why can't it follow a simple metronome?*: https://www.reddit.com/r/SunoAI/comments/1wqjv5w/why_cant_it_follow_a_simple_metronome/
- [B6] Reddit, *v6 feels like a massive downgrade*: https://www.reddit.com/r/SunoAI/comments/1wbzbaj/suno_v6_feels_like_a_massive_downgrade_very/

## 17. Changelog

- **1.4.0 — 10/10/2026:** Future Soul romantico/cinematografico indicato dall'autore come nuova firma sonora preferita per le prossime canzoni; conservato Style originale di *The Past Future* e introdotte regole per adattarlo a ogni brano senza omologazione. Efficacia su più brani DA_VERIFICARE.
- **1.3.0 — 09/10/2026:** supporto alle cinque fasce di velocità, BPM target manuale e indipendenza dell'energia in v41.3.
- **1.2.0 — 09/10/2026:** integrazione fonti ufficiali BPM, distinzione prompt/DAW/Sounds e protocollo test v6-mini.
- **1.1.0 — 09/10/2026:** integrato protocollo doppia modalità Lyrics v41.2, report editor, suggerimenti musicali sperimentali e piano test gratuito v6-mini.
- **1.0.0 — 09/10/2026:** Bibbia iniziale, ricerca ufficiale + esperienze Reddit + singolo test audio indipendente, archetipi VRicky e metodologia A/B; nessuna generazione v6 o modifica al generatore HTML. Priorità di test: funk e Variety 0.
