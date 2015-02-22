+++
date = "2015-02-22T17:30:00+01:00"
draft = true
title = "Video Games X-Plat con LibGDX"
tags = ["java","libgdx"]
categories = [ "libgdx"]
image = "/images/libgdx.png"
featured = ["Featured"]
+++

Di recente sono venuto a conoscienza di [LibGDX](http://libgdx.badlogicgames.com), una fantastica libreria per lo sviluppo di videogames cross platform in java. La buona notizia è che è completamente free per uso commerciale e non.

Le piattaforme che supporta sono iOS, BlackBerry, Windows, Mac, Linux, Android e HTML5, tutte queste piattaforme sono raggiungibili utilizzando la solita code base, per quanto riguarda la parte HTML5, viene sfruttata la tecnologia [GWT](http://www.gwtproject.org) creata da google per trasformare il codice Java in Javascript.

Come si può intendere dal nome, si tratta di una libreria e non di un game engine, di conseguenza sarà compito dello sviluppatore andare ad implementare certe logiche. Il vantaggio che ci da LibGDX è quello di astrarci dalla piattaforma, lasciandoci liberi dai dettagli di basso livello. Resta comunque la possibilità di accedere alle chiamate OpenGL che vengono esposte dalla stessa permettendoci di andare a creare funzionalità più complesse.

Come libro per la mia formazione ho scelto <a href="http://www.amazon.it/gp/product/1783554770/ref=as_li_tf_tl?ie=UTF8&camp=3370&creative=23322&creativeASIN=1783554770&linkCode=as2&tag=gamec02-21" nofollow>Learning LibGDX Game Development - Second Edition</a><img src="http://ir-it.amazon-adsystem.com/e/ir?t=gamec02-21&l=as2&o=29&a=1783554770" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" /> che dalle recensioni mi sembrava il più adatto. Purtroppo come la maggior parte dei libri del settore è in lingua inglese, ma spero presto di condividere qui con voi, degli articoli in lingua italiana dove andrò a spiegare la basi, come creare un progetto e un mini gioco!