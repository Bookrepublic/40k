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

- brew instal imagemagick
- gem install mini_magick
- gem install jekyll-minimagick
- gem install nokogiri json

###Fix per Jekyll

fixed in serve.rb by adding s.config.store(:DirectoryIndex, s.config[:DirectoryIndex] << "index.xml") after s = HTTPServer.new(webrick_options(options)).

###Media query

@media (max-width: @screen-xs-min){  }
@media (max-width: @screen-sm-min) and (min-width: (@screen-xs-min + 1)) {  }
@media (max-width: @screen-md-min) and (min-width: (@screen-sm-min + 1)) {  }
@media (max-width: @screen-lg-min) and (min-width: (@screen-md-min + 1)) {  }
@media (min-width: @screen-lg-min) {  }

# Deploy

Loggarsi come deploy sul server 'wordpress.bookrepublic.it'.

```
cd /var/www/40k.it/source
git pull
rake generate
```
