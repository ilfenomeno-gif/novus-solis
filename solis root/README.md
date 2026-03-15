# ✦ Solis — Lingua Romanza Pianificata

> *Solis est donat a tots ki aman las lengas romansas.*

**Solis** è una lingua romanza pianificata, progettata per essere naturale, fluida ed espressiva. Non è un algoritmo: è un organismo. Si basa sul patrimonio lessicale e grammaticale di italiano, spagnolo, francese, portoghese e catalano, ne eredita la vitalità — irregolarità comprese — e le distilla in una forma che chiunque parli una lingua romanza può riconoscere, e imparare, quasi senza sforzo.

---

## Filosofia del progetto

La domanda che ha generato Solis è semplice: *è possibile costruire una lingua romanza che suoni vera?*

La maggior parte delle lingue pianificate sceglie la regolarità totale. Solis fa la scelta opposta: mantiene le irregolarità dove queste sono morfologicamente radicate nel latino e riconoscibili nell'area pan-romanza. *Esser* è irregolare come *être*, *essere*, *ser*. *Andar* ha tre radici come in italiano, spagnolo, francese. Il dittongo accentuale (*pierd*, *puod*) funziona esattamente come in spagnolo e in italiano antico.

Il risultato è una lingua che non si sente artificiale. Chi parla italiano o spagnolo la capisce a prima lettura. Chi studia il latino la riconosce. Chi viene dal francese o dal portoghese trova echi familiari ovunque.

### Principi fondativi

**Naturalezza sopra la regolarità.** Quando la regolarità produce forme che suonano meccaniche o non hanno radici storiche solide, Solis preferisce la forma organica. Le lingue vive hanno eccezioni: quelle eccezioni sono la loro memoria.

**Massima intercomprensione.** Ogni scelta lessicale e morfologica è pesata sulla sua trasparenza rispetto all'insieme delle cinque lingue sorgente. Se una forma è riconoscibile in almeno tre di esse, ha la precedenza.

**Il parlante al centro.** Solis non è un documento accademico. È una lingua per essere parlata, scritta, cantata, maledetta e sussurrata. Il sistema dei registri — da colloquiale a giuridico — riflette questa ambizione.

**Occitano e catalano come cardine.** Le due lingue di mezzo tra Italia e Iberia occupano un posto privilegiato. Forme come il participio passato in *-at/-ut*, il pronome *je*, l'articolo *le/la/los/las* derivano direttamente dall'area occitano-catalana, che è geograficamente e tipologicamente il punto di convergenza massima del romanzo.

---

## Struttura del progetto

```
solis/
├── README.md              — questo file
├── CHANGELOG.md           — storia delle versioni e delle decisioni
├── STATUS.md              — stato di avanzamento della documentazione
├── index.html             — interfaccia web integrata (grammatica + lessico + fonetica)
│
├── grammar/               — moduli grammaticali
│   ├── verbs-regular.html      — coniugazione -AR / -ER / -IR
│   ├── verbs-irregular.html    — 12 verbi irregolari, tutti i tempi
│   ├── diphthongs.html         — dittongazione accentuale e→ie, o→uo
│   ├── modals.html             — poder, voler, dever, tener que
│   ├── passive.html            — passiva con ez e con se
│   ├── reflexives.html         — riflessivi, reciproci, impersonali
│   ├── aspect.html             — aspetto verbale e perifrasi
│   ├── comparatives.html       — comparativi, superlativi, irregolari
│   ├── adverbs.html            — avverbi e sistema in -ament
│   ├── numerals.html           — cardinali, ordinali, frazionari
│   └── decisions.html          — decisioni codificate (condizionale, zo, esser/estar…)
│
├── lexicon/               — vocabolario
│   ├── dictionary.html         — dizionario completo con flashcard
│   └── semantic-fields.html    — campi semantici (corpo, casa, natura, tempo…)
│
├── phonetics/             — fonetica e prosodia (in sviluppo)
│   └── phonology.html          — sistema fonologico, sandhi, prosodia
│
└── history/               — diacronia e filologia
    └── diachrony.html          — dal latino a Solis, fonti per ogni scelta
```

---

## Panoramica grammaticale rapida

### Fonologia

Solis ha una base fonetica trasparente: in linea generale si pronuncia come si scrive. L'accento tonico cade sulla penultima sillaba per default; se cade altrove è segnato dall'accento grafico (*caminár*, *canción*).

| Grafema | Pronuncia Core | Note |
|---------|---------------|------|
| **j** | /j/ | come *i* semivocalica in *ieri* |
| **z** | /ts/ | come *pizza* |
| **-** (legatura) | unione vocalica | *le-om*, *je-ez* |
| **g** + e/i | /dʒ/ | come *giorno* |
| **c** + e/i | /tʃ/ | come *cena* |

### Morfologia nominale

| | Maschile | Femminile |
|---|---|---|
| **Singolare** | *le libr* | *la femna* |
| **Plurale** | *los librs* | *las femnas* |

Il plurale si forma aggiungendo **-s**, come in spagnolo, portoghese e catalano. Il genere grammaticale funziona come in italiano e spagnolo; l'aggettivo concorda.

### Pronomi personali

| Persona | Soggetto | OD | OI | Riflessivo |
|---|---|---|---|---|
| 1ª sing. | *je* | *me* | *me* | *me* |
| 2ª sing. | *te* | *te* | *te* | *te* |
| 3ª m. | *ez* | *lo* | *li* | *se* |
| 3ª f. | *za* | *la* | *li* | *se* |
| 3ª neutro | *zo* | *lo* | *li* | *se* |
| 1ª pl. | *noz* | *noz* | *noz* | *noz* |
| 2ª pl. | *voz* | *voz* | *voz* | *voz* |
| 3ª pl. | *lor* | *los/las* | *lor* | *se* |

*zo* è il pronome neutro/non-binario di terza persona, codificato nel Core standard.

### Coniugazione verbale

Tre classi regolari: **-AR** (*caminar*), **-ER** (*perder*), **-IR** (*partir*).

| Tempo | je | te | ez/za | noz | voz | lor |
|---|---|---|---|---|---|---|
| **Presente -AR** | *camin* | *camines* | *camine* | *caminom* | *caminez* | *caminen* |
| **Imperfetto -AR** | *caminava* | *caminavas* | *caminava* | *caminavom* | *caminavez* | *caminavem* |
| **Futuro -AR** | *caminaré* | *caminarés* | *caminare* | *caminarom* | *caminaréz* | *caminaren* |
| **Condizionale -AR** | *caminaria* | *caminarías* | *caminaria* | *caminaríom* | *caminaríez* | *caminarien* |

**Participio passato:** *caminat* (-AR) · *perdut* (-ER) · *partit* (-IR)  
**Gerundio:** *caminand* · *perdend* · *partind*

#### Dittongazione accentuale

Quando l'accento cade sulla radice verbale, le vocali toniche dittongano:

- **e** tonica → **ie** (*perder* → *je pierd*, *noz perdom*)
- **o** tonica → **uo** (*poder* → *je puod*, *noz podom*)

Questo è il classico "pattern a ferro di cavallo": dittongano je/te/ez/lor, non noz/voz.

#### Tempi composti

| Tempo | Struttura | Esempio |
|---|---|---|
| Passato prossimo (transitivo) | *ver* + PP | *je vey caminat* |
| Passato prossimo (moto) | *ez* + PP | *ez ez andat* |
| Trapassato | *avev* + PP | *je avev caminat* |
| Futuro anteriore | *verer* + PP | *je verer caminat* |
| Condizionale passato | *veria* + PP | *je veria caminat* |

### Verbi irregolari principali

| Infinito | 1ª sing. pres. | PP | Ausiliare | Note |
|---|---|---|---|---|
| *esser* | *son* | *estat* | — | 3 radici: son-/er-/ser- |
| *aver/ver* | *vey* | *avut* | — | transitivo |
| *andar* | *vai* | *andat* | *ez* | supletismo totale |
| *venir* | *vien* | *vengut* | *ez* | dittongo e→ie |
| *far* | *faz* | *fat* | *ver* | radici fa-/faz-/fec- |
| *dir* | *dis* | *dit* | *ver* | radici dis-/diz-/dic- |
| *poder* | *puod* | *podut* | — | modale, no imperativo |
| *voler* | *vol* | *volut* | — | modale, no imperativo diretto |
| *saber* | *sav* | *sabut* | — | stativo, futuro sincopato *savré* |
| *tener* | *teng* | *tengut* | — | futuro sincopato *tendré* |
| *estar* | *estav* | *estat* | — | stato transitorio e posizione |
| *meter* | *met* | *mist* | — | PP breve, tutti i composti |

### Aspetto verbale

Solis ha un sistema aspettuale completo:

| Fase | Struttura | Esempio |
|---|---|---|
| Imminenza | *estar per* + inf. | *je estar per partir* |
| Inizio | *comezar a* + inf. | *je comez a caminar* |
| In corso | *star* + gerundio | *je star caminand* |
| Continuazione | *seguir* + gerundio | *je seguix caminand* |
| Fine | *laissar de* + inf. | *je laiss de caminar* |

### Negazione e interrogazione

```
Affermativa:  Je camin.          Cammino.
Negativa:     Je non camin.      Non cammino.
Interrogativa: Esque te camines? Cammini?
Inv. interrogativa: Camines-te?  Cammini? (registro formale)
```

### Comparativi

| Tipo | Struttura | Esempio |
|---|---|---|
| Maggioranza | *plus … que* | *Ez ez plus alt que te.* |
| Minoranza | *menos … que* | *Je son menos rapid que lor.* |
| Uguaglianza | *tan … com* | *La citat ez tan grand com Milano.* |
| Superlativo relativo | *art. + plus + agg. + de* | *Ez ez le plus alt de la classa.* |
| Superlativo assoluto | *molt + agg.* o *agg. + -isim* | *Ez ez molt inteligent / inteligentisim.* |

Forme irregolari: *bon → meior → optim* · *mal → peior → pessim* · *grand → maior → maxim*

---

## Decisioni codificate

Alcune questioni grammaticali strutturali sono state risolte definitivamente nel Core standard:

### Condizionale
- **Core:** desinenze **-aria/-eria/-iria** (eredità IT/ES/PT)
- **Solis Fralis:** desinenze **-ev/-evs** (eredità FR, variante esclusiva)

### esser vs estar
- **Parlato:** *ez/esser* copre tutto — la distinzione è facoltativa
- **Scritto formale:** *estar* raccomandato per stati transitori e posizione fisica

### Pronome neutro *zo*
*zo* è il pronome soggetto neutro/non-binario, simmetrico a *ez* (m.) e *za* (f.).

### Accordo del participio passato
- **Invariabile** nei tempi composti attivi (Core standard)
- **Invariabile** nella passiva (Core standard)
- **Obbligatorio** solo per il PP in funzione aggettivale: *la porta avrita*

---

## Registri di lingua

| Registro | Caratteristiche |
|---|---|
| **Colloquiale** | Costruzioni brevi, lessico comune, inversioni facoltative |
| **Standard (Core)** | La norma di riferimento per questo progetto |
| **Formale/accademico** | Subordinate complesse, congiuntivo, lessico tecnico |
| **Giuridico** | Formule fisse, participi assoluti, strutture passive |

---

## Varietà dialettali

Solis Core è la norma di riferimento. Esistono due varietà in sviluppo:

- **Solis Fralis** — variante con influenza francese rafforzata (condizionale in *-ev*, caduta consonanti finali, *on* impersonale)
- **Solis Iberic** — variante con influenza iberica rafforzata (distinzione obbligatoria *esser/estar*, influenza spagnola e portoghese)

---

## Esempi di testo

```
Core: Je non sav dov ez ez andat, ma je sab que ez verer tornar.
IT:   Non so dove è andato, ma so che tornerà.
ES:   No sé dónde fue, pero sé que volverá.
FR:   Je ne sais pas où il est allé, mais je sais qu'il reviendra.
```

```
Core: Le sol se leva supr las montagnas, e le temp era clar e fresc.
IT:   Il sole si levava sulle montagne, e il tempo era chiaro e fresco.
```

```
Proverb: Ki dorm ne prend pesk.
IT:      Chi dorme non piglia pesci.
```

---

## Comparazione con le lingue sorgente

| Lingua | Vicinanza | Principali tratti condivisi |
|---|---|---|
| Italiano | **molto alta** | dittongo *uo*, ausiliare *essere/avere*, congiuntivo, ordine SVO |
| Spagnolo | **molto alta** | dittongo *ie*, plurale *-s*, infinito *-ar/-er/-ir*, *tener que* |
| Portoghese | **alta** | PP *-ut* (≈ *-udo*), comparativi *meior/peior/maior* |
| Catalano | **alta** | PP *-at/-ut*, pronome *je* ≈ *jo*, *molt*, *sempre* |
| Occitano | **alta** | PP *-at/-ut*, sistema verbale medievale, dittongazione |
| Francese | **media** | *je*, *plus*, *jamais*, condizionale Fralis *-ev* |

---

## Come iniziare

1. **Apri `index.html`** nel browser — contiene grammatica interattiva, lessico completo e flashcard
2. **Inizia dalla grammatica base:** articoli → pronomi → verbi regolari *-AR*
3. **Studia la fonetica:** l'accento tonico e la dittongazione sono i due meccanismi più importanti
4. **Espandi con la Grammatica Estesa:** congiuntivo, subordinate, aspetto verbale
5. **Usa il Lessico** come dizionario di consultazione continua (300+ voci con etimologia)

---

## Stato del progetto

Vedi [`STATUS.md`](STATUS.md) per il tracciamento dettagliato. In sintesi:

- ✅ **Grammatica core:** morfologia verbale completa, sistema nominale, pronomi, sintassi
- ✅ **Lessico:** 300+ voci con etimologia, flashcard, campi semantici
- ✅ **Diacronia:** evoluzione dal latino, fonti per ogni scelta morfologica
- 🔄 **Fonetica estesa:** sandhi, prosodia, fonetica emotiva (in sviluppo)
- 🔄 **Varietà regionali:** Fralis e Iberic (in sviluppo)
- ⏳ **Grammatica Estesa v4:** documento unificato (pianificato)

---

## Versione

**Solis v1.0** · 2025  
Lingua Romanza Pianificata

---

*Solis è un progetto aperto. Ogni contributo — correzione, proposta lessicale, testo in Solis — è benvenuto.*
