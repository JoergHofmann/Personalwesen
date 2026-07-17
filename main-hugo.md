---
title: @(Projekt.title)
type: home
---

<div style="text-align: center" >@(Projekt.subtitle)</div>


<div style="width: 70%; margin:auto">![](images/@(Projekt.wwwCover))</div>

<div style="text-align: center" >

@(Autor.name)@(br)
@(Autor.mail)@(br)
Git: @(GetShortGITHash "")@(br)@(br)
Rechtsstand: @(Projekt.Rechtstand)
</div>
