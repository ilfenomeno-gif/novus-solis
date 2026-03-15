# Changelog — Solis

## [1.1.3] — Hotfix: revert wrong -c corrections (2026-03-15)
- kamp → camp (reverted: -mp ending, rule does not apply)
- pok → poc (reverted: core adverb, protected word)
- pek → pec (reverted: core adverb, protected word)
- No other wrong changes found
- lak→lak and porc→pork confirmed correct, kept

## [1.1.2] — Phonological rule: -c ending (2026-03-15)
### Nuova regola: nessuna parola Solis può terminare in -c
- Applicata la regola ufficiale: nessuna parola Solis può terminare in -c
	- Tutte le parole di 1–2 sillabe terminanti in -c → -k (eccetto eccezioni: muzik, kul, nuit)
	- Tutte le parole terminanti in -ic → -ico (eccetto eccezioni)
	- fresc/fresk eliminati e sostituiti da sorave (formale) e cul (slang)
	- Nuovi lemmi: sorave, cul
- Aggiornati e corretti:
	- dictionary.html (array ALL, badge, note, fresc/fresk eliminati, nuovi lemmi)
	- semantic-fields.html (tutte le tabelle)
	- index.html (paradigmi, tabelle)
	- grammar/comparatives.html, grammar/adverbs.html, grammar/numerals.html, grammar/reflexives.html, grammar/passive.html, grammar/decisions.html, grammar/aspect.html
	- STATUS.md
- Correzioni totali: 7
	- lak (lac), kamp (camp), pork (porc), pek (pec), pok (poc), sorave/cul (fresc/fresk)
- Nessuna traduzione o voce eliminata (eccetto fresc/fresk → sostituiti)
- Vedi file per dettagli

Tutte le modifiche significative al progetto Solis sono documentate in questo file.  
Formato: [Semantic Versioning](https://semver.org/). Ordine cronologico inverso.

---

## [1.1.1] — Apocope je-verbs (2026-03-15)
### Nuova regola: apocope dei verbi dopo "je"
- Applicata la regola ufficiale: dopo "je", i verbi perdono la vocale finale -a/-o/-e (solo 1ª sing.)
- Aggiornati paradigmi e tabelle in:
	- index.html (paradigmi regolari -AR: caminava→caminav, caminaré→caminar, camine→camin, camineria→caminari)
	- diachrony.html (je amaria→je amari)
- Correzioni totali: 5
- Nessuna traduzione o voce eliminata
- Vedi file per dettagli

## [1.1.0] — Lexicon merge and annotation (2026-03-15)
### Fusione lessico ufficiale (PDF) + esteso (progetto)
- Tutti i lemmi Solis sono stati unificati tra la fonte ufficiale (PDF, badge ⭐) e il lessico esteso del progetto (badge ·)
- In caso di conflitto, la forma PDF vince sempre (nessuna traduzione modificata, nessuna voce eliminata)
- Ogni lemma ora riporta badge e commento di provenienza: ⭐ = ufficiale, · = esteso
- Aggiornati: dictionary.html (array ALL), semantic-fields.html (tutte le tabelle)
- Correzioni fonologiche e annotazioni applicate ove necessario
 - Conteggio finale: 153 voci totali, di cui 120 ufficiali (⭐), 33 estese (·)
- Vedi file per dettagli e badge


## [1.0.1] — Phonological revision (2026-03-15)
### Correzioni fonologiche Solis
- scarps → scarpa (evita cluster finale, preferisce vocale finale)
- arbr → arbre (aggiunta vocale finale per fluidità)
- forquet → forqueta (aggiunta vocale finale per fluidità)
- cuilher → cuilhera (aggiunta vocale finale per fluidità)
- got → goto (aggiunta vocale finale per fluidità)

---

## [1.0.0] — 2025

### Prima versione pubblica

#### Grammatica — completato
- **Morfologia verbale regolare:** paradigmi completi per -AR, -ER, -IR su tutti i modi e tempi (presente, imperfetto, futuro, condizionale, congiuntivo presente e imperfetto)
- **Verbi irregolari:** tavole complete per 12 verbi fondamentali — *esser, aver, andar, venir, far, dir, estar, poder, voler, saber, tener, meter* — con tutti i tempi, PP, gerundio, imperativo, note etimologiche e confronto pan-romanzo
- **Dittongazione accentuale:** regola e→ie / o→uo, lista produttiva (12 verbi e→ie, 12 verbi o→uo), eccezioni documentate, apofonia e→i come terzo pattern minore
- **Tempi composti:** passato prossimo (ver/ez), trapassato, futuro anteriore, condizionale passato — regola definitiva sull'ausiliare e sull'accordo del PP
- **Congiuntivo:** presente e imperfetto per tutte e tre le classi; irregolari documentati
- **Passiva:** sistema completo con *ez* (10 tempi) e con *se*; agente con *da/por*; regola definitiva sull'accordo del PP
- **Riflessivi e pronominali:** riflessivo proprio, reciproco, intransitivo pronominale, *se* passivante e impersonale
- **Aspetto verbale:** mappa completa — imminenza, inizio, progressivo, continuazione, fine; confronto con IT/ES/FR
- **Verbi modali:** *poder, voler, dever, tener que* + semi-modali (*saber, far, soler, osar, laissar*); modale + infinito passato
- **Comparativi e superlativi:** maggioranza/minoranza/uguaglianza; superlativo relativo e assoluto (*-isim*); irregolari latini (*meior, peior, maior, menor, superior, inferior*)
- **Avverbi:** sistema produttivo in *-ament*; avverbi di luogo, tempo, modo, grado; posizione nella frase
- **Numerali:** cardinali 0–miliardo, ordinali con suffisso *-esim*, frazionari, collettivi in *-ena*
- **Derivazione morfologica:** 9 prefissi produttivi (*re-, des-, in-/im-, pre-, sub-, super-, auto-, inter-, extra-*); 8 suffissi nominali; 5 suffissi aggettivali; tipi di composizione
- **Sintassi dell'accordo:** PP nei tempi composti, pronomi relativi completi, concordanza dei tempi nel discorso indiretto
- **Sistema nominale:** genere, numero, articoli determinativi e indeterminativi, preposizioni e contrazioni (*del, al*)
- **Pronomi:** sistema soggetto completo (incluso *zo* neutro), clitici OD/OI, ordine, relativi, riflessivi

#### Decisioni codificate
- **Condizionale:** *-aria/-eria/-iria* = Core standard (IT/ES/PT) · *-ev/-evs* = Solis Fralis esclusivo
- **Pronome neutro *zo*:** codificato come terza persona singolare neutra/non-binaria, simmetrico a *ez/za*
- **Accordo PP:** invariabile nei tempi composti attivi e nella passiva (Core standard); obbligatorio solo in funzione aggettivale
- **esser vs estar:** distinzione facoltativa nel Core; raccomandata nello scritto formale; obbligatoria in Solis Iberic

#### Lessico
- Dizionario di 300+ voci con etimologia e traduzione italiano/inglese
- Organizzazione per campi semantici: saluti, cortesia, persone, famiglia, corpo, casa, natura, colori, cibo, emozioni, tecnologia, trasporti, sport, economia, politica, religione, arte, derivazione
- Modalità flashcard integrata
- Campi semantici dettagliati: corpo umano (con organi e parti del viso), casa, natura (paesaggio, animali, piante, meteo), tempo e calendario (giorni, mesi, stagioni)
- Regola esplicita per neologismi e calchi: radice latina/greca → calco interno → prestito adattato

#### Fonetica e prosodia
- Sistema dei 5 fonemi vocalici
- Consonanti speciali: J /j/, Z /ts/, G davanti a e/i /dʒ/, legatura vocalica
- Accento tonico: penultima sillaba per default; accento grafico per eccezioni
- Sandhi e fenomeni fonetici contestuali
- Adattamento dei prestiti alla fonologia Solis

#### Diacronia e filologia
- Linea del tempo: dal latino classico al proto-romanzo a Solis
- Evoluzione fonologica: perdita delle quantità vocaliche, consonanti finali, lenizione
- Evoluzione morfologica: perdita del sistema casuale, nascita dei tempi composti e dell'articolo
- Matrice delle scelte: fonte primaria per ogni fenomeno morfologico e fonologico
- Tavola comparativa di 20 lemmi fondamentali (LAT → IT/ES/FR/PT/CAT → Solis)
- Distanza lessicale rispetto alle sei lingue sorgente

#### Interfaccia web (`index.html`)
- Navigazione a sezioni: Grammatica, Verbi, Lessico, Fonetica, Storia
- Grammatica interattiva a schede: coniugazione, pronomi, articoli, comparativi, modali, numeri, avverbi, aspetto verbale, decisioni codificate
- Tavole dei verbi irregolari con navigazione per verbo
- Lessico con ricerca full-text, filtro per categoria, modalità tabella e flashcard
- Sezione fonetica con regole e IPA
- Sezione storia con timeline e tavola comparativa pan-romanza

---

## Decisioni aperte (da risolvere in v1.1)

- **Eventivo** — modo per azioni involontarie: marcatura `[Eventivo]` sul congiuntivo imperfetto vs paradigma autonomo; uso solo scritto formale vs anche orale
- **Grammatica Estesa v4** — documento unificato che incorpora tutti i supplementi prodotti

---

## Backlog

- Fonetica v2: sandhi avanzato, allofoni, prosodia del discorso, fonetica emotiva
- Grammatiche delle varietà regionali (Fralis, Iberic)
- Testi autentici in Solis (narrativa, poesia, prosa saggistica)
- Dizionario espanso (obiettivo: 1000+ voci)
- Audio pronuncia di riferimento
