---
author: @(Autor.name)
email: @(Autor.mail)
language: @(Projekt.shortlang)
title: @(Projekt.title)
subtitle: @(Projekt.subtitle)
www_cover: @(Projekt.wwwCover)
date: @(Monat[heute.month].MMMM) @(heute.year)
version: @(GetShortGITHash "")
icon: @(Projekt.icon)
logo: @(Projekt.logo)
wilhelm1: https://de.wikipedia.org/wiki
toc-title: Inhalt
---


<main>
<div class="jhoTitle" >@(Projekt.title)</div>

<div style="text-align: center;" >@(Projekt.subtitle)</div>


<div style="width: 70%; margin:auto">![](images/@(Projekt.wwwCover))</div>

<div style="text-align: center;" >

@(Autor.name)@(br)
@(Autor.mail)@(br)
Git: @(GetShortGITHash "")@(br)@(br)
Rechtsstand: @(Projekt.Rechtstand)@(br)@(br)
</div>
@include "personalwesen.md"
</main>
