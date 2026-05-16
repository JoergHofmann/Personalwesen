---
author: "@(Autor.name)"
title: @(Projekt.title)
subtitle: @(Projekt.beruf)
www_cover: @(Projekt.wwwCover)
date: @(Monat[heute.month].MMMM) @(heute.year)
git: @(GetShortGITHash "")
icon: @(Projekt.icon)
date: @(Monat[heute.month].MMMM) @(heute.year)
logo: @Projekt.logo
---

# @(Projekt.title)

 

## Arbeits- und Personalrecht

## Lohn und Gehalt

@include "lohn-gehalt.md"
