---
author: "Matteo Scurati"
date: 2014-03-07
layout: post
title: "Quella volta che abbiamo deciso di fare un nuovo sito in due settimane"
categories:
- 40k
- cose di casa
description: "Il racconto di quello che abbiamo fatto per creare il nuovo sito di 40k. L'influenza di Matteo Papadopoulos, la scelta degli strumenti e le fonti di ispirazione"
cover: /static/img/lentree_du_christ_ a_bruxelles.jpg
image: 
- url: "static/img/40K_nuovo_sito.jpg"
  caption: "fonte http://www.slantmagazine.com/assets/film/willywonkathechocolatefactory.jpg"
  alt: "Ora 40k ha un nuovo sito"
- url: "static/img/40k_mai_incrociare_flussi.jpg"
  caption: "fonte http://www.fanpage.it/mai-incrociare-i-flussi-di-coscienza/ Rip Harold Ramis"
  alt: "Mai incrociare i flussi"
- url: "static/img/40k_puffo.jpg"
  caption: "fonte http://images2.fanpop.com/image/photos/10200000/I-hate-kites-grouchy-smurf-10232278-450-328.jpg"
  alt: "Io odio i widget"
tag:
---

{{ page.image | first | map: 'url' | escape }}

Due settimane fa, [Daria](https://twitter.com/filodaria) mi ha chiesto un nuovo sito per 40k. Qualche giorno prima, [Matteo Papadopoulos](http://www.cantierecreativo.net/it/chi-siamo) mi ha parlato di [Jekyll](http://jekyllrb.com/).

* * *
<div id="fb-root"></div> <script>(function(d, s, id) { var js, fjs = d.getElementsByTagName(s)[0]; if (d.getElementById(id)) return; js = d.createElement(s); js.id = id; js.src = "//connect.facebook.net/en_US/all.js#xfbml=1"; fjs.parentNode.insertBefore(js, fjs); }(document, 'script', 'facebook-jssdk'));</script>
<div class="fb-post text-center" data-href="https://www.facebook.com/matteo.scurati/posts/10202938808773188" data-width="500"><div class="fb-xfbml-parse-ignore"><a href="https://www.facebook.com/matteo.scurati/posts/10202938808773188">Post</a> by <a href="https://www.facebook.com/matteo.scurati">Matteo Scurati</a>.</div></div>
* * *

Matteo Papadopoulos è un bellissimo ragazzo padre e, soprattutto, un bravissimo web designer. Così mi sono chiesto cosa fosse mai Jekyll.

<blockquote>
    <p>Jekyll is a simple, blog-aware, static site generator. It takes a template directory containing raw text files in various formats, runs it through Markdown (or Textile) and Liquid converters, and spits out a complete, ready-to-publish static website suitable for serving with your favorite web server.</p>
    <footer>dal sito di <a href="http://jekyllrb.com/docs/home/">Jekyll</a></footer>
</blockquote>

Da quel giorno, è amore (verso Jekyll). Perché?

1. **Jekyll è semplice**;
2. **Jekyll è veloce** come può esserlo un sito statico;
3. **il markup di [Liquid](https://github.com/Shopify/liquid/wiki/Liquid-for-Designers) ha una vaga somiglianza con quello di [Django](https://www.djangoproject.com/)** che abbiamo imparato a conoscere con la libreria di [Bookrepublic](http://www.bookrepublic.it/) (sì, lo so, non c'entrano niente l'uno con l'altro, ma la sintassi è davvero simile).

{% figure_img img-responsive lazy 0 caption %}

A queste considerazioni se ne aggiungono altre due, entrambe frutto del lavoro svolto fino a qui assieme a Daria e [Giovanni](https://twitter.com/CrazyDesign84) all'interno di Bookrepublic.

1. Scrivere un post in Jekyll significa scrivere in markdown (ok, non solo, ma soprattutto). Negli ultimi mesi, questo è stato lo strumento utilizzato per condividere documenti e progetti. Aldilà della facilità d'uso, scrivere in markdown obbliga a un certo ordine mentale che - almeno in alcuni casi - corrisponde a un certo ordine di idee;
2. il codice di questo nuovo progetto vive all'interno di un repository di Github. Oltre ai progetti più complessi (la libreria di Bookrepublic, il servizio di distribuzione Exlibris, il Reader etc.) abbiamo utilizzato Git per gestire codice in qualunque forma. In altri termini, Git non è, grazie a Dio, un perfetto sconosciuto all'interno del team.

##Cosa abbiamo deciso di inserire all'interno del sito di 40k

Da un lato il blog, dall'altro il catalogo. Lapalissiano, ma non lo era stato fino a ora. La community di autori makers di 40k Unofficial si sta allargando sempre di più (ne parleremo, per ora accontentatevi di [questa pagina](http://40k.it/diventa_autore/)): gestire, come fatto fino a ora, il catalogo attraverso pagine di un blog Wordpress non ci bastava più.

{% figure_img img-responsive 1 caption %}

Ora i flussi sono separati: da un lato la nostra comunicazione (fatta di tanta cialtronaggine, non crediate) dall'altro il catalogo e gli autori.

###Ma allora potevate continuare a usare Wordpress

Sì, è vero. Ma anche no. [Wordpress](http://wordpress.com/) *non* è *la* scelta nel caso della pubblicazione di blog o siti. O meglio, non lo è per noi. È una possibile, ottima, consolidata scelta. Ma non l'unica. Ora, io non amo Wordpress e temo di essere ricambiato, e se ad esempio in questo momento mi chiedeste "e allora come devo farlo il mio blog?", ecco, io vi risponderei dicendo [**Ghost**](https://ghost.org/). Ma Ghost è ancora troppo giovane per un sito che includa più autori e diverse pagine. Non va bene, insomma.

Del resto, la verità è questa: abbiamo giocato. Tralasciamo le tonnellate di studi etologici che ci ricordano come la nostra specie apprenda giocando e concentriamoci su un punto: per il nostro team **provare** è fondamentale. Giocare, sperimentare, imparare. Non ne abbiamo sempre il tempo e a volte non ne abbiamo neppure la forza, ma quando lo spazio c'è, allora perché no?

In definitiva: Wordpress è bello, Jekyll lo è altrettanto, e siamo davvero felici di usare l'uno in alcune occasioni e l'altro per questo sito.

##Ma il blog è molto, troppo simile a Medium!

Sì, lo so. E, a dire il vero, è molto simile anche al tema di default di Ghost. Ma non è un problema. [Medium](https://medium.com/) è bello, Ghost è bello. Averci avuto più tempo, chissà, ora avremmo rivoluzionato il mondo del web design, ma per ora ci siamo solo largamente ispirati a chi, in rete, sta facendo un grandissimo lavoro.

Direte: ma mancano i classici widget di un blog.

{% figure_img img-responsive 2 caption %}

Io odio i widget, non ne capisco il senso. Ok, generare più traffico all'interno del sito. Ok, far rimanere il lettore all'interno del nostro mondo. Ma all'alba del 2014 e con un mondo popolato da Social Network, ha davvero senso pensare a 40k come il sito di 40k? Non credo: 40k è la somma dei suoi elementi ovunque in rete: blog, social network, ebook, autori, lettori. Credere che per essere in 40k si debba essere sul suo sito significa avere capito poco - io credo - di cosa significhi oggi essere online.

Per questo motivo, arriveranno, probabilmente, articoli correlati e piccoli altri orpelli, ma per ora il blog che vogliamo è esattamente quello che sta facendo il team di Medium: un luogo che racconti storie.

##Ma è molto, troppo simile a Boostrap!

Sì, lo so. Abbiamo usato [questo framework](http://getbootstrap.com/). Abbiamo messo le mani qua è là per modificare alcuni stili, abbiamo lavorato su alcune classi e, in maniera assolutamente disordinata, creato nuovi elementi da usare all'occorrenza.

Vi ho detto che avevamo due settimane per realizzare il sito, vero?

In definitiva, Bootstrap è così veloce. Ma così veloce. Ancora mi emoziono.

##Cosa abbiamo usato

Anzitutto: non è detto che non si renda il repository pubblico. In fin dei conti, non nascondiamo nulla e sarebbe bello che altri contribuissero a migliorare questo progetto.

Principalmente:

1. Jekyll;
2. Boostrap;
3. Font Awesome.

##Cosa useremo

Non lo sappiamo ancora. Di certo, il suddetto Matteo Papadopoulos mi sta instillando la convinzione che [Sass](http://sass-lang.com/) sia da preferire a Less (dove questa volta ci siamo adagiati) e che abbia senso scrivere di elementi e classi coltivando un'insana passione per [BEM](http://csswizardry.com/2013/01/mindbemding-getting-your-head-round-bem-syntax/). Non credo ne usciremo vivi.
