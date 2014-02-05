#Il nuovo 40k

Questo documento deve spiegare come installare il nuovo blog 40k.

##Obiettivo

```
Home page
|
|__ blog loop
|  |
|  |__ post blog
|
|__ category loop
|   |
|   |__ single category
|
|__ libri (elenco totale)
|   |
|   |__ collana
|       |
|       |__ libro songolo
|
|__ autori
|   |
|   |__ gruppo autori
|   |
|   |__ autore singolo
|
|__ special
|
|__ about
|   |
|   |__ la nostra storia
|   |
|   |__ vision
|   |
|   |__ team
|   |
|   |__ dicono di noi
|
|__ contattaci
|
|__ sei un autore? scrivi

```

##Setup iniziale

Prima considerazione importante: **Jekyll non richiede alcun database**. Questo semplifica di molto il lavoro. Non
avere il database significa anche questo: **sito più veloce**.

###Installare Xcode

go to Downloads and install Command Line Tools.

###Installare rvm

Rvm sta per *Ruby Version Manager*. Se dovessimo usare più installazioni Ruby, questa è la risposta. Non è il nostro
caso, ma è bene essere ordinati.

Per installarlo, accedi al terminale e digita:

    \curl -sSL https://get.rvm.io | bash -s stable

A questo punto, installa ruby usando rvm:

    rvm install 2.1.0

E comincia a usarlo:

    rvm use 2.1.0

###Installare Jekyll

Ovviamente, [qui trovi tutto](http://jekyllrb.com/). Ma facciamola facile.

    gem install jekyll

E poi

####Dipendenze necessarie####

