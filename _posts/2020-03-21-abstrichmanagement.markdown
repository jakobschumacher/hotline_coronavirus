---
layout: single
title: Abstrichmanagement 
date: 2020-03-21 08:00:00 +0300
description: Hintergrundwissen zu Infektionsepidemiolgoie zu Sars-Cov-2 # Add post description (optional)
img: swab.jpg # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: [Eingabe]
---
<div class="mermaid">
graph TD
     1[Erfassung des Sachverhalts]
     2a[Covid-Fall]
     2b[Zuständigkeit Gesi<br />Weitergabe an 5030]
     3a[Medizinisches Personal]
     3b[Zuständigkeit Gesi<br />Weitergabe an 5030]
     4a[Befund Auskunft]
     4b[Zuständigkeit Fr. Sackschweski<br />Weitergabe an 5069]
     5a[Anfrage nicht zu <br /> Coronavirus]
     5b[Zuständigkeit GesSekr<br />Weitergabe an 5079]
     6a[Anfrage zu <br />Unterbringung<br />Nahrungsmittel]
     6b[Zuständigkeit Dudey<br /> Weitergabe an ]
     7a[Anfrage zu Ehrenamtlicher Tätigkeit]
     7b[Zuständigkeit <br />Ehrenamtsmangement <br /> Weitergabe an ]
     8a[Eigene Zuständigkeit]
     
     
     1--&gt;2a
     2a--Ja--&gt;2b
     2a--Nein--&gt;3a
     3a--Ja--&gt;3b
     3a--Nein--&gt;4a
     4a--Ja--&gt;4b
     4a--Nein--&gt;5a
     5a--Ja--&gt;5b
     5a--Nein--&gt;6a
     6a--Ja--&gt;6b
     6a--Nein--&gt;7a
     7a--Ja--&gt;7b
     7a--Nein--&gt;8a
     
    </div>
