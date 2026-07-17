---
title: @(Projekt.title)
layout: landing
weight: 100
bookToC: true
bookCollapseSection: true
---

<div style="text-align: center" >
<h1>@(Projekt.title)</h1>
@(Projekt.subtitle)</div>


<div style="width: 70%; margin:auto">![](images/@(Projekt.wwwCover))</div>

<div style="text-align: center" >
@(Autor.Firma.name)@(br)
Inh.: @(Autor.name)@(br)@(br)
@(Autor.Firma.strasse)@(br)
@(Autor.Firma.plz) @(Autor.Firma.ort)@(br)@(br)
@(Autor.Firma.tel)@(br)
@(Autor.Firma.mail)@(br)@(br)
@(Monat[heute.month].MMMM) @(heute.year)@(br)
Version: @(GetShortGITHash "")@(br)
Rechtsstand: @(Projekt.Rechtstand)@(br)@(br)
{{<button href="/docs/">}}Weiter{{</button>}}

</div>
