---
author: Roberto Zanasi
date: 2014-03-19
layout: post
title: "Un punto fermo: l'appendice"
categories:
- altramatematica
description:
cover: /static/img/appendice_zanasi.jpg
image: 
- url:
  caption:
  alt:
- url:
  caption:
  alt:
tag:
---
<i>O di come l'apprendista mostri al Vero Matematico un errore nella
dimostrazione di un teorema; di come una apparente complicazione si
riveli una semplificazione; del dialogo impossibile tra due universi
paralleli.</i>


"Senti, stavo riguardando i teoremi sul gioco del quindici..."

"Sì? C'è qualcosa di non chiaro?"

"Eh, sì, il teorema dello spostamento verticale."

"Dimmi, cosa non hai capito?"

"Tu dici che quando spostiamo il buco, modifichiamo l'invariante di 3,
in più o in meno."

"Esatto, spostando il buco si cambia la posizione di una tessera
rispetto ad altre tre, e quindi l'invariante viene modificato di tre
unità."

"Ecco, sì, però stavo pensando a questo esempio:"

<tt> 1 2 3 5
4 6 7 .
</tt>

"Cos'ha che non va?"

"Dimmi se ho capito bene: ora c'è solo una coppia di numeri che non
sono nell'ordine naturale, vero?"

"Certo, la coppia (5,4)."

"Ok. Allora, se sposto il buco verso l'alto, il 5 scende di una
posizione e ottengo questa configurazione:"

<tt> 1 2 3 .
4 6 7 5
</tt>

"Vero, e 5 ha cambiato posizione rispetto alle tre tessere successive,
cioè 4, 6 e 7."

"Adesso però le coppie che non sono nell'ordine naturale sono (6,5) e
(7,5): sono solo due."

"..."

"Ho sbagliato?"

"..."

"Cosa succede? Stai bene?"

"..."

"Non ho sbagliato? HAI SBAGLIATO TU?"

"Argh."

"Eh eh eh."

"Ma non c'è niente da ridere!"

"Ok, scusa, eh eh, no scusa, davvero."

"Divertente, eh?"

"Un pochino. Vedere un Vero Matematico in difficoltà è per me una
situazione nuova, vorrei godermela a pieno."

"Uff. Fammi pensare."

"Ok."

"..."

"Cosa?"

"Ma devi proprio stare lì a guardare?"

"Come dicevo, mi sto divertendo abbastanza..."

"Guarda che non so quanto tempo ci vorrà non so se riuscirò a
rimediare non voglio nessuno che mi guardi via via VIA DI QUA CHE..."

"Va bene, va bene, ora vado."

[Passa un po' di tempo. Non diciamo quanto per non offendere
ulteriormente la dignità del Vero Matematico]

"Ce l'ho fatta!"

"Hai rimediato all'errore?"

"Sì, ho capito come funziona adesso."

"Oh, bene. Me lo racconti?"

"Certo. Dobbiamo modificare la definizione dell'invariante, quella di
prima non andava bene."

"Me ne sono accorto... Come sarebbe questa nuova definizione?"

"Dobbiamo, come prima, calcolare il numero di coppie che non sono
nell'ordine naturale, poi dobbiamo aggiungere a questo valore il
numero della riga in cui si trova il buco."

"Ah. Partiamo da 0 o da 1?"

"Non importa, basta mettersi d'accordo. Diciamo che numeriamo le righe
da 1 a 4, dall'alto verso il basso, va bene?"

"Ok. Basta così?"

"No, alla fine del numero che abbiamo ottenuto ci interessa la parità."

"Nel senso che dobbiamo dire solo se è pari o dispari?"

"Esattamente. Supponiamo che l'esempio che hai fatto tu fosse relativo
alle prime due righe. Te lo riscrivo:"

<tt> 1 2 3 5
4 6 7 .
</tt>

"Provo a fare il calcolo: c'è solo una coppia di numeri che non sono
nell'ordine naturale, e cioè (5,4). E il buco si trova nella riga
numero 2. Quindi 1 più 2 fa 3."

"E 3 è un numero dispari: questo è l'invariante. Il teorema dello
spostamento verticale, nella versione corretta, dice che se spostiamo
il buco allora la parità del numero che si ottiene sommando il numero
di coppie che non sono nell'ordine corretto con il numero di riga in
cui si trova il buco non cambia."

"Aspetta che provo, che non ho mica capito bene."

"Se sposti il buco in alto, facendo scendere il 5, ottieni questa
configurazione:"

<tt> 1 2 3 .
4 6 7 5
</tt>


"Provo a rifare i conti: le coppie che non sono nell'ordine naturale
ora sono due: (6,5) e (7,5), mentre il buco si trova ora nella riga 1.
In effetti 2 più 1 fa ancora 3."

"Non è importante che si ottenga sempre 3, come è successo ora: ci
interessa il fatto che il risultato sia ancora dispari."

"Va bene. E mi assicuri che questo fatto sia sempre vero, per
qualunque tipo di movimento? Non è che hai fatto un altro errore, eh?"

"Ti diverti a infierire, eh?"

"Un pochino..."

"Comunque sia, ora provo a convincerti, tu mi dirai se la spiegazione
ti convince."

"Va bene, vai."

"Come abbiamo già detto, spostare il buco di una posizione in
verticale significa modificare la posizione di una tessera rispetto
soltanto ad altre tre."

"Mi sembrava giusto anche prima, ma poi ho trovato quell'esempio in
cui questo ragionamento non funzionava."

"In realtà il ragionamento fino a qui funziona, sono le conclusioni a
essere sbagliate. Se sposti il buco verso l'alto, sposti una tessera
verso il basso: si modifica la posizione di quella tessera rispetto
alle tre successive, vero?"

"Vero, ne supero tre. È anche vero che se sposto una tessera verso
l'alto modico la posizione di quella tessera rispetto alle tre
precedenti."

"Molto bene. Ora, per fissare le idee, immaginiamo di spostare il buco
verso l'alto, cioè una tessera verso il basso. Quello che succederà
spostando il buco verso il basso sarà analogo."

"Bene, andiamo avanti."

"Ora, se indichiamo con <i>A</i> la tessera che spostiamo verso il
basso, con <i>B</i>, <i>C</i> e <i>D</i> le tre tessere successive, e
con <i>X</i> il buco, passeremo da una configurazione del tipo
...<i>ABCDX</i>... a questa: ...<i>XBCDA</i>..."

"Fammi capire... Potremmo avere uno schema di questo tipo:"

<tt> A B C D
. E F G
</tt>

"Che diventa:"

<tt> . B C D
A E F G
</tt>


"Ok, ci sono, le tessere che ho chiamato <i>E</i>, <i>F</i> e <i>G</i>
non contano, rispetto a quelle non è cambiato niente. E se <i>A</i>
non si trova nella prima colonna?"

"Prova a vedere che succede."

"Vediamo, se ho uno schema fatto così cosa cambia?"

<tt> Z A B C
D . E F
</tt>

"Succede che ottieni questo:"

<tt> Z . B C
D A E F
</tt>

"Ho capito, le tessere <i>Z</i>, <i>E</i> e <i>F</i> sono inutili,
cambia solo l'ordinamento tra <i>A</i>, <i>B</i>, <i>C</i>, <i>D</i> e
il buco. Succede lo stesso anche se <i>A</i> si trova nelle altre due
colonne, suppongo."

"Esatto, se vuoi puoi fare i disegni anche per quei due casi, ma sono
perfettamente analoghi. Comunque puoi verificarlo, non troverai altri
errori..."

"Eh eh."

"Se vuoi vado avanti, quando ha finito di ridere."

"Ok, scusa, vai pure."

"Allora, vediamo quello che può accadere. L'errore nella prima
dimostrazione stava nel fatto che avevo immaginato che automaticamente
il numero di coppie non nell'ordine naturale cambiasse di 3, ma non è
così. Se <i>B</i>, <i>C</i> e <i>D</i> sono tutte maggiori di
<i>A</i>, allora nello spostamento effettivamente il numero di coppie
non nell'ordine naturale cambia di 3, numero dispari."

"E fin qua siamo d'accordo."

"Dato che il numero di riga del buco è cambiato di 1, dispari pure
lui, la parità del nostro nuovo invariante non cambia"

"Ho capito. Non importa se il buco va verso l'alto o verso il basso,
sia 3 + 1 che 3 - 1 sono numeri pari, e la parità non cambia."

"Se sposti il buco nell'altra direzione, o se <i>B</i>, <i>C</i> e
<i>D</i> sono tutte minori di <i>A</i>, avresti un -3 al posto di un
+3, e non cambierebbe niente comunque."

"Giusto anche questo. È chiaro, andiamo avanti."

"Se solo una delle tre tessere è maggiore di <i>A</i>, succede invece
qualcosa di diverso."

"Diciamo che sia <i>B</i> maggiore di <i>A</i>?"

"Per esempio, sì. Nella configurazione ...<i>ABCDX</i>... abbiamo due
coppie che non sono nell'ordine naturale, e cioè (<i>A</i>,<i>C</i>) e
(<i>A</i>,<i>D</i>)."

"Vero. Quando spostiamo il buco otteniamo ...<i>XBCDA</i>..., in cui
rimane solo la coppia (<i>B</i>,<i>A</i>)"

"Quindi il numero di coppie con valori sballati..."

"I Veri Matematici le chiamano <i>inversioni</i>."

"Ok, il numero di inversioni cambia di una unità."

"Potrebbe essere un cambiamento in positivo o in negativo, ma comunque
di un valore dispari..."

"E se a questo aggiungo un cambiamento di una unità nel numero di riga
in cui si trova il buco, ho di nuovo una modifica che non fa cambiare
la parità del numero di inversioni sommato al numero di riga. Bello."

"Vero. Supponiamo ora che due delle tre tessere siamo maggiori di <i>A</i>."

"Diciamo <i>B</i> e <i>C</i>?"

"Va bene. Prima del movimento in ...<i>ABCDX</i>... hai una sola
inversione, (<i>A</i>,<i>D</i>)."

"Dopo il movimento ho ...<i>XBCDA</i>..., in cui le inversioni sono
(<i>B</i>,<i>A</i>) e (<i>C</i>,<i>A</i>). Ancora una volta si
modificano di un valore 1, e se a questo sommo il numero di riga del
buco ottengo nuovamente un numero pari."

"Proprio così, e se sei convinto possiamo dire che il teorema è
finalmente dimostrato."

"Sì, mi pare convincente, anche se complica la dimostrazione un po'."

"In realtà, se ci pensi bene, grazie a questo teorema puoi fare a meno
del teorema del ritorno."

"Uhm, perché?"

"Perché ora non ti interessa più il fatto che il buco ritorni alla
posizione iniziale. Mi spiego meglio: per risolvere il problema
proposto da Loyd il buco deve tornare al suo posto, ma quello che ci
fa capire questo nuovo invariante è che, qualunque movimento tu
faccia, la parità di inversioni più numero di riga del buco non
cambia, e quindi esistono solo due tipi di configurazioni, quelle
<i>pari</i> e quelle <i>dispari</i>. È come se ci fossero due
universi, e con le tue mosse tu non potrai mai passare da un universo
all'altro. La posizione proposta dal quesito di Loyd, con una sola
inversione, e quella con tutti i numeri in ordine, appartengono a due
universi diversi. Nessuna mossa potrà farci passare da uno all'altro"

"Hai ragione, così mi pare anche più bello."

"Ti aggiungo un'ultima considerazione: per posizionare le quindici
tessere (più il buco) del gioco del Quindici hai 16! possibili modi
per farlo"

"Sono le permutazioni di 16 elementi, vero?"

"Esatto. Sono 20.922.789.888.000 possibilità."

"Wow."

"Metà di queste sono risolvibili, metà sono fregature come quella
proposta da Loyd."

"Quindi se smonto il mio gioco del Quindici devo poi stare attento a
rimontarlo bene..."

"Esatto. Perché la sfiga ci vede benissimo..."

"Anche nel trovare gli errori?"

"..."