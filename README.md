# Contesto: Navisio AI

Questo file dà il contesto a Claude Code. Nessuna proposta: il ragionamento sulla home lo facciamo insieme nella chat. Lo screenshot della home attuale lo fornisce Vittoria.

## Chi sono e perché questo progetto
Sono Vittoria Rossetti, UX/UI & Service Designer. Mi sto candidando come **Product & Project Manager in Navisio AI**. Il CEO mi ha mandato lo screenshot della home dell'app e mi ha detto: *"vedi tu cosa puoi farne"*. Nessun brief. Il suo principio dichiarato è **less is more**: semplificare il più possibile l'esperienza. Il prodotto non è ancora sviluppato, esiste solo la schermata.

Obiettivo del weekend: analizzare la home, proporre una direzione motivata e prototiparla in HTML (vibe coding), pubblicarla su Vercel e verificarla con Lighthouse.

## Cos'è Navisio AI
Sito: https://navisio.ai/it

- AI copilot per gli **intermediari assicurativi italiani**: broker, agenti mono e plurimandatari, collaboratori di agenzia, banche, compagnie, periti. **Non si rivolge al cliente finale.**
- Operativo da ottobre 2025, usato da **oltre 200 intermediari**. Tra le **Top 100 Startup Italiane 2025** di Forbes.
- Nato a **Torino** dentro **Nano I-Tech S.r.l.**, che è a sua volta un broker assicurativo (quindi ha broker in casa).
- Fondatori: **Sebastiano Andreis** (CEO, cura in prima persona design e UX) e **Simone Alberto** (CTO, guida lo sviluppo).
- Posizionamento: **l'AI non sostituisce l'intermediario, lo potenzia.** Meno tempo tra documenti ed email, più tempo per la consulenza al cliente. Dichiarano fino al 90% di tempo in meno sulle attività ripetitive.
- Descritto come sistema **multi-agente** che si integra nei processi esistenti; libreria normativa UE/IT; conforme a GDPR e AI Act; i dati restano di proprietà degli intermediari. Roadmap verso agenti AI più autonomi con controllo umano.
- Le risposte sono **tracciabili**: citano sempre le fonti (documento e pagina).

## Moduli del prodotto
- **Chat "Chiedi a Navisio"**: risponde su clausole, garanzie, esclusioni, limiti e normativa IVASS, citando le fonti.
- **Confronti**: confronta preventivi, set informativi, CGA e schede prodotto; evidenzia differenze in garanzie, massimali, franchigie ed esclusioni.
- **Sinistri**: guida nella gestione di un sinistro (procedura, responsabilità, documenti, prossimi passi).
- **Risk Analysis**: consulenza conforme IDD per PMI e privati.
- **Analisi portafoglio (in arrivo)**: carica il portafoglio di un cliente e trova le scoperture.
- **Libreria Navisio**: documenti dei prodotti delle principali compagnie (Generali, Allianz, AXA, Unipol, Zurich, Reale Mutua, ecc.).
- **Libreria privata / Drive**: documenti interni dell'agenzia, condivisi con il team.
- **Formazione**: corsi e formazione obbligatoria IDD.
- Export in PDF, Excel e DOCX; storico; analytics; documenti in lingua straniera.

## La home attuale (dallo screenshot)
Mobile. Dall'alto: avatar utente + logo NAVISIO.AI · titolo "Ciao Sebastiano, come posso aiutarti?" · sottotitolo "Nano i-Tech · giovedì 12 novembre" · sezione SUGGERIMENTI con 4 card (Confronta i preventivi di un cliente · Cosa copre questa polizza? · Trova un prodotto in libreria · Scrivi una mail di rinnovo) · grande spazio vuoto · input in basso "Chiedi a Navisio…" con un "+" · nav bar a 5 voci: Chiedi, Attività, Clienti, Drive, Storico.
Stile: sfondo crema, verde scuro, titoli serif, card bianche arrotondate, molto pulito e leggibile.

## Modello di business
- **Self-serve**: registrazione dal sito, prova gratuita, poi piano Singola Utenza a 99 €/mese + IVA. Nessun contatto con il sales.
- **Multiutenza**: da 49 €/mese per utente + IVA, per agenzie, broker e gruppi; add-on (risk analysis, workflow custom, account manager).
- **Enterprise**: banche, compagnie e reti di intermediari, con demo, onboarding, integrazioni e rollout.

## Chi è l'utente
Un intermediario che passa la giornata tra documenti (CGA di 50–100 pagine, set informativi, preventivi), email ai clienti, rinnovi in scadenza e sinistri aperti. Lavora a interruzioni: ufficio, telefono, cliente. Da mobile è spesso dal cliente. Ha bisogno di risposte affidabili e **motivate con la fonte**, perché deve spiegarle al cliente e risponderne.

## Glossario assicurativo
- **Intermediario**: chi sta tra compagnia e cliente (agente, broker, banca, collaboratore). Iscritti al RUI, registro tenuto da IVASS.
- **Compagnia**: crea le polizze e paga i sinistri. **Agente**: vende per conto della compagnia. **Broker**: lavora per il cliente e confronta più compagnie.
- **IVASS**: autorità di vigilanza. **IDD**: direttiva europea sulla distribuzione assicurativa; obbliga a valutare e documentare i bisogni del cliente e a formarsi ogni anno.
- **Premio**: quanto paga il cliente. **Sinistro**: l'evento dannoso. **Garanzia**: cosa è coperto. **Esclusione**: cosa non lo è.
- **Massimale**: il massimo che la compagnia paga. **Sottolimite**: massimale ridotto per un caso specifico. **Franchigia**: cifra fissa a carico del cliente. **Scoperto**: lo stesso, in percentuale.
- **Set informativo**: DIP/IPID (scheda di 2 pagine) + DIP aggiuntivo + **CGA** (Condizioni Generali di Assicurazione, il contratto completo).
- **Rami**: Danni (auto, casa, RC, aziende) e Vita. **RC**: responsabilità civile. **Portafoglio**: l'insieme dei clienti e delle polizze gestite.

## Il ruolo per cui mi candido (dall'annuncio)
Product & Project Manager che prende in mano il prodotto con CEO e CTO: roadmap e priorità (anche dire di no), discovery con broker e agenzie, user story e criteri di accettazione, sprint e rilasci (Jira), progetti con i clienti enterprise, crescita del funnel self-serve, misura di attivazione, utilizzo e retention. Modo di lavorare AI-native: prototipi, test e sviluppo passano da agenti AI.

## Come voglio lavorare con te
- Parti dal problema dell'utente, non dalla soluzione. Usa il glossario corretto.
- Ragiona con me prima di scrivere codice: domande, ipotesi, alternative.
- Quando prototipiamo: un solo `index.html` (HTML/CSS/JS vanilla), stile identico alla home attuale, mobile 390×844.
- Dopo ogni modifica significativa: commit su GitHub. Prima della consegna: Lighthouse (mobile), accessibilità ≥ 90.
- Scrivi in italiano, salvo i termini tecnici consolidati.
