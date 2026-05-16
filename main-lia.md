<!--
author: @(Autor.name)
email: @(Autor.mail)
language: @(Projekt.shortlang)
title: @(Projekt.title)
subtitle: @(Projekt.ihkBeruf)
www_cover: @(Projekt.wwwCover)
date: @(Monat[heute.month].MMMM) @(heute.year)
version: @(GetShortGITHash "")
icon: @(Projekt.icon)
date: @(Monat[heute.month].MMMM) @(heute.year)
link: css/jho-lia.css
logo: @(Projekt.logo)
-->

# @title

<div style="width: 70%; margin:auto">![](/images/@(Projekt.wwwCover))</div>

<div style="text-align: center" >

@author@(br)
@email@(br)
Git: @version

</div>

@include "wiederholung.md"

