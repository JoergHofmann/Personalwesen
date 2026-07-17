---
context-lang: @(Projekt.contextlang)
title: @(Projekt.title)
subtitle: @(Projekt.subtitle)
cover: @(Projekt.pdfCover)
date: @(Monat[heute.month].MMMM) @(heute.year)
git: @(GetShortGITHash "")
author: @(Autor.name)
---




# @(Projekt.title)

@include "personalwesen.md"

