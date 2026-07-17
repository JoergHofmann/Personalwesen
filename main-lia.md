<!--
author: @(Autor.name)
email: @(Autor.mail)
language: @(Projekt.shortlang)
title: @(Projekt.title)
subtitle: @(Projekt.subtitle)
www_cover: @(Projekt.wwwCover)
date: @(Monat[heute.month].MMMM) @(heute.year)
version: @(GetShortGITHash "")
icon: @(Projekt.icon)
date: @(Monat[heute.month].MMMM) @(heute.year)
link: css/jho-lia.css
logo: @(Projekt.logo)
wilhelm1: https://de.wikipedia.org/wiki
-->

# @title

<div style="text-align: center" >@subtitle</div>


<div style="width: 70%; margin:auto">![](/images/@(Projekt.wwwCover))</div>

<div style="text-align: center" >

@author@(br)
@email@(br)
Git: @version@(br)@(br)
Rechtsstand: @(Projekt.Rechtstand)
</div>

@include "personalwesen.md"

