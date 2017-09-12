---
title:  "Phalcon and Functional Programming"
layout: post
description: Research based on functional programming and how could this help in development of Phalcon projects.
comments: true
---

> Those who know don't talk.
> Those who talk don't know.

I would like you to note that all subprojects we have used in Phalcon e.g.:

+ **Zephir Parser**
+ **Volt Parser**
+ **PHQL Parser**
+ **Annotation Parser**

were created with the use of [C89](https://en.wikipedia.org/wiki/ANSI_C#C89).
Time showed that the community isn’t interested in these projects support.
It turned out that there are no enthusiasts with professional knowledge of
[Zend Engine](https://en.wikipedia.org/wiki/Zend_Engine) API, who wanted to
take part in these projects development.

In this latter year I study capabilities of such functional languages as
[Lisp](https://en.wikipedia.org/wiki/Lisp_(programming_language)),
[Haskell](https://en.wikipedia.org/wiki/Haskell_(programming_language)),
[Idris](https://en.wikipedia.org/wiki/Idris_(programming_language)) and
[ATS](https://en.wikipedia.org/wiki/ATS_(programming_language)). I wonder how
could these help in development of our projects. I consider a possibility of
creating new-brand software – parsers, code generators, static and semantic
analyzers – using functional languages. If anyone wants to object to my choice
of languages I would say that in view of lacking community’s support there is
no difference what language these projects are and could be written in.
