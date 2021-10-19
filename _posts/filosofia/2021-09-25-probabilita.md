---
layout: post
title:  Nozioni di probabilità
date:   2021-09-25 11:40:16
tags: filosofia
description: Diamo alcune nozioni base di probabilità per poter comprendere al meglio il pensiero filosofico della spiegazione scientifica.
lang: in
ref: prob

---

La prima riflessione filosofica strutturata sulla nozione di probabilità si ha nella prima metà del '600 ad opera di Pascal e Fermat. A riguardo, ricordiamo la celeberimma "Scommessa di Pascal". Secondo  quest'ultimo, il concetto di probabilità era necessario per affrontare questioni che riguardavano l'incertezza sia relativa all'occorrenza di fenomeni (occorrenza nel senso di occorrere, verificazione successiva di eventi) sia relativa ad una scommessa. Vediamo come il concetto di probabilità contenga in sue una duplice valenza: in primo luogo come nozione legata all'andamento di fenomeni ed quindi con un referente empirico, in secondo luogo come la credenza che un fenomeno si verifichi, che invece riguarda la conoscenza dei fenomeni ma non il loro prodursi. A partire da questa distinzione emergono poi diverse interpretazioni sulla nozione di probabilità.[^1]

Arrivati a questo punto è necessario fare anche un'altra distinzione: un conto è il _calcolo_ della probabilità, un altro conto è la sua _interpretazione_. Difatti, il calcolo della propbabilità si compone di regole formali indipendenti dalla interpretazione e risulta univoco. D'altra parte l'interpretazione non è univoca, ce ne sono diverse che andiamo ora ad esplorare.

#### 1. Classica 
Il fondatore dell'interpretazione classica è sicuramente Laplace. È un'interpretazione epistemica, ovvero la probabilità è un certo nostro grado di ignoranza rispetto al verificarsi di un fenomeno. Questa intepretazione si inserisce in un paradigma determinista che fa uso del principio di ragion sufficiente da cui si deduce la causalità assoluta. In questo contesto il demone di Laplace è colui che non ha bisogno della probabilità, ne può fare a meno. Inoltre la probabilità $$P(A)$$ è definita solo in contesti che presentano un numero di esiti ugualmente probabili: questa ipotesi è chiamata "Equipossibilità" degli stati possibili, che formano per l'appunto lo spazio delle possibilità.
#### 2. Frequentista 
La probabilità è la frequenza con cui si verifica $$A$$ relativamente a una determinata classe di riferimento. Il calcolo è il rapporto delle occrrenze ripetute con ripetizioni tendenti all'infinito. Emerge subito il problema dell'evento unico, il quale non ha una classe di riferimento ben definita. Importante in questa interpretazione è la nozione di collettivo casuale, che nasce dalla domanda: che cosa significa "successione casuale"? Per dare un significato a questo concetto è necessario prima definirne un altro, ovvero il concetto di "scelta di posto": da una successione infinita estraggo una sottosuccessione basandomi su una regola matematica dipendente dall'ordine e non dal valore dell'attributo estratto. Un collettivo allora è causa se i rapporti frequentisti non dipendono dalle sottosuccessioni. L'approccio frequentista è empirico e oggettivo: la probabilità è una caratteristica dei fenomeni che cerco di cogliere con ripetute osservazioni tramite analisi empirica. In tale contesto, per risolvere il problema del caso singolo serve un'interpretazione diversa.
#### 3. Propensionismo
Tale interpretazione è dovuta a Popper[^2] e stabilisce che le probabilità vanno viste come propensioni/tendenze/capacità dell'apparato sperimentale a generare determinate frequenze. La probabilità **NON** è la frequenza, è la capacità di generare frequenze. Noi non osserviamo la probabilità, io osservo la tendenza a produrre certe frequenze. La concezione probabilistica si sposta su un piano metafisico. La frequenza è associata sempre a una successione di eventi; la propensione invece può essere associata anche a un singolo evento. Per Popper le propensioni sono fisicamente reali come le forze Newtoniane [^3]. Per molti questa è una finta soluzione: quando devo esprimere la probabilità tramite un numero, come lo ricavo da questa interpretazione? Abbiamo sembre bisogno dell'interpretazione frequentista. Chi invece la difende pensa che la capacità propensionistica sia una proprietà intrinseca ma una volta che si prova a calcolarla questa collassi su un calcolo di tipo frequentista. [^4] Inoltre Popper distingue tra enunciati probabilistici che esprimono propensioni e che sono congetturali da enunciati statistici che esprimono frequenze e possono essere usati per un controllo sperimentale.
#### 4. Logica 
L'interpretazione logica asserisce l'esistenza di una relazione logica tra i dati, intesi come evidenze, e le ipotesi. Questa interpretazione fa uso della logica induttiva come logica dei gradi di credenza razionale. È un'interpretazione epistemica e oggettiva. In base all'evidenza il valore della probabilità è univocamente determinato. In sostanza, la probabilità è un sottoinsieme della logica una volta fissata l'evidenza, nel senso che le proposizioni probabilistiche sono non deduttive/dimostrative. Essendo la conoscenza relativa all'informazione disponibile è imperfetta, la probabilità è in rapporto a un certa conoscenza disponibile. Data quest'ultima però la probabilità è univocamente determinata: fissata l'evidenza le relazioni logiche sono un fondamento oggettivo. Un promotore di questa interpretazione è sicuramente Rudolf Carnap: egli da due nozioni: probabilità 1, il grado di conferma / probabilità logica, probabilità 2, probabilità frequentista. La probabilità 1 rappresenta il supporto induttivo a favore di una ipotesi fissata in base all'evidenza. La misura di quanto sono possibili è oggetto della logica induttiva.
#### 5. Soggettiva
La probabilità è il grado di credenza (degree of belief) nei confronti di una certo evento $$A$$. Il valore di questa probabilità è soggettiva, ovvero stesse evidenze possono portare a valori diversi di $$P(A)$$. Non è però un "anything goes": siamo esseri razionali che devono tenere conto dell'evidenza nel formulare il valore di $$P(A)$$. Questa intepretazione è in polemica con l'interpretazione logica in quanto si basa su un fondamento psicologico e i due principali esponenti di tale corrente sono Ramsey e De Finetti. La probabilità di diversi eventi $$A,B,C$$ devono essere coerenti: questo è l'unico criterio rigoroso. De Finetti dà luogo a un soggettivismo molto radicale: secondo lui non esistono probabilità sconosciute e non esistono probabilità vere o false perché tutte le probabilità sono soggettive. Tuttavia l'evidenza deve, in quanto esseri razionali, influenzarci nella determinazione della probabilità. Il successo delle mie previsioni stabilisce la correttezza della mia determinazione.

Per completezza, è necessario fare riferimento anche alla impostazione assiomatica della probabilità dovuta a Kolmogorov. Questa è un'impostazione formale che pertanto prescinde dall'interpretazione. Si basa su tre principi, ovvero

$$\begin{gather} 
P(A)\geq 0      \nonumber \\
\text{A tautologia} \iff P(A) = 1 \nonumber \\
\text{A,B mutualmente esclusivi} \Longrightarrow P(A \lor B) = P(A)+P(B)   \nonumber
\end{gather}$$

Inoltre $$A$$ e $$B$$ sono indipendenti $$ \iff P(A\vert B) = P(A) \land P(B\vert A) = P(B)$$.

Definiamo un concetto importante nell'analisi del filosofo Salmon (vedere mettere link): il concetto di rilevanza positiva (negativa) di $$B$$ rispetto a $$A$$ si ha quando $$P(A\vert B) > P(A)$$ ($$P(A\vert B) < P(A)$$), $$B$$ è rilevante positivamente (negativamente) rispetto a $$A$$ se la probabilità di verificarsi di $$A$$ sapendo che si è verificato $$B$$ è maggiore (minore) della probabilità del verificarsi del solo $$A$$.

Un'altro concetto importante è quello di probabilità composta $$P(A\cdot B) = P(A) P(B\vert A) = P(B)P(A\vert B)$$ e nel caso di eventi indipendenti $$P(A\cdot B) = P(A) P(B)$$. Da questa semplice definizione abbiamo la regola di Bayes (1763) che da luogo a tutto un filone teorico sulla probabilità che prende il nome di ragionamenti Bayesiani. Il teorema e il filone teorico sono utili per capire come cambia la probabilità di una certa asserzione al aumentare o diminuire dell'evidenza. In sostanza il teorema è il seguente $$\begin{gather}P(H\vert E) = \frac{P(H\cdot E)}{P(E)}\end{gather}$$ in cui $$H$$ è un'ipotesi ed $$E$$ un'evidenza.[^5]

---
Riferimenti bibliografici
---

[^1]: Riferimento bibliografico: Hacking "Emergence of Probability".
[^2]: Riferimento Bibliografico: "Un mondo di propensioni"
[^3]: Domanda: viene spontaneo chiedersi allora come vengono calcolate queste propensioni
[^4]: Domanda: come fanno ad essere fisicamente reali se sono le frequenze a determinare il valore della propensione?.
[^5]: Riferimenti Bibliografici sulla probabilità: Gillies, Phylosophycal Theories of Probability (parte finale tendente al propensionismo), Galavotti (tendente al soggettivismo), Gigerenzer, Quando i numeri ingannano (common sense logic al confronto con la probabilità formale)



